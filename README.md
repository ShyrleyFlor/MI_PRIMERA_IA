# MI_PRIMERA_IA
Este script muestra cómo construir y entrenar una red neuronal simple para entender los fundamentos básicos de la inteligencia artificial. Utiliza TensorFlow y Keras para crear una red neuronal que pueda aprender a predecir valores en base a un conjunto de datos.
## Librerías:
tensorflow: Biblioteca para crear y entrenar redes neuronales.
numpy: Para manejar arrays y operaciones matemáticas.
matplotlib.pyplot: Para graficar los resultados.
## Creación de la Red Neuronal:
Se define una red neuronal con una sola capa densa (Dense) con una neurona y una entrada.
Capa densa (o capa completamente conectada): es una de las arquitecturas más básicas y comunes.
## Compilación del Modelo:
Utilizamos el optimizador Adam con una tasa de aprendizaje de 0.01.
La función de pérdida es el error cuadrático medio, que mide la diferencia entre los valores predichos y los valores reales.
## Entrenamiento:
Entrenamos el modelo con los datos proporcionados durante 1000 épocas.
## Evaluación y Predicción:
Se grafica el error del entrenamiento para observar cómo mejora el modelo.
Finalmente, se realiza una predicción para un valor de entrada y se muestra el resultado en Fahrenheit.
Este ejemplo básico de red neuronal ayuda a entender cómo funcionan los principios básicos del aprendizaje automático y la creación de modelos predictivos.
