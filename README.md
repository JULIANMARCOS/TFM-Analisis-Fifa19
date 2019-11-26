JULIÁN MARCOS VÁZQUEZ


# TFM-Analisis-Fifa19
Estudio jugadores Fifa19 para aproximación estudio pasajeros en aeropuertos.

En mi TFM utilizaré diferentes algoritmos de regresión de Machine Learning para poder estimar la puntuación total de un jugador del FIFA19 a partir de otras habilidades de cada jugador. Mi objetivo es obtener el algoritmo que me dé el mejor RMSE y MAE.

ALGORITMOS
Una vez me decidí por realizar una regresión dentro del aprendizaje supervisado, realicé los cálculos de los 3 algoritmos vistos en clase para comprobar cuál de todos me ofrecía mejores resultados: 
1)	Regresión lineal: Permite determinar el grado de dependencia de las series de valores X e Y, prediciendo el valor y estimado que se obtendría para un valor x que no esté en la distribución.,
2)	 K-vecinos: predice cogiendo los k vecinos más cercanos. Parte de la idea de que una nueva muestra será clasificada en base a la cual pertenezca la mayor cantidad de vecinos más cercanos del conjunto de entrenamiento.
3)	Árboles de decisión: Un árbol de decisión está formado por un conjunto de nodos de decisión (interiores) y de nodos-respuesta (hojas):
Un nodo de decisión está asociado a uno de los atributos y tiene 2 o más ramas que salen de él, cada una de ellas representando los posibles valores que puede tomar el atributo asociado. 
Una hoja o leaf, está asociado a la clasificación que se quiere proporcionar, y devuelve la decisión del árbol con respecto al ejemplo de entrada.

Además, utilicé el método aprendido en clase (Grid SearchCV) y que indica cuál es el valor óptimo de los parámetros tanto para K-vecinos como para Árboles de decisión. 

MÉTRICAS: 
Dentro de cada algoritmo, he usado las siguientes métricas para comprobar la eficiencia de cada uno de ellos utilicé las métricas utilizadas en clase:
1)	MAE: Error absoluto medio: es la suma de los valores absolutos del error
2)	MSE: Error cuadrático medio, es la media de la diferencia entre los puntos reales de datos y la salida predicha, al cuadrado
3)	RMSE: Raíz del error cuadrático medio, es la raíz de la media de los errores elevados al cuadrado.

