## Atributos HTML

Todos los elementos HTML pueden tener atributos
El href atributo de <a>especifica la URL de la página a la que va el enlace</a>
<a>El src atributo de <img>especifica la ruta a la imagen que se mostrará</a>
<a>Los atributos width y height de <img>proporcionan información sobre el tamaño de las imágenes.</a>
<a>El alt atributo de <img>proporciona un texto alternativo para una imagen.</a>
<a>El style atributo se usa para agregar estilos a un elemento, como color, fuente, tamaño y más</a>
<a>El lang atributo de la etiqueta declara el idioma de la página web.</a>
<a>El title atributo define información adicional sobre un elemento.</a>

## HTML Headings

Encabezados HTML
Los encabezados HTML se definen con las etiquetas
<h1>to
</h1><h6>.
</h6><h1>define el encabezado más importante.
</h1><h6>define el encabezado menos importante.
Ejemplo
</h6><h1>Heading 1
</h1><h2>Heading 2
</h2><h3>Heading 3
</h3><h4>Heading 4
</h4><h5>Heading 5
</h5><h6>Heading 6
</h6>

## Párrafos HTML

El

elemento HTML define un párrafo.

Un párrafo siempre comienza en una nueva línea, y los navegadores agregan automáticamente un espacio en blanco (un margen) antes y después de un párrafo.

## Reglas horizontales HTML

La

- - -

etiqueta define un salto temático en una página HTML, y con frecuencia se muestra como una regla horizontal.

El

- - -

elemento se usa para separar contenido (o definir un cambio) en una página HTML:

## Saltos de línea HTML

El
elemento HTML define un salto de línea.

<br>
Úselo
si desea un salto de línea (una nueva línea) sin comenzar un nuevo párrafo:
<br>
## el elemento HTML

<code data-te-codeblock=""></code>

El
<code data-te-codeblock="">elemento HTML define texto preformateado.</code>
El texto dentro de un
elemento se muestra en una fuente de ancho fijo (generalmente Courier), y conserva espacios y saltos de línea:

HTML Styles

El style atributo HTML se usa para agregar estilos a un elemento, como color, fuente, tamaño y más.

El atributo de estilo HTML

La configuración del estilo de un elemento HTML se puede hacer con el style atributo

El style atributo HTML tiene la siguiente sintaxis:

La propiedad es una propiedad CSS. El valor es un valor CSS.

Color de fondo

La background-color propiedad CSS define el color de fondo para un elemento HTML.

Ejemplo

Establezca el color de fondo para una página en azul polvo:

This is a heading

This is a paragraph.

Color de texto

La color propiedad CSS define el color del texto para un elemento HTML:

This is a paragraph.

Fuentes

La font-family propiedad CSS define la fuente que se utilizará para un elemento HTML:

This is a heading

This is a paragraph.

Tamano del texto

La font-size propiedad CSS define el tamaño del texto para un elemento HTML:

This is a heading

This is a paragraph.

Alineación del texto

La text-alignpropiedad CSS define la alineación horizontal del texto para un elemento HTML:

Centered Heading

Centered paragraph.

Use el style atributo para diseñar elementos HTML

Usar background-color para color de fondo

Usar color para colores de texto

Usar font-family para fuentes de texto

Usar font-size para tamaños de texto

Usar text-align para alineación de texto

Formato de texto HTML

HTML contiene varios elementos para definir texto con un significado especial.

Los elementos de formato fueron diseñados para mostrar tipos especiales de texto:

* Texto en negrita
* Texto importante
* Texto en cursiva
* Texto enfatizado
* Texto marcado
* Texto más pequeño
* Texto eliminado
* Texto insertado
* Texto del subíndice
* Texto superíndice

## HTML CSS

¿Qué es el CSS?

Las hojas de estilo en cascada (CSS) se utilizan para formatear el diseño de una página web.

Con CSS, puede controlar el color, la fuente, el tamaño del texto, el espacio entre los elementos, cómo se colocan y distribuyen los elementos, qué imágenes de fondo o colores de fondo se utilizarán, diferentes pantallas para diferentes dispositivos y tamaños de pantalla, y mucho ¡más!

Consejo: la palabra en cascada significa que un estilo aplicado a un elemento primario también se aplicará a todos los elementos secundarios dentro del elemento primario. Por lo tanto, si establece el color del texto del cuerpo en "azul", todos los encabezados, párrafos y otros elementos de texto dentro del cuerpo también obtendrán el mismo color (a menos que especifique algo más).

### Usando CSS

CSS se puede agregar a documentos HTML de 3 maneras:

En línea : mediante el uso del styleatributo dentro de elementos HTML
Interno : mediante el uso de un <style>elemento en la <head>sección
Externo : mediante el uso de un <link> elemento para vincular a un archivo CSS externo

<head>
  <link rel="stylesheet" href="styles.css">
</head>

### Colores CSS, fuentes y tamaños
Aquí, demostraremos algunas propiedades CSS comúnmente utilizadas. Aprenderá más sobre ellos más tarde.

La color propiedad CSS define el color del texto que se utilizará.

La font-family propiedad CSS define la fuente que se utilizará.

La font-size propiedad CSS define el tamaño del texto que se utilizará.


### Borde CSS

La border p ropiedad CSS define un borde alrededor de un elemento HTML.

p {
border: 2px solid powderblue;
}

### Relleno CSS
La padding propiedad CSS define un relleno (espacio) entre el texto y el borde.
p {
  border: 2px solid powderblue;
  padding: 30px;
}

### Margen CSS
La marginpropiedad CSS define un margen (espacio) fuera del borde.

p {
  border: 2px solid powderblue;
  margin: 50px;
}


Use el style atributo HTML para el estilo en línea
Use el <style> elemento HTML para definir CSS interno
Use el <link> elemento HTML para referirse a un archivo CSS externo
Use el <head> elemento HTML para almacenar elementos <style> y <link>
Use la color propiedad CSS para colores de texto
Use la font-family propiedad CSS para fuentes de texto
Use la font-size propiedad CSS para tamaños de texto
Use la border propiedad CSS para bordes
Use la padding propiedad CSS para el espacio dentro del borde
Use la margin propiedad CSS para espacio fuera del borde