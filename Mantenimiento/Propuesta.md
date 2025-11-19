# 1. Tipo de Mantenimiento Propuesto
**Correctivo y Preventivo**

---

# 2. Justificación

## Mantenimiento Correctivo
Se debe corregir una falla lógica en el proceso de gestión de préstamos (**RF2**). Actualmente, el sistema permite registrar un préstamo incluso cuando el libro ya está en estado **"prestado"**, generando inconsistencias en la base de datos y riesgos operativos.

## Mantenimiento Preventivo
Para mejorar la estabilidad del sistema y evitar futuros errores, es necesario reforzar el módulo de devoluciones (**RF3**). Esto permitirá asegurar que cada devolución actualice correctamente el estado del libro a **"disponible"**, evitando errores de estado que afecten la operación de la biblioteca.

---

# 3. Tareas Clave

## Validación Correctiva (RF2)
- Implementar una validación que impida registrar un préstamo si el libro no está en estado **"disponible"**.
- Incluir mensajes de error claros cuando la solicitud sea rechazada por falta de disponibilidad.
- Garantizar que el sistema registre el intento fallido si es necesario para auditoría.

## Fortalecimiento Preventivo (RF3)
- Revisar y actualizar la función de devolución para asegurar que el estado del libro cambie siempre a **"disponible"**.
- Identificar y manejar casos límite como devoluciones duplicadas o libros ya disponibles.
- Implementar registros de auditoría para verificar cada cambio de estado.

---
