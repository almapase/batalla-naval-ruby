# Batalla-Naval-Ruby
## Se pide:

- Hacer una diagrama con objeto de las componentes.
- Un diagrama posible es Flota:
    - Cada flota tiene naves y estado donde está viva si tiene al menos una nave funcional.
    - Cada nave tiene partes y tamaño (donde tamaño es la cantidad de partes) y estado que indica si está hundida o no.
    - Las naves son de distintos tamaños, (eso se refleja en la cantidad de componentes que tienen).
    - Las naves pueden estar alineadas verticalmente o horizontalmente, pero no diagonalmente ni nada con forma de L o cosas raras.
    - Cada parte tiene un set de coordenadas y un indicador que muestra si está golpeada (si ya le han dado o no)
    - cuando todas las partes son golpeadas la nave queda marcada como hundida
    - Un jugador controla una flota.
    - No pueden haber dos partes distintas en las mismas coordenadas.
    - El juego solo debe simular al jugador 1.

- Al empezar el juego se sitúan al azar las naves (solo de la flota enemiga) (cuidar la restricción de que dos partes no pueden ocupar las mismas coordenadas)
- luego en el main loop se pide un input, el input debe ser un par de coordenadas, o, la letra m para mostrar el mapa, o la letra q para terminar el juego.
- Al mostrar el mapa se mostraran las naves enemigas y los puntos donde has atacado (para
debbugging)
- Si es un par de coordenadas revisar contra la flota contraria, si hay una parte hundirla, si todas las partes de la nave están hundidas hundir la nave, si todas las naves enemigas están hundidas
ganar el juego.
