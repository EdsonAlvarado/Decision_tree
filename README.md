# Arboles de decisión (Decision Tree Classifier)

## Concepto

Un árbol de decisión es una forma gráfica y analítica de   representar   todos   los   eventos   (sucesos)   que   pueden  surgir  a  partir  de  una  decisión  asumida  en  cierto momento. 

Dado un conjunto de datos se fabrican diagramas de construcciones lógicas, muy similares a los sistemas de predicción basados en reglas, que sirven para representar y categorizar una serie de condiciones que ocurren de forma sucesiva, para la resolución de un problema.

![alt text](https://runestone.academy/runestone/static/pythoned/_images/booktree.png)

## Elementos del arbol

- Nodos: Es una decisión de entre varias posibles, a medida que aumenta el número de nodos aumente el número de posibles finales a los que puede llegar.
- Vectores: Es el conjunto de decisiones para llegar a un determinado final.
- Ramas: Son las uniones entre los nodos.

## Caracteristicas del arbol

1. El inicio del arbol esta dado por un solo nodo que no es apuntado por nada y debe de ser el único nodo con esta caracteristica.
2. Los demas nodos deben de estar conectados a una rama.
3. Existe un único camino para llegar desde el nodo inicial hacia un determinado final dentro del arbol.
