# 📄 Generador de Informes PDF para Estudiantes - EEST N°1

Este proyecto consiste en el desarrollo de una mini aplicación web que permite **ingresar datos académicos y personales de un estudiante** y generar automáticamente un informe en formato **PDF**. La herramienta está pensada para ser utilizada por cualquier estudiante de la **EEST N°1 “Eduardo Ader” - Vicente López**, como parte de trabajos prácticos, proyectos finales o presentaciones escolares.

---

## 🚀 Tecnologías Utilizadas

- **HTML**: Estructura de la página web y formulario de ingreso de datos.
- **CSS**: Estilos modernos, validaciones visuales, modales e interfaz amigable.
- **JavaScript**: Lógica para generar el informe PDF, validar formularios, mostrar vista previa y descargar el archivo.
- **[jsPDF](https://github.com/parallax/jsPDF)**: Librería externa utilizada para generar archivos PDF directamente en el navegador.

---

## ⚙️ Funcionalidades

- 🧾 **Formulario completo**: Captura datos como nombre, correo, edad, curso, materia, proyecto, descripción y DNI.
- 📑 **Generación automática de PDF** con estructura visual clara, encabezado, secciones separadas y pie de página institucional.
- 👁️ **Vista previa en vivo**: Visualización del PDF generado directamente en pantalla.
- ✅ **Validación en tiempo real** de todos los campos del formulario con mensajes de error amigables.
- 📤 **Botón de descarga** del PDF generado, nombrado automáticamente con el nombre del estudiante.
- 📚 **Detección automática de Ciclo y Modalidad** según el curso elegido (Básico o Superior - Electrónica o Programación).

---

## 🧪 Instrucciones para Probar el Proyecto

1. **Descargar el Proyecto desde GitHub**:
   - Visita: https://github.com/Elmaciiiii/generador-informes
   - Haz clic en el botón verde `Code` y selecciona `Download ZIP`.
   - Extrae el archivo ZIP en tu computadora.

2. **Abrir el Proyecto en Visual Studio Code**:
   - Abre VS Code y selecciona "Archivo > Abrir Carpeta".
   - Elige la carpeta extraída (`generador-informes-main`).

3. **Ejecutar el Proyecto con Live Server**:
   - Asegúrate de tener instalada la extensión **Live Server** en VS Code.
   - Abre el archivo `index.html`.
   - Haz clic derecho sobre él y selecciona `Open with Live Server`.

4. **Completar el Formulario e Interactuar**:
   - Ingresá los datos requeridos en cada campo del formulario.
   - Presioná el botón **🎯 Generar Informe PDF**.
   - Visualizá el resultado en la vista previa.
   - Hacé clic en **📥 Descargar PDF** para obtener el archivo.

---

## 🗂️ Estructura del Proyecto
```plaintext
.                   // Nombre que le pongas a la carpeta (por eso pongo un .)
├── index.html      // Página principal con el formulario
├── style.css       // Estilos visuales de la app
├── script.js       // Lógica JS para validaciones y generación del PDF
