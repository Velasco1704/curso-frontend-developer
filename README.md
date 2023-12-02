RESUMEN DEL CURSO DE FRONTEND DEVELOPER

HTML

HTML Semántico:

Al utilizar elementos semánticos apropiados, se mejora la estructura y comprensión del contenido de una página web tanto para los desarrolladores como para los motores de búsqueda.

===========================

Etiquetas De HTML:

Layout:

<header></header>
<nav></nav>
<section></section>
<article></article>
<aside></aside>
<footer></footer>

Enlaces:
<a></a>

Textos:

<h1></h1>, <h2></h2>, <h3></h3>, <h4></h4>, <h5></h5>, <h6></h6>
<p></p>
<span></span>

Imágenes y Videos:

<img/>
<svg></svg>

<iframe></iframe>
<video></video>

Formularios:

<form></form>
<input/>
<label></label>
<button></button>

Listas:

<ul></ul>
<ol></ol>
<li></li>

===========================
CSS

Selectores Básicos:

De tipo = div {...}
De Clase = .elemento {...}
De Id = #id-elemento {...}
De atributo = a[href="..."] {...}
Universal = \* {...}

Selectores Combinadores:

Descendientes = div p
Hijo Directo = div > p
Elemento Adyacente = div + p
General De Hermanos = div ~ p

===========================

Pseudoclases:

:active
:focus
:hover
:nth-child(n)
:checked

Pseudoelementos:
::after
::before
::first-letter
::placeholder

===========================

Especificidad:

!important (1,0,0,0,0)
#ID (0,1,0,0,0)
Estilos en Linea (0,0,1,0,0)
Clases, Atributos y pseudoclases (0,0,0,1,0)
Elementos y pseudoelementos (0,0,0,0,1)
Selector Universal (0,0,0,0,0)

===========================

Tipos de Display:

inline: Su caja se ajusta al contenido, integrándose al texto sin crear nuevas líneas. Limitaciones incluyen la imposibilidad de añadir márgenes o modificar su tamaño.

block: Estos elementos ocupan toda la pantalla, garantizando que cualquier elemento adicional se coloque automáticamente debajo, independientemente de la cantidad de contenido disponible.

inline-block: Permite elementos que ocupan solo el ancho necesario, pero también posibilita márgenes y ajuste de tamaño según necesidades.

Flexbox: Sistema de diseño que organiza elementos en un contenedor de manera flexible, permitiendo distribución dinámica y alineación en una dirección. Ideal para estructuras más simples.

Grid: Herramienta de diseño que establece una cuadrícula, permitiendo un control preciso de la disposición de elementos en filas y columnas. Óptimo para estructuras más complejas y alineaciones detalladas.

===========================

Modelo de Caja:

Contenido: Es el área dentro de la caja que muestra el texto, las imágenes u otros elementos Html.

Padding: Es el espacio entre el contenido y el borde de la caja. Se puede agregar relleno para aumentar el espacio entre el contenido y el borde.

Border: Es una línea que rodea el contenido y el relleno de la caja. Puede tener un grosor, un estilo y un color definidos.

Margin: Es el espacio que rodea el borde de la caja. Se utiliza para crear espacio entre las cajas adyacentes.

===========================

Posicionamiento:

Static: es la posición predeterminada sin afectar las propiedades top, bottom, left o right ni admitir z-index.

Relative: desplaza elementos respecto a su posición original sin afectar a otros.

Absolute: se posiciona respecto al elemento padre no estático más cercano o al documento, permitiendo ajustar su posición con top, bottom, left y right.

Fixed: se sitúa en relación con la ventana del navegador, permaneciendo fijo al desplazarse la página.

Sticky: se comporta como relative hasta salir de la vista, luego se vuelve fixed,ajustándose con top, bottom, left y right.

===========================

Z-index y el Contexto de Apilamiento:

Z-index es una propiedad de CSS que se utiliza para controlar el orden de apilamiento de los elementos posicionados en una página web. Esta propiedad determina qué elementos se muestran por encima de otros cuando se superponen en la página.

===========================

Unidades De Medida:

Absolutas:
px - pt - pc - in - cm - mm

Relativas:
rem - em - vw - vh - vmin - vmax - ex - ch

===========================

Responsive Design:

