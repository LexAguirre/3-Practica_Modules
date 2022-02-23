![Logo](img/ucol-logo.jpg)

# Práctica 3: Modules

> Primera Parcial

- FACULTAD DE TELEMATICA
- INGENIERÍA EN SOFTWARE
- “4ºG”
- ESTRUCTURA DE DATOS
- CATEDRATICO: ULIBARRI IRETA CARLOS
- AGUIRRE ROMERO RAMÓN ALEJANDRO

## OBJETIVO

- En la clase pasada abordamos los conceptos de
  -- First class functions
  -- Function expressions
  -- Passing functions as parameters

- Los conceptos que quedan pendientes son:
  -- Functions created on the fly
  -- Interpolación de strings
  ---- String interpolation
  ---- Embedded expressions
  ---- Multiline strings
  -- Javascript Modules
  -- Event loop

> ENTREGA: DOMINGO 27 DE FEBRERO DEL 2022

## EXPLICACIÓN DEL PROCESO

1.

## EVENT LOOPS

Las "arrow functions" de ES6 son una nueva manera de expresar las funciones de siempre, de un modo resumido y con algunas características nuevas. Aunque son comúnmente conocidas como arrow functions, también podrás oír hablar de ellas con su denominación en español, funciones flecha, o como "fat arrow functions", ya que para formar la flecha se usa una línea doble, del signo matemático igual "=". Además de servir como azúcar sintáctico, son además una de las novedades más representativas de ES6, y que nos soluciona uno de los problemas más representativos y clásicos de Javascript en su versión ES5, el nuevo contexto generado por las funciones normales.

- Cómo expresar una función con las arrow functions

Esta parte es muy simple, en vez de usar la palabra clave function se utiliza el símbolo de la flecha gorda, como se puede ver en el siguiente código:
Como has visto, no solo se usa la flecha, sino que los paréntesis donde se colocarían los parámetros de la función también se mueven de lado, colocándolos antes de la flecha. La invocación de la función se realizaría como ya conoces.

- Parámetros de las funciones flecha

El tratamiento de los parámetros se realiza como hasta ahora, simplemente se colocan entre los paréntesis. Veamos este segundo ejemplo.
El único detalle es que, en el caso que tengamos un único parámetro, podemos ahorrarnos colocar esos paréntesis.

- Ausencia de las llaves de la función

Existe otro caso especial, en el que podemos también ahorrarnos algún carácter extra, en este caso las llaves de apertura y cierre de la función. Sería cuando solamente tenemos una línea de código en nuestra función. La función del saludo la podrías ver así también:

- Ausencia de la palabra return

Si tenemos una única línea de código y la función devuelve un valor también nos podríamos ahorrar la palabra return, además de las llaves como se dijo antes. La función del cuadrado de un número podría expresarse así.

- Código más compacto

Como ves, explotando todas las posibilidades de las funciones flecha, podemos obtener un código muy compacto. Para observar este hecho puedes compararlo con la declaración de una función de una manera tradicional en ES5:
Quizás en la declaración de una función así sola en el código no se llegue a ver tanta ventaja, pero al tratarse Javascript de un lenguaje lleno de funciones callback se consigue bastante ahorro de líneas de código.
