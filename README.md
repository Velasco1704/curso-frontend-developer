# Resumen del Curso de Frontend Developer

[GitHub Pages](http://https://velasco1704.github.io/curso-frontend-developer/ "GitHub Pages")

## HTML Semántico:

<p>Al utilizar elementos semánticos apropiados, se mejora la estructura y comprensión del contenido de una página web tanto para los desarrolladores como para los motores de búsqueda.</p>

## Etiquetas De HTML:

### Layout:

<ul>
<li>Header</li>
<li>nav</li>
<li>Section</li>
<li>Article</li>
<li>Aside</li>
<li>Footer</li>
</ul>

### Enlaces:

<ul>
<li>a</li>
</ul>

### Textos:

<ul>
<li>h1, h2, h3, h4, h5, h6</li>
<li>p</li>
<li>span</li>
</ul>

### Imágenes y Videos:

<ul>
<li>img</li>
<li>svg</li>
<li>span</li>
<li>iframe</li>
<li>video</li>
</ul>

### Formularios:

<ul>
<li>form</li>
<li>input</li>
<li>label</li>
<li>button</li>
</ul>

### Listas:

<ul>
<li>ul</li>
<li>ol</li>
<li>li</li>
</ul>

# CSS

## Selectores Básicos:

<ul>
<li>De tipo = div {...}</li>
<li>De Clase = .elemento {...}</li>
<li>De Id = #id-elemento {...}</li>
<li>De atributo = a[href="..."] {...}</li>
<li>Universal = * {...}</li>
</ul>

## Selectores Combinadores:

<ul>
<li>Descendientes = div p{...}</li>
<li>Hijo Directo = div > p {...}</li>
<li>Elemento Adyacente = div + p {...}</li>
<li>General De Hermanos = div ~ p {...}</li>
</ul>

## Pseudoclases:

<ul>
<li>:active</li>
<li>:focus</li>
<li>:hover</li>
<li>:nth-child(n)</li>
<li>:checked</li>
</ul>

## Pseudoelementos:

<ul>
<li>::after</li>
<li>::before</li>
<li>::first-letter</li>
<li>::placeholder</li>
</ul>

## Especificidad:

<ul>
<li>!important (1,0,0,0,0)</li>
<li>#ID (0,1,0,0,0)</li>
<li>Estilos en Linea (0,0,1,0,0)</li>
<li>Clases, Atributos y pseudoclases (0,0,0,1,0)</li>
<li>Elementos y pseudoelementos (0,0,0,0,1)</li>
<li>Selector Universal (0,0,0,0,0)</li>
</ul>

## Tipos de Display:

<ul>
<li><strong>Inline: </strong>Su caja se ajusta al contenido, integrándose al texto sin crear nuevas líneas. Limitaciones incluyen la imposibilidad de añadir márgenes o modificar su tamaño.</li>
<li><strong>Block:</strong> Estos elementos ocupan toda la pantalla, garantizando que cualquier elemento adicional se coloque automáticamente debajo, independientemente de la cantidad de contenido disponible.</li>
<li><strong>Inline-block: </strong>Permite elementos que ocupan solo el ancho necesario, pero también posibilita márgenes y ajuste de tamaño según necesidades.
</li>
<li><strong>Flexbox: </strong>Sistema de diseño que organiza elementos en un contenedor de manera flexible, permitiendo distribución dinámica y alineación en una dirección. Ideal para estructuras más simples.</li>
<li><strong>Grid: </strong>Herramienta de diseño que establece una cuadrícula, permitiendo un control preciso de la disposición de elementos en filas y columnas. Óptimo para estructuras más complejas y alineaciones detalladas.</li>
</ul>

## Modelo de Caja:

<ul>
<li><strong>Contenido: </strong> Es el área dentro de la caja que muestra el texto, las imágenes u otros elementos Html.</li>
<li><strong>Padding: </strong>Es el espacio entre el contenido y el borde de la caja. Se puede agregar relleno para aumentar el espacio entre el contenido y el borde.</li>
<li><strong>Border: </strong> Es una línea que rodea el contenido y el relleno de la caja. Puede tener un grosor, un estilo y un color definidos.</li>
<li><strong>Margin:</strong>Es el espacio que rodea el borde de la caja. Se utiliza para crear espacio entre las cajas adyacentes.</li>
</ul>

## Posicionamiento:

<ul>
<li><strong>Static: </strong>Es la posición predeterminada sin afectar las propiedades top, bottom, left o right ni admitir z-index.</li>
<li><strong>Relative: </strong>Desplaza elementos respecto a su posición original sin afectar a otros.</li>
<li><strong>Absolute: </strong>Se posiciona respecto al elemento padre no estático más cercano o al documento, permitiendo ajustar su posición con top, bottom, left y right.</li>
<li><strong>Fixed: </strong>Se sitúa en relación con la ventana del navegador, permaneciendo fijo al desplazarse la página.</li>
<li><strong>Sticky: </strong>Se comporta como relative hasta salir de la vista, luego se vuelve fixed,ajustándose con top, bottom, left y right.</li>
</ul>

## Z-index y el Contexto de Apilamiento:

<p>Z-index es una propiedad de CSS que se utiliza para controlar el orden de apilamiento de los elementos posicionados en una página web. Esta propiedad determina qué elementos se muestran por encima de otros cuando se superponen en la página.</p>

## Unidades De Medida:

<ul>
<li><strong>Absolutas: </strong>px - pt - pc - in - cm - mm</li>
<li><strong>Relativas: </strong>rem - em - vw - vh - vmin - vmax - ex - ch</li>
</ul>

## Responsive Design:

<p>Las Media Queries son una característica de CSS que permite adaptar el contenido a diferentes tipos de dispositivos y tamaños de pantalla. Son una parte fundamental del diseño web responsivo.</p>

## Arquitecturas de CSS:

### OOCSS:

<p>Significa CSS Orientado a Objetos, es una metodología para escribir CSS de manera más eficiente y sostenible. Se basa en dos principios fundamentales:</p>
<ul>
<li>Separación de estructura y piel: Este principio se refiere a la separación de las propiedades de diseño (como colores, fuentes, etc.) y las propiedades de estructura (como el padding, el margen, etc.). De esta manera, puedes reutilizar los estilos de estructura en diferentes componentes y aplicar diferentes "pieles" o estilos de diseño.</li>
<li>Separación de contenedor e contenido: Este principio sugiere que los estilos no deben estar vinculados a un contenedor específico. En su lugar, los estilos deben ser independientes y reutilizables en diferentes contextos.</li>
</ul>

### BEM:

<p>Significa Block Element Modifier, es una metodología de nomenclatura para escribir CSS de manera más estructurada y modular. Se basa en tres conceptos principales:
</p>
<ul>
<li><strong>Bloque (Block): </strong> Representa un componente independiente y reutilizable de la interfaz de usuario. Un bloque puede ser cualquier elemento de la página, como un encabezado, un menú, un formulario, etc.</li>
<li><strong>Elemento (Element): </strong>Son las partes individuales que componen un bloque. Los elementos están estrechamente relacionados con el bloque al que pertenecen y no tienen significado por sí mismos fuera de ese contexto.</li>
<li><strong>Modificador (Modifier): </strong>Son variaciones o estados diferentes de un bloque o elemento. Los modificadores se utilizan para cambiar la apariencia o el comportamiento de un bloque o elemento sin tener que escribir estilos CSS adicionales.</li>
</ul>

### SMACSS:

<p>Significa Scalable and Modular Architecture for CSS, es una metodología para organizar y estructurar el código CSS de manera más eficiente y mantenible. Se basa en cinco categorías principales:</p>
<ul>
<li><strong>Base: </strong>Esta categoría incluye los estilos base y globales que se aplican a todo el sitio web, como los estilos de reset, tipografía básica y estilos de enlaces.</li>
<li><strong>Layout: </strong>Aquí se definen los estilos para la estructura y el diseño de la página, como los estilos de la barra de navegación, el encabezado, el pie de página, etc.</li>
<li><strong>Módulos: </strong>Los módulos son componentes independientes y reutilizables que se pueden combinar para construir páginas más complejas. Cada módulo tiene su propio archivo CSS y contiene estilos específicos para ese componente.</li>
<li><strong>Estado:</strong>Esta categoría se utiliza para definir los estilos que se aplican en diferentes estados de los elementos, como los estilos de hover, focus, active, etc.</li>
<li><strong>Tema:</strong>Aquí se definen los estilos que se aplican para diferentes temas o variaciones del sitio web, como estilos de color, estilos de fuente, etc.
</li>
</ul>

### Atomic Design:

<p>Es un sistema de trabajo que se basa en la creación de elementos modulares sencillos para crear estructuras de información mucho más complejas. Cada vez tenemos que diseñar para más tamaños de pantallas y para distintos dispositivos (móviles, tabletas, TV, etc.) y necesitamos procesos que eviten errores y faciliten el desarrollo. Se basa en 5 niveles:
</p>
<ul>
<li><strong>Nivel 1: </strong>Átomos Un átomo es la unidad de partículas más pequeña que puede existir. Aplicado al diseño, hablamos de átomos cuando hablamos de elementos UI que por sí solos tienen alguna funcionalidad: botones, cards, avatares, inputs de formulario… pero también las tipografías, paleta de colores, espaciados, párrafos.</li>
<li><strong>Nivel 2: </strong>Moléculas Una molécula es una unión de dos o más átomos. Del mismo modo, una molécula en Atomic Design es la unión de diferentes átomos para formar un elemento UI más complejo. Por ejemplo, un campo de formulario con un botón de enviar y un label. O un rectángulo con un avatar, nombre y ubicación del usuario.</li>
<li><strong>Nivel 3: </strong>Organismos Unión de moléculas. Por ejemplo, cuando juntamos los rectángulos con el avatar y los nombres, cuando unimos los iconos y texto para crear una navegación de una aplicación, etc.
</li>
<li><strong>Nivel 4: </strong>Plantillas Unión de distintos organismos que forman una página o una aplicación. Se trata de un entregable de alta fidelidad, pero que no termina de ser el diseño final. Para que nos entendamos, se trata del “esqueleto” de la aplicación o página web.</li>
<li><strong>Nivel 5: </strong>Páginas El diseño final que ya contiene las imágenes y otros detalles que hacen que ese archivo ya esté listo para el desarrollo o, en su defecto, test con usuarios o el equipo.
</li>
</ul>