Las Media Queries son una característica de CSS que permite adaptar el contenido a diferentes tipos de dispositivos y tamaños de pantalla. Son una parte fundamental del diseño web responsivo.

===========================

Arquitecturas de CSS:

-OOCSS:

Significa CSS Orientado a Objetos, es una metodología para escribir CSS de manera más eficiente y sostenible. Se basa en dos principios fundamentales:

Separación de estructura y piel: Este principio se refiere a la separación de las propiedades de diseño (como colores, fuentes, etc.) y las propiedades de estructura (como el padding, el margen, etc.). De esta manera, puedes reutilizar los estilos de estructura en diferentes componentes y aplicar diferentes "pieles" o estilos de diseño.

Separación de contenedor e contenido: Este principio sugiere que los estilos no deben estar vinculados a un contenedor específico. En su lugar, los estilos deben ser independientes y reutilizables en diferentes contextos.

-BEM:

Significa Block Element Modifier, es una metodología de nomenclatura para escribir CSS de manera más estructurada y modular. Se basa en tres conceptos principales:

Bloque (Block): Representa un componente independiente y reutilizable de la interfaz de usuario. Un bloque puede ser cualquier elemento de la página, como un encabezado, un menú, un formulario, etc.

Elemento (Element): Son las partes individuales que componen un bloque. Los elementos están estrechamente relacionados con el bloque al que pertenecen y no tienen significado por sí mismos fuera de ese contexto.

Modificador (Modifier): Son variaciones o estados diferentes de un bloque o elemento. Los modificadores se utilizan para cambiar la apariencia o el comportamiento de un bloque o elemento sin tener que escribir estilos CSS adicionales.

-SMACSS:

Significa Scalable and Modular Architecture for CSS, es una metodología para organizar y estructurar el código CSS de manera más eficiente y mantenible. Se basa en cinco categorías principales:

Base: Esta categoría incluye los estilos base y globales que se aplican a todo el sitio web, como los estilos de reset, tipografía básica y estilos de enlaces.

Layout: Aquí se definen los estilos para la estructura y el diseño de la página, como los estilos de la barra de navegación, el encabezado, el pie de página, etc.

Módulos: Los módulos son componentes independientes y reutilizables que se pueden combinar para construir páginas más complejas. Cada módulo tiene su propio archivo CSS y contiene estilos específicos para ese componente.

Estado: Esta categoría se utiliza para definir los estilos que se aplican en diferentes estados de los elementos, como los estilos de hover, focus, active, etc.

Tema: Aquí se definen los estilos que se aplican para diferentes temas o variaciones del sitio web, como estilos de color, estilos de fuente, etc.

-Atomic Design

Es un sistema de trabajo que se basa en la creación de elementos modulares sencillos para crear estructuras de información mucho más complejas. Cada vez tenemos que diseñar para más tamaños de pantallas y para distintos dispositivos (móviles, tabletas, TV, etc.) y necesitamos procesos que eviten errores y faciliten el desarrollo. Se basa en 5 nivel

Nivel 1: Átomos Un átomo es la unidad de partículas más pequeña que puede existir. Aplicado al diseño, hablamos de átomos cuando hablamos de elementos UI que por sí solos tienen alguna funcionalidad: botones, cards, avatares, inputs de formulario… pero también las tipografías, paleta de colores, espaciados, párrafos…

Nivel 2: Moléculas Una molécula es una unión de dos o más átomos. Del mismo modo, una molécula en Atomic Design es la unión de diferentes átomos para formar un elemento UI más complejo. Por ejemplo, un campo de formulario con un botón de enviar y un label. O un rectángulo con un avatar, nombre y ubicación del usuario.

Nivel 3: Organismos Unión de moléculas. Por ejemplo, cuando juntamos los rectángulos con el avatar y los nombres, cuando unimos los iconos y texto para crear una navegación de una aplicación, etc.

Nivel 4: Plantillas Unión de distintos organismos que forman una página o una aplicación. Se trata de un entregable de alta fidelidad, pero que no termina de ser el diseño final. Para que nos entendamos, se trata del “esqueleto” de la aplicación o página web.

Nivel 5: Páginas El diseño final que ya contiene las imágenes y otros detalles que hacen que ese archivo ya esté listo para el desarrollo o, en su defecto, test con usuarios o el equipo.
