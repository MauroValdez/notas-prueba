## CSS

#### COMO INSERTAR CSS EN HTML

Existen cuatro formas de incluir CSS en un documento HTML
  En la cabecera a través de la etiqueta <style>
    <style> código css </style>
  En línea dentro de la etiqueta
    <p style="código css"></p>
  Asociando una hoja de estilo externa a nuestro documento
    <link rel="stylesheet" href="style.css">
  A travéz de @import dentro de las etiquetas
    <style> @import url("style.css"); </style>

#### SINTAXIS DE CSS

  selector {
    propiedad: valor;
  }

  Ejemplo:

  body {
    background: red;
  }

Existen at-rules (reglas arroba)

@media{}      => tamaño de pantallas
@font-face{}  => importar estilos de fuentes
@keyframes{}  => animaciones
@import()     => importar un archivo

#### TIPOS DE SELECTORES

Un selector hace referencia al elemento que se le aplicará el estilo

  Los selectores podemos agruparlos en 4 grupos
    Selectores básicos
    Selectores combinadores
    Selectores de pseudo-elementos
    Selectores de pseudo-clases
    y más...

#### ESPECIFICIDAD, CASCADA Y HERNECIA

La herencia se aplica con el valor inherit, esto obliga al elemento a heredar la propiedad de su elemento más cercano.

La cascada es el orden en el que se le aplicará n los estilos al ir leyendo el css, los estilos que vienen después sobrescriben a los anteriores.

La especificidad en el peso que tiene un selector cuando hay conflictos de estilos

La especificidad se divide en:

  etiquetas             => 5
  clases y pseudoclases => 4
  ID                    => 3
  estilos en línea      => 2
  !important            => 1

#### RESETEAR ESTILOS POR DEFECTOS

Todos los navegadores de forma predeterminada tienen estilos que pueden afectar a la creación de nuestra página web y para ello necesitamos resetearlo

La forma más facil de hacerlo es usando normalize (visitar página web)

#### METODOLOGÍA DE BEM

Una metodología en CSS son una serie de consejos para estructurar nuestras clases de una forma sencilla, escalable y reutilizable

BEM es una de las más utilizadas en el mundo

Su nombre viene de las siglas Block, Element, Modifier

  Block (bloque) Es cada uno de los elementos del bloque
    un menú, una galería, un formulario

  Element (elemento) Es cada uno de los elementos del bloque
    un link, una foto, un campo de texto

  Modifier (modificador) Cuando un bloque se repite en otro lugar de nuestra webpero con alguna modificación
    el color del texto, el tamaño de la fuente

