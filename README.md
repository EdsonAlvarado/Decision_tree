# Arboles de decisión (Decision Tree Classifier)

## Concepto

Un árbol de decisión es una forma gráfica y analítica de   representar   todos   los   eventos   (sucesos)   que   pueden  surgir  a  partir  de  una  decisión  asumida  en  cierto momento. 

Dado un conjunto de datos se fabrican diagramas de construcciones lógicas, muy similares a los sistemas de predicción basados en reglas, que sirven para representar y categorizar una serie de condiciones que ocurren de forma sucesiva, para la resolución de un problema.

Los árboles de decisión son una familia popular de métodos de clasificación y regresión.
El aprendizaje del árbol de decisiones es uno de los enfoques de modelado predictivo utilizados en estadística, minería de datos y aprendizaje automático. Utiliza un árbol de decisiones (como modelo predictivo) para pasar de las observaciones sobre un elemento (representado en las ramas) a las conclusiones sobre el valor objetivo del elemento (representado en las hojas). Los árboles de decisión en los que la variable de destino puede tomar valores continuos (normalmente números reales) se denominan árboles de regresión. Los árboles de decisión se encuentran entre los algoritmos de aprendizaje automático más populares dada su inteligibilidad y simplicidad.



![alt text](https://runestone.academy/runestone/static/pythoned/_images/booktree.png)

## Elementos del arbol

- Nodos: Es una decisión de entre varias posibles, a medida que aumenta el número de nodos aumente el número de posibles finales a los que puede llegar.
- Vectores: Es el conjunto de decisiones para llegar a un determinado final.
- Ramas: Son las uniones entre los nodos.

## Caracteristicas del arbol

1. El inicio del arbol esta dado por un solo nodo que no es apuntado por nada y debe de ser el único nodo con esta caracteristica.
2. Los demas nodos deben de estar conectados a una rama.
3. Existe un único camino para llegar desde el nodo inicial hacia un determinado final dentro del arbol.
