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

- 🧾 Formulario con campos: nombre, correo, edad, curso, materia, DNI, proyecto y descripción.
- 📑 Generación automática de un archivo PDF personalizado con diseño estructurado.
- 👁️ Vista previa inmediata del informe PDF generado, sin salir de la página.
- ✅ Validación en tiempo real de todos los campos con mensajes claros.
- 📤 Botón para descargar el PDF con nombre automático personalizado.
- 📚 Detección automática de ciclo (Básico/Superior) y modalidad (Programación/Electrónica) según el curso.

---

## 🧪 Instrucciones para Probar el Proyecto del Generador de Informes PDF

Para probar la mini aplicación de generación de informes escolares en PDF, seguí estos pasos:

---

1. **Descargar el proyecto desde GitHub:**
   * Ve a esta página: [https://github.com/Elmaciiiii/actividad_10_Soto-de-la-Colina.git](https://github.com/Elmaciiiii/actividad_10_Soto-de-la-Colina.git)
   * Haz clic en el botón verde que dice **"Code"**.
   * Elige la opción **"Download ZIP"** y guarda el archivo en tu computadora.

---

2. **Extraer el archivo ZIP:**
   * Buscá el archivo ZIP que descargaste y hacé clic derecho para **extraer su contenido**.
   * Se creará una carpeta llamada `actividad_10_Soto-de-la-Colina-main` o similar.

---

3. **Abrir la carpeta del proyecto en Visual Studio Code:**
   * Abrí **Visual Studio Code**.
   * En la barra de menú, andá a **"Archivo" (File)** y seleccioná **"Abrir Carpeta" (Open Folder)**.
   * Navegá hasta la carpeta que se creó al extraer el ZIP (`actividad_10_Soto-de-la-Colina-main`) y seleccionala.
   * Hacé clic en **"Seleccionar carpeta"** o **"Abrir"**.

---

4. **Abrir `index.html` con Live Server:**
   * 📦 **Asegurate de tener instalada la extensión "Live Server" en Visual Studio Code.**
     - Podés buscarla en la sección de extensiones (ícono con cuatro cuadrados) y hacer clic en **"Instalar"**.
   * En el panel de archivos de Visual Studio Code (a la izquierda), **buscá y abrí el archivo `index.html`**.
   * Hacé clic derecho dentro del archivo abierto y seleccioná **"Open with Live Server"**.
   * La página del generador de informes se abrirá automáticamente en tu navegador.
   * Cada vez que hagas un cambio en el código, Live Server actualizará la página.

---

5. **Interactuar con el generador de informes:**
   * Completá todos los campos del formulario con tu información:
     - Nombre completo
     - Correo electrónico
     - Edad
     - Curso
     - Materia
     - DNI
     - Proyecto Final
     - Descripción del Proyecto
   * Hacé clic en el botón **"🎯 Generar Informe PDF"**.
   * Verás una **vista previa del PDF** en la misma página.
   * Aparecerá un **modal de confirmación** indicando que el PDF se generó correctamente.
   * Hacé clic en el botón **"📥 Descargar PDF"** para guardar tu informe en tu computadora.

---

✅ El informe incluirá:
- Encabezado con nombre del colegio y fecha.
- Datos personales y académicos.
- Ciclo y modalidad deducidos automáticamente según el curso.
- Descripción del proyecto con formato profesional.
- Pie de página institucional.

---

---

## 🗂️ Estructura del Proyecto
```plaintext
.                   // Nombre que le pongas a la carpeta (por eso pongo un .)
├── index.html      // Página principal con el formulario
├── style.css       // Estilos visuales de la app
├── script.js       // Lógica JS para validaciones y generación del PDF
