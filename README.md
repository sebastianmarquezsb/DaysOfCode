# HTML
## Atributos HTML

Todos los elementos HTML pueden tener atributos
El href atributo de <a> especifica la URL de la página a la que va el enlace
El src atributo de <img> especifica la ruta a la imagen que se mostrará
Los atributos width y height de <img> proporcionan información sobre el tamaño de las imágenes.
El alt atributo de <img> proporciona un texto alternativo para una imagen.
El style atributo se usa para agregar estilos a un elemento, como color, fuente, tamaño y más
El lang atributo de la etiqueta declara el idioma de la página web.
El title atributo define información adicional sobre un elemento.

## HTML Headings

Encabezados HTML
Los encabezados HTML se definen con las etiquetas
````html
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
````
## Párrafos HTML

El elemento HTML define un párrafo.
Un párrafo siempre comienza en una nueva línea, y los navegadores agregan automáticamente un espacio en blanco (un margen) antes y después de un párrafo.

## Reglas horizontales HTML

La * * *  define un salto temático en una página HTML, y con frecuencia se muestra como una regla horizontal.
El * * * elemento se usa para separar contenido (o definir un cambio) en una página HTML:

## Saltos de línea HTML

El elemento HTML define un salto de línea.
Úselo si desea un salto de línea (una nueva línea) sin comenzar un nuevo párrafo:
````HTML
<br>
````

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

### Formato de texto HTML
HTML contiene varios elementos para definir texto con un significado especial.
Los elementos de formato fueron diseñados para mostrar tipos especiales de texto:
-   Texto en negrita
-   Texto importante
-   Texto en cursiva
-   Texto enfatizado
-   Texto marcado
-   Texto más pequeño
-   Texto eliminado
-   Texto insertado
-   Texto del subíndice
-   Texto superíndice

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

## secciónes

### Header

Crear seccion de Header como logo,

### nav

Barra de navegacion, Home, Contacto, etc

### article

### section

### aside

no corresponde al contenido pero queremos mostrará como publicidad

### footer

 pie de pagina

## Agrupaciones de contenido

### Listas anidadas
ul :Unordered List
ol :Orderer List
li :List Item
````html
<ul>
  <li>item de lista 1</li>
  <li>item de lista 2
    <ol>
      <li>subitem de lista 1</li>
      <li>subitem de lista 2</li>
    </ol>
  </li>
  <li>item de lista 3</li>
</ul>
````
### Listas de definicion

Sirven para indicar un termino y una definicion ej. glosario
dl : Definition List
dt : Definition Term
dd : Definition description
````html
<dl class="">
  <dt>Peru</dt>
  <dd>Lima</dd>
  <dt>Chile</dt>
  <dd>Santiago</dd>
  <dt>Venezuela</dt>
  <dd>Caracas</dd>
</dl>
````

## Figure y Figcaption

Figure sirve para colocar contenido relacionado pero que rompa el flujo del contenido
Ejemplo un tutorial o contenido, noticia,etc en el que se inserta imagen, video, en el medio del documento que esta relacionado con el contenido.

Figcaption es la leyenda del contenido, description, title, opcional
````html
<figure>
  <pre>
    <code>function hola() {
      return "Hola Mundo"
    }
  </code>
  </pre>
  <figcaption>
    Declaracion de una funcion JavaScript
  </figcaption>
</figure>
````
## Otros elementos

### Main
el elemento mas importante, Contenido principal de la pagina
````html
<main>
  <p>este en un parrafo</p>
  <hr> <!-- horizontal rule -->
  <pre>  <!-- preformateado -->
        este Texto
   se representa
     igual en el Navegador
  </pre>
  <blockquote cite="http://">
    <!-- citas frases famosas, Destacar elemento del contenido -->
  </blockquote>
</main>
````
### Divisiones (Layout)

Div y span son contendores de contenidos para luego ser usados css ,js,etc

## Elementos de Linea y Bloque

los elementos de linea deben estar dentro de un elemento de Bloque,
la mayoria son elementos de bloque
````html
 ul,li,p,blockquote,article,figure
 ````
 ````html
<p>Este es un elemento de bloque</p>
<span>Este es un elemento de linea</span>
````
### elementos de texto comunes

````html
<small></small>
<strong></strong> <!--mas importanto  -->
<em></em> <!--enfasis cursiva-->
<cite></cite> <!--citar -->
<dfn></dfn> <!--definicion ej Siglas-->
<code></code> <!--fragmentos de codigos-->
<data value=""></data>
<br> <!--Quiebre de linea -->
<q cite=""></q><!-- -->
<abbr title=""></abbr> <!--Abbreviation -->
<del></del> <!-- Deleted Text-->
<wbr> <!-- Word Break Opportunity-->
<span></span>  <!--Contendor de elementos de linea -->
<i></i> <!-- italic -->
<b></b> <!--bold o negrita-->
<u></u> <!-- undeline -->
<sup></sup> <!-- superíndice -->
<sub></sub> <!-- subindice -->
<time></time> <!-- Tiempo -->
<mark></mark> <!-- resaltar el texto, remarcar -->
<a href="#"></a> <!-- Hipertexto Enlaces -->
````

## Enlaces

````html
<p>
  <!-- Ruta Absoluta -->
  <a href="https://ed.team">Educacion con honestidad</a>
  <!-- Ruta Relativa, Misma carpeta -->
  <a href="usuarios.html">Usuarios</a>
  <a href="./usuarios.html">Usuarios</a>
  <!-- Ruta Relativa, Carpeta superior -->
  <a href=../usuarios.html>Usuarios</a>
  <!-- Ruta Relativa, 2 carpetas arriba y subdirectorio -->
  <a href="../usuarios/usuarios.html"></a>
  <!-- Ruta Relativa a la Raiz / -->
  <a href="/usuarios.html">Usuarios</a>
</p>
````
