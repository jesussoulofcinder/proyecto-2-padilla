# Colegio Alegría - Educación Primaria

Este proyecto es una página web moderna y atractiva (Landing Page) para una escuela de educación primaria llamada **Colegio Alegría**. Está diseñada para brindar información sobre la institución, sus grados escolares y facilitar el contacto con los padres de familia, todo ello con un diseño amigable, colorido y con animaciones sutiles.

## Características Principales

*   **Diseño Responsivo:** La página se adapta perfectamente a diferentes tamaños de pantalla, incluyendo dispositivos móviles, gracias a un diseño adaptable y un menú de navegación tipo "hamburguesa".
*   **Animaciones Suaves:** Transiciones y efectos visuales atractivos al hacer scroll (como elementos que aparecen gradualmente `fade-in` o se deslizan `slide-in-right`).
*   **Secciones Claras e Informativas:**
    *   **Inicio:** Una cabecera (hero section) atractiva con un claro llamado a la acción.
    *   **Nosotros:** Información sobre la misión, valores y filosofía de desarrollo creativo de la escuela.
    *   **Grados:** Descripción de los diferentes niveles escolares ofrecidos y qué se aprende en cada uno.
    *   **Contacto:** Un formulario de inscripción/contacto intuitivo, e información de ubicación.
*   **Interacciones Dinámicas:** 
    *   La barra de navegación añade una sombra al hacer scroll.
    *   El formulario de contacto simula un envío exitoso interactivo.

## Tecnologías Utilizadas

Este proyecto fue desarrollado construyendo sobre las tecnologías base de la web ("Vanilla"), sin el uso de frameworks pesados:

*   **HTML5:** Estructura semántica de la página.
*   **CSS3:** Diseño, paletas de colores modernos, variables CSS (Costum Properties), tipografías (Nunito y Outfit de Google Fonts) y animaciones clave con `keyframes` y `transitions`.
*   **JavaScript (Vanilla JS):** Interactividad principal: 
    *   *Menú móvil.*
    *   *Efectos al hacer scroll* utilizando la API `IntersectionObserver` por rendimiento.
    *   *Manejo simulado de envío* del formulario de inscripción.

## Estructura de Archivos

*   `index.html`: El archivo principal que contiene toda la estructura de contenido de la página.
*   `styles.css`: La hoja de estilos que define todo el aspecto visual y layout del proyecto.
*   `script.js`: El archivo con la lógica interactiva del sitio.

## Cómo Ejecutar el Proyecto

Como es un proyecto web estático fundamental, no requiere la instalación de dependencias ni la configuración de un servidor complejo.

1.  Abre la carpeta del proyecto en tu computadora (donde están guardados estos archivos).
2.  Haz doble clic en el archivo `index.html` para abrirlo directamente en tu navegador web predeterminado (Google Chrome, Firefox, Edge, Safari, etc.).
3.  **(Opcional para desarrollo):** Si utilizas un editor de código como Visual Studio Code, te recomendamos la extensión **Live Server** para hacer clic derecho sobre `index.html` y seleccionar "Open with Live Server", permitiéndote visualizar el sitio y actualizarse automáticamente si realizas cambios.
