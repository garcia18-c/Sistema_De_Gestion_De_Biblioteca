# 1. Investigación: Uso de Markdown en Proyectos de Software

## 1.1. ¿Qué es Markdown y por qué se utiliza?

* **1.1.1. Definición:** Markdown es un **lenguaje de marcado ligero** (LML) que permite escribir texto con formato (títulos, listas, negrita) utilizando una sintaxis simple basada en texto plano. Fue creado para que los documentos fueran **fáciles de leer y escribir** en su forma sin procesar, pero fáciles de convertir a HTML.

* **1.1.2. Usos en Software:** Se utiliza en proyectos de software por varias razones clave:
    * **Legibilidad:** Permite documentar de forma clara y rápida sin depender de editores complejos.
    * **Portabilidad:** Es compatible con muchas plataformas como GitHub, GitLab y Bitbucket.
    * **Estandarización:** Es el formato universal para documentación técnica, notas de desarrollo y archivos `README`.
    * **Control de Versiones:** Su naturaleza de texto plano lo hace ideal para sistemas como Git.

## 1.2. Ejemplo Práctico de Uso de Markdown

El siguiente código muestra la sintaxis básica para los elementos de formato:

| Elemento | Sintaxis Markdown |
| :--- | :--- |
| **Encabezado** | `# Título Principal (H1)` |
| **Lista Viñeta** | `- Elemento uno` |
| **Lista Numerada** | `1. Primer paso` |
| **Tabla** | `| Producto | Precio |` |
| **Enlace** | `[Texto visible](https://github.com)` |
| **Imagen** | `![Texto alternativo](URL_de_la_imagen)` |

## 1.3. Ventajas de utilizar Markdown en combinación con GitHub

1.  **Renderizado Automático:** GitHub renderiza automáticamente el archivo `README.md` y otros archivos Markdown, convirtiéndolos en la página principal o la documentación estructurada del repositorio.
2.  **Claridad en Diffs (Historial de Cambios):** El texto plano permite a Git mostrar las **diferencias exactas** (*diffs*) entre una versión y otra (por ejemplo, entre `DRS_v1` y `DRS_v2`), facilitando la revisión del historial de cambios de la documentación técnica.
3.  **Colaboración Sencilla:** Los archivos ligeros y de texto plano reducen los conflictos de fusión (*merge conflicts*) cuando varios desarrolladores editan la documentación simultáneamente, mejorando la colaboración.
