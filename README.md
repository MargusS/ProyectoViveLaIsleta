# ProyectoViveLaIsleta

En esta versión del proyecto, añadimos la página de presentación a la experiencia de realidad virtual de una de las rutas de nuestros sabios guías además de implementar canvas y objetos JSON en AFRAME.

Página de Presentación:

index.html 
- Barra de navegación que incluye la función scrollspy para las secciones de "Experiencia VR" y "Galería".
- Navegación offCanvas para dispositivos móviles
- Jumbotron con video y overlay
- Secciones de información y presentación del proyecto junto con imágenes parallax
- Galería de imagenes con GRID.
- Footer con enlace al Facebook del proyecto

aboutus.html 
- Barra de navegación que incluye la función scrollspy para las secciones de "Contacto"
- Navegación offCanvas para dispositivos móviles
- Información del proyecto y la organización
- Carousel de imágenes
- Colaboradores del proyecto
- Formulario de contacto

Proyecto AFRAME

isleta_vr.html
castillo_vr.html
victoria_vr.html
escobio_vr.html
En estas páginas tenemos los distintos escenarios de nuestra ruta de Realidad Virtual.
- Imagen 360
- Elementos clickeacles
- Elementos de textos con canvas
- Botones con distintas funciones
- Botón fijo para activar y desactivar el sonido ambiente

Ficheros JS

change_site.js
- Registra un elemento AFRAME que tiene un atributo URL que será la direccion del cielo que se debe mostrar.

draw_canvas.js
- Registra un elemento AFRAME con un atributo pos que almacenará la posición del objeto a la que hace referencia el escenario.
- Tiene un objeto JSON con la información de cada escenario de la ruta.
- Crea un rectágulo canvas y dentro escribe la información que le llega del objeto dependiendo del valor del atributo pos.

toggle_sound.js
- Se encarga de controlar el botón del sonido ambiente cuando se hace click sobre el.

view_info.js
- Registra un elemento AFRAME sin atributos que controla el estado del atributo "visible" de los elementos de información.

visible-menu-js
- Registra un elemento AFRAME  sin atributos que sirve para controlar el menu de isleta_vr.html. 
