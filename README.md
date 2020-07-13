`2020-07-12 14:17:33 Sunday`

# Curso de Desarrollo Web Online

Curso Básico de 6 horas de contenido.

> En este curso, Leonidas Esteban te da una introducción al mundo del desarrollo web que te será de mucha utilidad, tanto si quieres convertirte en un programador Backend, como si tu objetivo es ser un programador Frontend. Aprenderás a codificar los documentos necesarios para que tu sitio web se vea y se pueda acceder a través de internet.

* [Curso de Desarrollo Web Online]( https://platzi.com/clases/html5-css3/ "Curso de Desarrollo Web Online")


## Atributos HTML
Los atributos son valores agregados a las etiquetas (tags) html que extienden su habilidad o funcionalidad con información específica.

A continuación, un ejemplo de los atributos más comunes y usados en algunas etiquetas:

Para **img:**

**src:** específica la ruta de la imagen que será mostrada a través de esta etiqueta. La ruta puede ser absoluta (cunado especifica una dirección exacta, incluyendo el prefijo http(s) ) o relativa (cuando la referencia a la ubicación de la imagen parte de la ubicación del archivo actual).

**alt:** indica un texto alternativo que será mostrado en lugar de la imagen cuando ésta no pueda ser mostrada.

**width:** ancho de la imagen en pixeles.

**height:** alto de la imagen en pixeles.

Para **link**, en la cabecera head del documento:

**rel:** indica la relación del recurso con el contenido.

**type:** indica el tipo de recurso / formato.

**href:** indica la ubicación (url) del recurso enlazado.

Para **meta**, también en la cabecera head del documento:

**charset:** indica la tabla de caracteres (utf-8 para caracteres latinos) usada en el documento.

Para **a:**
**href:** la ubicación o ruta a la que enlaza esta etiqueta de ancla. En el caso de querer enlazar a elementos que se encuentran dentro del mismo documento, este atributo debe indicar el valor del atributo ““id”” de ese elemento destino del enlace.

## Formularios HTML

Los Formularios en html son unidades de información que nos permiten recolectar información para enviarlos al propietario del website o a un servicio externo. Esta formado por dos partes o contextos: una parte donde se hace el ingreso y modelación de esos datos (en el frontend), y otra parte que se encarga de enviar, procesar y almacenar esos datos (en el backend).

Los formularios se crean con la etiqueta **form**. El atributo principal de un formulario es **action**, ya que contiene la ruta a la que serán enviados los datos recolectados.

Hay diversos elementos html que permiten la captura o recolección de datos, aunque generalmente se usan los elementos creados con la etiqueta **input**. Los inputs también sirven para crear botones, aunque existe una etiqueta especial para ésto llamada **button**… El atributo principal de los inputs es **type**, que indica el tipo de comportamiento o dato que se espera recibir.

Los elementos creados con la etiqueta **label** muestran un texto que se puede asociar con un input para darle mayor significado al campo, principalmente cuando no se usa el atributo **placeholder**.

## Formas de agregar estilos a HTML

Hay tres opciones para incluir estilos que definan la apariencia de tu html:

Estilos **en línea**: se definen directamente en el elemento html que quieres estilizar, se agregan con el atributo **style**.

Estilos con el **tag Style**: regularmente este tag se incluye dentro de la etiqueta head del html.

Estilos enlazados desde un archivo **css externo**: utilizando la etiqueta **link** que nos permite enlazar recursos externos.

A CSS, se le llama hojas de estilos en cascada porque los estilos que se definen para una página, se van aplicando de arriba hacia abajo, y de lo más general a lo más particular, teniendo prioridad lo más particular. Esto es, los estilos que prevalecen son los que han sido definidos en línea, luego los que fueron definidos mediante la etiqueta style en la cabeza o cuerpo del html, y por último los estilos definidos en archivos externos enlazados con la etiqueta link. Esta prioridad se puede alterar al usar el modificador **!important** en la definición de algún estilo en particular, aunque esto no es recomendado.

## Bordes

Todos los elementos html admiten la propiedad de css border, que define la apariencia que tendrá el contorno del componente.
El borde puede ser de muchos estilos, y al igual que las propiedades margin y padding que aprenderás más adelante, a los bordes se les puede colocar estilos tanto de forma general con la propiedad border, como de acuerdo al lado del elemento que se indique: **border-top, border-right, border-bottom y border-left**.

Con la propiedad **boder-radius** se define el redondeado de las esquinas de los bordes.

## Márgenes

Los márgenes en CSS son el espacio que separa a los elementos html entre sí. Hay elementos de html que traen márgenes predefinidos (por defecto) en los estilos propios del navegador como el caso de: body, h1, h2, h3, h4, h5, h6, ol, ul, li, p, y muchos otros.

Cuando hay dos márgenes de elementos diferentes que colindan entre sí, se presenta una situación llamada **“margin collapsing”** en la que el mayor margen de los dos se superpone al otro.

Se puede asignar una medida de margin para los cuatro lados del elemento, o márgenes individuales para cada uno de los lados con: **margin-top, margin-right, margin-bottom y margin-left.**

Se puede centrar un elemento html colocándole el valor de **margin: 0 auto**, cuando dicho elemento tiene **display block**.
