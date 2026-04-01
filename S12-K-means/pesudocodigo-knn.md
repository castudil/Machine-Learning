seudocodigo de KNN(data,K,d(.))
data, la data a procesar
K el numero de vecinos
d la distancia

paso 1: dado un punto q, calcular la distancia entre q y cada uno de los puntos del conjunto.

complejidad O(nd)

paso 2: ordemanos de menor a mayor con respecto a la distancia.

O(n log n)

paso 3: escoger las K mejores

paso 4: votacion simple y se reponde con la mayoria

O(k)

Problema práctico: que paso es el mas costos si: 10^6 instancias,  100 dimensiones?

Trabajo autonomo: implementa tu propia versión de KNN en Python sin usar la biblioteca sklearn.

