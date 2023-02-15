# Markdown de 0 a 100

## Que es Markdown

Es un lenjuage de marcado ligero que se usa para escribir y procesar texto plano para darle formato. <br> Tiene una sintaxis sencilla y amigable.
Es compatible con web (html).

## Contents

- [Markdown de 0 a 100](#markdown-de-0-a-100)
  - [Que es Markdown](#que-es-markdown)
  - [Contents](#contents)
- [Sintaxis basica](#sintaxis-basica)
  - [Encabezados](#encabezados)
  - [Comentarios](#comentarios)
  - [Parrafos](#parrafos)
  - [Saltos de Linea](#saltos-de-linea)
  - [Enfasis](#enfasis)
  - [Listas](#listas)
  - [Enlaces](#enlaces)
  - [Imagenes](#imagenes)
  - [Codigo](#codigo)
    - [Codigo en bloque](#codigo-en-bloque)
- [Sintaxis extendida](#sintaxis-extendida)
  - [Tablas](#tablas)
    - [Alinear tablas](#alinear-tablas)
- [Herramientas](#herramientas)


# Sintaxis basica

## Encabezados

Se usan para llamar la atención sobre una sección. Como su nombre lo indica, actúan como títulos o subtítulos sobre las secciones.

Hay seis tipos de encabezados en tamaños decrecientes y se usa el símbolo hash (**#**) para definir el tamaño del título.

>**Por compatibilidad siempre ponga un espacio luego de cada (#) y separe con una linea en blanco antes y después de cada encabezado**

``` markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

## Comentarios

Para ocultar contenido puedes usar  
<!-- Este es un comentario -->
    <!-- Este es un comentario -->

## Parrafos

Para crear párrafos, debe mantener el texto aliniado a la izquierda y usar una línea en blanco para separar una o más líneas de texto.

Por ejemplo:

    Linea 1: Este es un parrafo
    Linea 2:  
    Linea 3: Este es otro parrafo


## Saltos de Linea

Para crear saltos de linea termine una linea con 2 espacios.  
O escriba (**< br >**) <br> para ejecutar un salto de linea

**Por ejemplo:**

    Linea 1: Este es una linea  //2 espacios y enter
    Linea 2: Esta es otra linea

    Linea 1: Esta es una linea <br>
    Linea 2: Esta es otra linea

## Enfasis

Tres básicos elementos en este formato de texto son: 

- itálica
    > Para hacer una palabra en itálica debes poner un asterisco (*) al inicio y al final de cada palabra.
- negrita
    > Si quieres el formato negrita, serán dos asteriscos (**) al inicio y al final de la palabra o frase.
- tachada
    > Para formato tachado, entonces serán dos virgulillas (~~) al inicio y final de cada palabra o frase.
- Citas
    > Para crear citas se usa (>)
    >
    > en las lineas que necesites citar

```markdown
*Itálica*

**Negrita**

~~Tachada~~
 ```

> ***Negrita e italica:*** se ebe usar (***)


## Listas

Utiliza las listas ordenadas (numeradas con **1.**) cuando los elementos deban seguir un orden y las listas desordenadas (con viñetas/guiones **-**) cuando no importa el orden de las instrucciones.

- **Lista desordenada**
- Usa este tipo de listas
- Cuando no importe el orden
- De los elementos de la lista
  - Tambien puedes tener
  - sub listas
  >Si necesita comenzar un elemento de lista desordenado con un número seguido de un punto, puede usar una barra invertida (\\) para escapar del punto.
  - 1968\. A great year!

1. **Lista ordenada**
2. Aquí los elementos
3. De la lista
4. Debes ir en este orden
   1. Tambien puedes tener
   2. sub listas

## Enlaces

Para crear un enlace debes encerrar el texto del enlace entre corchetes ( [ ] ) y después encerrar el enlace entre paréntesis ( ( ) ).


    [Dinamo](https://dinamo.app/)

Ejemplo: Este es un **[enlace](https://dinamo.app/)**

<br>

> Tambien puedes centralizar el enlace creando un ID e insertando en enlace en la variable.

    Este es un enlace -> [Dinamo1]

    [Dinamo1]: https://dinamo.app/

> Para URL rápidas y correos electronicos puedes usar <>
> 
> <https://www.markdownguide.org>
> 
> <fake@example.com>


## Imagenes

Para crear una imagen debes usar ( ![texto alternativo] ) y después encerrar el enlace entre paréntesis ( ( ) ).

    ![Este es un texto alternativo](https://dinamo.app/img/logo.6e68e897.png)


![Este es un texto alternativo](https://dinamo.app/img/logo.6e68e897.png)

>Puedes centralizar la imagen creando un ID e insertando el enlace de la imagen en la variable.

    Este es una imagen -> ![Texto alternativo][imagenID]

    [imagenID]: https://dinamo.app/img/logo.6e68e897.png


## Codigo

Para denotar una palabra o frase como código, enciérrela entre comillas graves (`).

this is code -> `nano`.

    this is code -> `nano`.


Si la palabra o frase que desea indicar como código incluye uno o más acentos graves, puede escaparlos encerrando la palabra o frase entre dobles acentos graves (``).

this is code -> ``Use `code` in your Markdown file.``

    this is code -> ``Use `code` in your Markdown file.``

### Codigo en bloque

Para crear bloques de código, Usa (```) al inicio y final del bloque o  identa cada línea del bloque con al menos cuatro espacios o una tabulación.

> Puedes especificar el lenguaje usando ```lenguaje al inicio del bloque
```javascript
var a = 1
```
    javascript
    var a = 1


# Sintaxis extendida

## Tablas

Para agregar una tabla, use tres o más guiones (---) para crear el encabezado de cada columna y use barras verticales (|) para separar cada columna. Para compatibilidad, también debe agregar una tubería en cada extremo de la fila.

> Puede mostrar un carácter de barra vertical (|) en una tabla utilizando su código de carácter HTML (& #124;)

| Syntax      | Description |
| ----------- | ----------- |
| Header &#124;     Header | Title       |
| Paragraph  Paragraph | Text        |

### Alinear tablas

Puede alinear el texto de las columnas a la izquierda, a la derecha o al centro agregando dos puntos (:) a la izquierda, a la derecha o a ambos lados de los guiones dentro de la fila del encabezado.

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |


# Herramientas

- https://boostnote.io/
- https://www.inkdrop.app/


...................

Listas de tareas
- [x] Tarea  realizada
- [x] Otra tarea realizada sin ordenar
- [ ] Tarea sin realizar
Producirá

[x] Tarea realizada
[x] Otra tarea realizada sin ordenar
[ ] Tarea sin realizar

