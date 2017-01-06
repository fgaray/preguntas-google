# Breath First Search (BFS)

Este es el dificil: lo que hace es ir recorriendo en forma de círculo los nodos
vecinos. Primero visita sus vecinos antes de visitar los vecinos de los vecinos.

Entonces si el problema requiere encontrar una solución que sabemos que
probablemente esté en el vecindario más cercano, conviene usar este método. Es
igual de caro que DFS pero puede que en promedio sea mejor.

Se implementa con una cola, donde agregamos lo vecinos del nodo que estamos
viendo actualmente.

# Deep First Search (DFS)

Es el más obvio, toma un vecino, luego toma el vecino de el hasta llegar al
final. Si no se encuentra lo que se busca, se vuelve un nivel. Es cuando sabemos
que la solución puede que no esté cerca.


# Bi-directional search

Usa 2 BFS simultáneamente de manera tal que cuando se encuentren los dos
algoritmos se va a encontrar el camino más corto.
