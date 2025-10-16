## Los tensores: cómo la máquina entiende las palabras

En este capítulo aprendimos que los tensores son los valores que determinan las dimensiones semánticas de las palabras.
En otras palabras, cada dimensión nos ofrece una pista sobre qué significa realmente una palabra.

1.5.1. Qué es una dimensión

Para entenderlo de forma sencilla, pensemos en matemáticas o física.
Si queremos saber exactamente dónde está un objeto, necesitamos conocer su posición en tres ejes:

X,

Y,

Z.

Con esas tres dimensiones obtenemos su ubicación precisa.

Del mismo modo, para definir un color usamos tres dimensiones: rojo, verde y azul (RGB).
Cada una representa una parte de la mezcla, y al combinarlas obtenemos el color exacto.

1.5.2. De los colores a las palabras

Con las palabras sucede algo muy parecido.
Imagina un juego en el que tu amigo piensa una palabra y tú vas haciendo preguntas para adivinarla.
Cada respuesta te da una dimensión de información sobre esa palabra.

Por ejemplo, podrías preguntar:

¿Es un sustantivo?

¿Pertenece al ámbito de la astronomía?

¿Implica una acción o un estado?

Cada respuesta añade una coordenada más a la “posición” de esa palabra dentro del espacio del lenguaje.

Los ordenadores, sin embargo, no entienden palabras sino números.
Así que, en lugar de respuestas escritas, asignamos valores numéricos:

1 = sí,

2 = no,

3 = no sé,

4 = no válido.

O en otro caso:

1 = sustantivo,

2 = verbo,

3 = adjetivo…

Cuando reunimos todas esas respuestas en forma de números, obtenemos un tensor semántico: una lista de valores que, combinados, describen de forma numérica el significado de la palabra.
¿Fácil de visualizar, verdad?

1.5.3. Tipos de dimensiones

Cada palabra puede tener muchas dimensiones distintas, pero podemos agruparlas en tres tipos principales:

Gramaticales o estructurales – describen la función de la palabra en una frase (nombre, verbo, adjetivo…).

Contextuales o de área de conocimiento – indican en qué campo se usa (astronomía, biología, música…).

Semánticas o funcionales – expresan la relación de significado profundo con otras palabras (por ejemplo, emitir y lanzar son casi idénticas).

1.5.4. Ejemplo: cuando el significado cambia

Observa las frases:

El Sol emite fotones.

El Sol lanza fotones.
Ambas son casi idénticas: su estructura y área de conocimiento son similares, y su significado profundo también.

Pero si decimos:

El Sol absorbe fotones.
Aunque gramaticalmente y por contexto sea correcta, semánticamente cambia por completo.
La diferencia está en la dirección de la acción, una dimensión invisible pero fundamental del significado.

1.5.5. Los tensores FFE

En Aurora llamamos a estos tensores FFE (Forma, Función y Estructura):

Forma = el área o dominio del conocimiento.

Función = el significado o papel que cumple la palabra.

Estructura = su categoría gramatical y relaciones sintácticas.

El objetivo de Aurora es combinar estas tres visiones para construir una representación completa y eficiente del lenguaje: un tensor que no solo entienda las palabras, sino la realidad que representan.