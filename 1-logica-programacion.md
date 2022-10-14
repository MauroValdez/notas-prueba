## TEMARIO 1: Algoritmo e instrucciones

#### Definición

En términos simples un Algoritmo es un conjunto de pasos que deben ser ejecutados en orden para realizar una tarea y/o resolver un problema.

De un modo más formal, un algoritmo es una secuencia finita de operaciones realizables, cuyo seguimiento paso a paso debe conducir a la solución de un problema en un tiempo finito.

ejemplo en lo cotidiano:
  esperar tono
  marcar el número de teléfono destino
  si  contestan
    saludar
    hablar con la persona
    despedirse
  fin  si
  colgar el teléfono

#### Algoritmo en lo cotidiano 

Todos en la vida real hemos realizado algoritmos en múltiples ocasiones,ya sea para resolver un problema matemático o preparar una comida.

#### Intrucción y programacón

La programación consiste en adaptar un algoritmo mediante un lenguaje de programación a un dispositivo capaz de entenderlo y cada uno de sus pasos son referidos o llamados "instrucción"

Una intrucción es una acción específica entendida por el dispositivo programable y en consecuencia realizable o ejecutable por el mismo

-algoritmo para iniciar sesión
mostrar vista
capturar datos
consultar con la base de datos 
si existe y son iguales
  iniciar sesión
si no 

## TEMARIO 2: Algoritmo usando bloques

#### Definición

La programación con bloques es una estrategia para desarrollar la lógica algorítmica usando un computador, la cual consiste en conectar bloques como un rompecabezas

#### Ejercicio inicial:

repetir hasta llegar a la meta
hacer AVANZAR
  si  hay camino a la izquierda
  hacer girar a la izquierda
  si hay camino a la derecha 
  hacer girar a la derecha

## TEMARIO 3 Flujograma

#### Definición

Un flujograma o diagrama de flujo de datos DFD es una representación gráfica de un algoritmo, la cual debe presentar la información de manera clara, concisa y ordenada

Algoritmo LLAMAR
  levantar_auricular
  marcar_numero
  esperar_tono
  contestar
    V saludar
      hablar_persona
      despedirse
    F dejar_mensaje
  colgar
Fin Algoritmo

## TEMARIO 4 Lenguaje y Pseudolenguaje

#### Definición 

Lenguaje de programación:
  Es un lenguaje artificial usado para controlar el comportamiento de un dispositivo programable, generalmente una computadora

  Se componen de un conjunto de reglas sintácticas que permiten realizar instrucciones que posteriormente serán procesadas

Pseudolenguaje
  Es un lenguaje de documentación de programas similar al ingles o español

  No hay ningún estándar definido para Pseudolenguaje, por ende cualquier persona puede crear uno propio

Clasificación

  Nivel de abstracción
    Lenguaje Maquina: codigo binario (11001110101)
    Bajo Nivel: lenguaje ensamblador
    Nivel Medio: C, C++, Pascal, Cobol
    Alto Nivel: Java, Delphi, PHP
  
  Paradigma de programación 
    No Estructurados: lenguajes ensambladores
    Estructurados: Pascal, C 
    Orientado a Objetos: C++, Java, PHP

#### Código fuente y ejecutable

Código fuente
  es un conjunto de líneas de texto con los pasos que debe seguir la computadora para ejecutar un programa, los cuales están escritos en un lenguaje de programaciónsegúnlas reglas del mismo

Código ejecutable
  es un archivo que tiene todos las instrucciones en código máquina que le indica a l CPU las operaciones a realizar electronicamente

#### IDE (Entorno de desarrollo)

Por sus siglas, Entorno de Desarrollo Integrado. Es un software especializado y utilizado por los programadores para escribir el código fuente en algun lenguaje de programación determinado

Éste tipo de programas ofrecen una gama de herramientas que le permiten al programador ser más eficiente en el desarrollo de software al momento de programar

## TEMARIO 6 Pseudocódigo y PseInt

#### Definición

Pseudocódigo
  Es un término usado en la informática para referirse a un lenguaje artificial e informal, es usado por los programadores para el diseño y creación de algoritmos mediante un Pseudilenguaje

  No es un lenguaje de programción real

 
#### PseudoInterprete

Es un programa creado para leer y ejecutar instrucciones de un pseudocódigo

## Lenguajes 

#### Palabras recervadas

Todo lenguaje de programación tiene palabras unicas que no podras usar ya que tienen su funcion establecida

#### Comentarios

En todos los lenguajes se puede agragar comentarios para documentar lo que estamos realizando, son ignorados por el interprete o compilador

#### Datos y Variables

Datos 
  es simplemente un elemento dentro de la ejecución de un programa 
  puede ser un número, palabra, cadena de texto

Variable
  es como un contenedor donde podemos almacenar datos
  la podemos diseñar para que almacene datos especificos

#### Tipos de Datos

Todas variables tiene asociados un tipo de datos que pueden almacenar, los tipos de datos se clasifican de dos formas

