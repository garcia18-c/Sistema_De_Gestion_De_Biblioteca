# 1. Investigación: Uso de Markdown en Proyectos de Software

## 1.1. ¿Qué es Markdown y por qué se utiliza?

### 1.1.1. Definición
Markdown es un **lenguaje de marcado ligero (LML)** diseñado para permitir escribir texto con formato utilizando una sintaxis simple, legible y basada en texto plano.  
Su objetivo es que el contenido sea:

- Fácil de leer incluso sin ser procesado.
- Fácil de convertir a HTML u otros formatos.
- Ideal para documentación técnica.

### 1.1.2. Usos en el Desarrollo de Software
Markdown es ampliamente utilizado en proyectos de software por las siguientes razones:

- **Legibilidad:** Permite crear documentación clara sin herramientas complejas.
- **Portabilidad:** Funciona en plataformas como GitHub, GitLab, Bitbucket, VSCode, etc.
- **Estandarización:** Es el formato universal para `README.md`, manuales, especificaciones y documentación técnica.
- **Control de Versiones:** Al ser texto plano, facilita el seguimiento de cambios en Git.

---

## 1.2. Ejemplo Práctico de Uso de Markdown

La siguiente tabla muestra la sintaxis básica para los elementos más utilizados:

| Elemento | Sintaxis Markdown |
| :--- | :--- |
| **Encabezado** | `# Título Principal (H1)` |
| **Lista con Viñetas** | `- Elemento uno` |
| **Lista Numerada** | `1. Paso uno` |
| **Tabla** | `| Producto | Precio |` |
| **Enlace** | `[Visitar GitHub](https://github.com)` |
| **Imagen** | `![Descripción](https://assets.bytebytego.com/diagrams/0204-git-vs-github.png)` |
| **Código en línea** | `` `ejemplo` `` |
| **Bloque de código** | ``` ```python <br>print("Hola") <br>``` |

---

## 1.3. Ventajas de Utilizar Markdown en Combinación con GitHub

1. **Renderizado Automático**  
   GitHub interpreta y transforma automáticamente los archivos `.md`, mostrando contenido con formato profesional sin necesidad de herramientas externas.

2. **Historial de Cambios Claro (Diffs)**  
   Al ser texto plano, Git puede mostrar con precisión las diferencias entre versiones, facilitando revisiones entre documentos como `DRS_v1`, `DRS_v2` o cualquier archivo técnico.

3. **Colaboración y Mantenimiento Eficiente**  
   Los archivos Markdown generan menos conflictos de fusión, permiten revisiones más rápidas y son ligeros, lo que mejora el trabajo colaborativo dentro del repositorio.

4. **Integración con el Ecosistema GitHub**  
   GitHub permite agregar Markdown en:
   - Issues
   - Pull Requests
   - Wikis
   - Documentación interna  
   Esto unifica toda la documentación bajo un mismo formato estándar.
