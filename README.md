# JuegoConLetras

Descripción del problema
Un popular juego de palabras consiste
en detectar aquéllas que han quedado
formadas con las letras que se han
distribuido al azar en un tablero
cuadrangular.
En este caso se desea jugar según una
de las variantes más sencillas que el juego
permite. Esto consiste en responder si las
palabras de un conjunto dado están en el
tablero, mirando sus filas y columnas, e
indicando la dirección (N O S E) en la que
pueden leerse. Tal vez algunas de las
palabras tengan apariciones repetidas,
pero para informar su presencia basta con
considerar alguna de las apariciones
detectadas.
Para asegurar que las respuestas de los
jugadores sean correctas se te solicita que
escribas un programa rapigrama.pas,
rapigrama.cpp o rapigrama.c que,
recibiendo un conjunto de palabras
formadas con letras del alfabeto a...z y un
tablero cuadrangular con una letra en cada
casillero, decida cuales palabras están y la
orientación en la que se leen (N si es
abajo-arriba, E si es izquierda- derecha, S

si es arriba-abajo, O si es derecha-
izquierda).

Datos de entrada
Se recibe un archivo rapigrama.in
con el siguiente formato:
-> Una línea conteniendo un par de
números separados por blanco que indican
la dimensión del tablero D ( 2 ≤ D ≤ 100 ),
y la cantidad P de palabras del conjunto a
buscar ( 1 ≤ P ≤ 10 000 ).
-> D líneas conteniendo las D letras de
cada fila del tablero, tomadas del alfabeto
internacional a...z.
-> P líneas, cada una con una palabra a
buscar, de largo l ( 2 ≤ l ≤ 20 ).

Datos de salida
Se debe generar un archivo
rapigrama.out conteniendo
-> Una línea por cada palabra encontrada
indicando el número de palabra
(coincidente con el orden de aparición
en la entrada), y la dirección en la que
se lee.