Primitivos
  son los predefinidos por cada lenguaje de programción

Definido por el usuario
  son tipos de datos más complejos agragados por el programador

Los tipos de datos primitivos se basan en 
  Númericos
    Enteros o decimales, positivos o negativos
  Alfanuméricos
    Conjuntos de letras, números y caracteres especiales
    Se dividen en
      Cadena de texto (String)
        Formadas por un conjuntos de caracteres como un nombre o número de placa
      Caracter (Char)
        una letra, un número o un símbolo
  Lógicos o buleanos
    Es un tipo de datos que toma solo dos valores
      Verdadero o Falso

#### Instruccion de entrada

Una instrucción de entrada (o simplemente entrada) consiste en asignar a una o más variables, uno o más valores (datos) recibidos desde el exterior.

Normalmente, los datos son recogidos desde la entrada estándar (el teclado), pero, también existen otros dispositivos de entrada (el ratón, el escáner...).

En pseudocódigo, una instrucción de entrada se puede escribir utilizando la siguiente sintaxis:

Leer <variable_1>, ..., <variable_n>

#### Instrucción de salida

Una instrucción de salida (o simplemente salida) consiste en llevar hacia el exterior los valores (datos) obtenidos de la evaluación de una lista de expresiones.

Normalmente, los datos son enviados a la salida estándar (la pantalla), pero, también existen otros dispositivos de salida (la impresora, el plotter...).

En pseudocódigo, una instrucción de salida se puede escribir utilizando la siguiente sintaxis:

Escribir <expresión_1>, ..., <expresión_n>

#### Instrucción de asignación

Una instrucción de asignación (o simplemente asignación) consiste en asignar el resultado de la evaluación de una expresión a una variable.

EJEMPLO A partir de la definición de las siguientes declaraciones de variables en pseudocódigo:

Definir nombre Como Cadena

Definir nota_1, nota_2, nota_3, nota_media Como Real

#### Instrucción condicional

Una instrucción condicional nos permite plantear la solución a un problema considerando los distintos casos que se pueden presentar. De esta manera, podemos utilizar un algoritmo distinto para enfrentar cada caso que pueda existir en el mundo

#### Instrucción en cascada

Cuando el problema tiene más de dos casos, es necesario utilizar una cascada (secuencia) de instrucciones if-else, en donde cada condición debe indicar sin ambigüedad la situación que se quiere considerar. 

#### Ciclo para (For)

La instrucción Para ejecuta una secuencia de instrucciones un número determinado de veces.

Para <variable> <- <inicial> Hasta <final> [Con Paso <paso>] Hacer
	<instrucciones>
FinPara

Al ingresar al bloque, la variable <variable> recibe el valor <inicial> y se ejecuta la secuencia de instrucciones que forma el cuerpo del ciclo.

Luego se incrementa la variable <variable> en <paso> unidades y se evalúa si el valor almacenado en <variable> superó al valor <final>.

Si esto es falso se repite hasta que <variable> supere a <final>.

Si se omite la cláusula Con Paso <paso>, la variable <variable> se incrementará en 1.

#### Ciclo repetir - hasta que (do while)

La instrucción Repetir-Hasta Que ejecuta una secuencia de instrucciones hasta que la condición sea verdadera.

Repetir
    <instrucciones>
Hasta Que <condición>

Al ejecutarse esta instrucción, la secuencia de instrucciones que forma el cuerpo del ciclo se ejecuta una vez y luego se evalúa la condición. Si la condición es falsa, el cuerpo del ciclo se ejecuta nuevamente y se vuelve a evaluar la condición. Esto se repite hasta que la condición sea verdadera.

Note que, dado que la condición se evalúa al final, las instrucciones del cuerpo del ciclo serán ejecutadas al menos una vez.

Además, a fin de evitar ciclos infinitos, el cuerpo del ciclo debe contener alguna instrucción que modifique la o las variables involucradas en la condición de modo que en algún momento la condición sea verdadera y se finalice la ejecución del ciclo.

#### Ciclo mientras (while)

La instrucción Mientras ejecuta una secuencia de instrucciones mientras una condición sea verdadera.

Mientras <condición> Hacer
    <instrucciones>
FinMientras

Al ejecutarse esta instrucción, la condición es evaluada. Si la condición resulta verdadera, se ejecuta una vez la secuencia de instrucciones que forman el cuerpo del ciclo. Al finalizar la ejecución del cuerpo del ciclo se vuelve a evaluar la condición y, si es verdadera, la ejecución se repite. Estos pasos se repiten mientras la condición sea verdadera.

Se puede dar la circunstancia que las instrucciones del bucle no se ejecuten nunca, si al evaluar por primera vez la condición resulta ser falsa.

Si la condición siempre es verdadera, al ejecutar esta instrucción se produce un ciclo infinito. A fin de evitarlo, las instrucciones del cuerpo del ciclo deben contener alguna instrucción que modifique la o las variables involucradas en la condición, de modo que ésta sea falsificada en algún momento y así finalice la ejecución del ciclo.










