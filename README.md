# HTML
## Atributos HTML

Todos los elementos `HTML` pueden tener atributos  
El `href` atributo de `<a>` especifica la URL de la página a la que va el enlace.  
El `src` atributo de `<img>` especifica la ruta a la imagen que se mostrará.  
Los atributos `width` y `height` de `<img>` proporcionan información sobre el tamaño de las imágenes.  
El `alt` atributo de `<img>` proporciona un texto alternativo para una imagen.  
El `style` atributo se usa para agregar estilos a un elemento, como color, fuente, tamaño y más.  
El `lang` atributo de la etiqueta declara el idioma de la página web.  
El `title` atributo define información adicional sobre un elemento.  

### HTML Headings
Los encabezados `HTML` se definen con las etiquetas.  
`<h1>` hasta `<h6>`  
`<h1>` define el encabezado más importante.  
`<h6>` define el encabezado menos importante.  

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```
### Párrafos HTML

El elemento `<p>` define un párrafo.  
Un párrafo siempre comienza en una nueva línea, y los navegadores agregan automáticamente un espacio en blanco (un margen) antes y después de un párrafo.
### Horizontal Rules - Reglas horizontales

La `<hr>`  define un salto temático en una página `HTML`, y con frecuencia se muestra como una regla horizontal.  
El `<hr>` elemento se usa para separar contenido (o definir un cambio) en una página HTML

### Saltos de línea

El elemento `<br>` define un salto de línea.
Úselo si desea un salto de línea (una nueva línea) sin comenzar un nuevo párrafo

### Line Break - Linea de Quiebre
El elemento `<br>` define un salto de línea.  
Úselo `<br>` si desea un salto de línea (una nueva línea) sin comenzar un nuevo párrafo

### Preformateado
El elemento `pre` define texto preformateado.  
El texto dentro de un elemento se muestra en una fuente de ancho fijo (generalmente Courier), y conserva espacios y saltos de línea:
````html
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>
````

### blockquote
El elemento `<blockquote>` define una sección que se cita de otra fuente.
Los navegadores suelen indentar `<blockquote>`elementos.
```html
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For nearly 60 years, WWF has been protecting the future of nature. The world's leading conservation organization, WWF works in 100 countries and is supported by more than one million members in the United States and close to five million globally.
</blockquote>
```
### Short Quotations
La etiqueta `<q>` define una cita corta.
Los navegadores normalmente insertan comillas alrededor de la cita
```html
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>

```
### Abbreviations
La etiqueta `<abbr>` define una abreviatura o un acrónimo, como `HTML`, `CSS`,`Mr`,`ASAP`,`ATM`.  
Las abreviaturas de marcado pueden proporcionar información útil a los navegadores, sistemas de traducción y motores de búsqueda.  
Consejo: Use el atributo de título global para mostrar la descripción de la abreviatura / acrónimo cuando pase el mouse sobre el elemento.
```html
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>

<p>Marking up abbreviations can give useful information to browsers, translation systems and search-engines.</p>

```
### Address - Contact Information
La etiqueta `<address>` define la información de contacto del autor/propietario de un documento o artículo.  
La información de contacto puede ser una dirección de correo electrónico, URL, dirección física, número de teléfono, identificador de redes sociales, etc.

El texto en el elemento `<address>` generalmente se muestra en cursiva, y los navegadores siempre agregarán un salto de línea antes y después del `<address>` elemento.
```html
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>

```

### Cite - Citar
La etiqueta `<cite>` define el título de una obra creativa (por ejemplo, un libro, un poema, una canción, una película, una pintura, una escultura, etc.).  
Nota: El nombre de una persona no es el título de una obra.  
El texto en el <cite>elemento generalmente se presenta en cursiva .
```html
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>

```
### bdo
`BDO` significa anulación bidireccional.  
La etiqueta `<bdo>` se usa para anular la dirección del texto actual:
```html
<bdo dir="rtl">Este Texto esta escrito de derecha a izquierda</bdo>

