# Big O

Mejor caso: Si los elementos son iguales, entonces quicksort va a recorrer el
arreglo en tiempo O(n).

Peor caso: Si elegimos un pivote que sea el elemento más grande del arreglo,
entonces vamos a tener un tiempo de ejecución de O(n^2).

Caso esperado: Quicksort O(n * log(n))



En el caso de la complejidad espacial, el espacio de stack tambien cuenta en las
funciones recursivas.


O(n^2) < O(2^n) < O(n!) < O(n^n)



## Tiempo Amortizado

Nos permite expresar situaciones en las que el O() sea más grande, pero en la
mayoria de los casos es un mejor tiempo O().

Un arreglo dinámico es O(x) en el peor caso (ya que debe copiar x elementos) y
O(1) en el mejor caso.
