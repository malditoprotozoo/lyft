# Lyft

* **Track:** _Common Core_
* **Curso:** _Creando tu primer sitio web interactivo_
* **Unidad:** _Maquetado web con HTML & CSS_

***

En este reto se nos pidió replicar la maquetación del sitio de la empresa **Lyft**. Este debía ser el resultado final:

![Lyft Website](docs/fullpage.png)

## Flujo de trabajo

Para cumplir con el objetivo partí por dividir el sitio en siete secciones, usando tanto etiquetas ``div`` como	los nuevos elementos semánticos de HTML5:

* ``#container``: Contenedor que abarca todo el sitio.
* ``nav``: Barra de navegación.
* ``header``: Gif animado con el logo de la empresa y un formulario de subscripción.
* ``section #gradient``: La id fue elegida porque representa el color de fondo de este espacio. Acá se describe el servicio que entrega la empresa.
* ``#videos``: Como el nombre lo indica, creé un contenedor que abarca todos los vídeos que se presentan en el sitio.
* ``footer``: Parte inferior de la estructura web.

###Desafíos

* **Degradado:** El sitio original de Lyft tiene una transición sútil de colores que no conseguía lograr sólo con el color degradado. Para suavizar la transición, le añadí una sombra al ``header`` con el mismo color del inicio del degradado (``#6b1e85``) y le fui agrandando el tamaño hasta que consideré que quedaba lo suficientemente parecido.

* **Vídeos:** Para insertar los vídeos usé la etiqueta recomendada ``iframe``. Esta etiqueta de tipo *inline* se usa para insertar un documento dentro del sitio. En este caso, usé los enlaces especiales de YouTube que permiten que el vídeo se reproduzca en el sitio que uno está creando y no sólo un enlace hacía Youtube. Para que en esta sección los vídeos quedaran en un lado y el texto en otro usé la propiedad ``float``.

### Resolución de Pantalla

Template realizado en una laptop con resolución de pantalla **1366 x 768 (16:9).**