```

### code
El elemento `code`
```html
<code data-te-codeblock=""></code>
```

## HTML Styles

El `style` atributo `HTML` se usa para agregar estilos a un elemento, como color, fuente, tamaño y más.  
El style atributo HTML tiene la siguiente sintaxis:

La propiedad es una propiedad CSS. El valor es un valor CSS.

* Color de fondo  
La `background-color` propiedad CSS define el color de fondo para un elemento HTML:
```html
<body style="background-color:powderblue;"></body>  
```

* Color de texto  
La `color` propiedad CSS define el color del texto para un elemento HTML:
````html
<p style="color:red;">This is a paragraph.</p>
````

* Color de Borde  
La `border` propiedad CSS define el borde para un elemento HTML:
```html
<h1 style="border:2px solid Violet;">Hello World</h1>
```   

* Fuentes  
La font-family propiedad CSS define la fuente que se utilizará para un elemento HTML:
````html
<p style="font-family:courier;">This is a paragraph.</p>
````

* Tamano del texto  
La font-size propiedad CSS define el tamaño del texto para un elemento HTML:
````html
<p style="font-size:160%;">This is a paragraph.</p>
````

* Alineación del texto  
La text-alignpropiedad CSS define la alineación horizontal del texto para un elemento HTML:
````html
<p style="text-align:center;">Centered paragraph.</p>
````

Use el `style` atributo para diseñar elementos `HTML`  
Usar `background-color` para color de fondo  
Usar `color` para colores de texto  
Usar `font-family` para fuentes de texto  
Usar `font-size` para tamaños de texto  
Usar `text-align` para alineación de texto  

### Formato de texto HTML
`HTML` contiene varios elementos para definir texto con un significado especial.  
Los elementos de formato fueron diseñados para mostrar tipos especiales de texto:
+ `<b>` - Bold text
+ `<strong>` - Important text
+ `<i>` - Italic text
+ `<em>` - Emphasized text
+ `<mark>` - Marked text
+ `<small>` - Smaller text
+ `<del>` - Deleted text
+ `<ins>` - Inserted text
+ `<sub>` - Subscript text
+ `<sup>` - Superscript text

## HTML CSS

¿Qué es el CSS?

Las hojas de estilo en cascada (CSS) se utilizan para formatear el diseño de una página web.  
Con CSS, puede controlar el color, la fuente, el tamaño del texto, el espacio entre los elementos, cómo se colocan y distribuyen los elementos, qué imágenes de fondo o colores de fondo se utilizarán, diferentes pantallas para diferentes dispositivos y tamaños de pantalla, y mucho ¡más!

Consejo: la palabra en cascada significa que un estilo aplicado a un elemento primario también se aplicará a todos los elementos secundarios dentro del elemento primario. Por lo tanto, si establece el color del texto del cuerpo en "azul", todos los encabezados, párrafos y otros elementos de texto dentro del cuerpo también obtendrán el mismo color (a menos que especifique algo más).

### Usando CSS

`CSS` se puede agregar a documentos `HTML` de 3 maneras:
+ En Linea - mediante el uso del `style` atributo dentro de elementos HTML  
+ Interno - mediante el uso de un ``< style>``elemento en la `<head>`  
+ Externo -  mediante el uso de un `link` elemento para vincular a un archivo CSS externo

### Colores CSS, fuentes y tamaños

+ La `color` propiedad CSS define el color del texto que se utilizará.  
+ La `font-family` propiedad CSS define la fuente que se utilizará.  
+ La `font-size` propiedad CSS define el tamaño del texto que se utilizará.

### Border CSS - borde

La `border` propiedad CSS define un borde alrededor de un elemento HTML.
```css
p {
  border: 2px solid powderblue;
}
```

### Padding CSS - relleno

La `padding` propiedad CSS define un relleno (espacio) entre el texto y el borde.
```css
p {
  border: 2px solid powderblue;
  padding: 30px;
}
```

### Margin CSS - margen

La `margin` propiedad CSS define un margen (espacio) fuera del borde.
```css
p {
  border: 2px solid powderblue;
  margin: 50px;
}
```

Use el `style` atributo `HTML` para el estilo en línea  
Use el `< style>` elemento `HTML` para definir CSS interno  
Use el `<link>` elemento `HTML` para referirse a un archivo CSS externo  
Use el `< head>` elemento `HTML` para almacenar elementos `< style>` y `<link>`  
Use la `color` propiedad `CSS` para colores de texto  
Use la `font-family` propiedad `CSS` para fuentes de texto  
Use la `font-size` propiedad `CSS` para tamaños de texto  
Use la `border` propiedad `CSS` para bordes  
Use la `padding` propiedad `CSS` para el espacio dentro del borde  
Use la `margin` propiedad `CSS` para espacio fuera del borde  

## section

### Header

Crea una seccion de Header como logo

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
+ ul : Unordered List
+ ol : Orderer List
+ li : List Item
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
+ dl : Definition List
+ dt : Definition Term
+ dd : Definition description
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

`Figure` sirve para colocar contenido relacionado pero que rompa el flujo del contenido.  
Ejemplo un tutorial o contenido, noticia,etc en el que se inserta imagen, video, en el medio del documento que esta relacionado con el contenido.

`Figcaption` es la leyenda del contenido, description, title, opcional
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
el elemento `main` es el mas importante, Contenido principal de la pagina
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

`Div` y `span` son contendores de contenidos para luego ser usados css ,js,etc

## Elementos de Linea y Bloque

los elementos de linea deben estar dentro de un elemento de Bloque,
la mayoria son elementos de bloque `ul`,`li`,`p`,`blockquote`,`article`,`figure`

 ````html
<p>Este es un elemento de bloque</p>
<span>Este es un elemento de linea</span>
````
### Elementos de texto comunes

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
  <a href="https://sebastian.dev">Sebastian Marquez</a>
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
