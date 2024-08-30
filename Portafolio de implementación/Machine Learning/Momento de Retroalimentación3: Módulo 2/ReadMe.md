# Análisis y Evaluación de un Modelo de Regresión con SGDRegressor

Este proyecto implementa y evalúa un modelo de regresión utilizando `SGDRegressor` para un conjunto de datos proporcionado en un archivo CSV. El objetivo es analizar el desempeño del modelo y cómo varía con diferentes tamaños de muestra.

## Contenido del Proyecto

### Carga y Preprocesamiento de Datos

- El archivo CSV `Valhalla23 (1).csv` se carga y se divide en características (X) y etiquetas (y).
- Los datos se dividen en conjuntos de entrenamiento (40%), validación (40%) y prueba (20%) utilizando una semilla fija para garantizar reproducibilidad.

### Entrenamiento del Modelo Base

- Se entrena un modelo `SGDRegressor` con una tasa de aprendizaje de \(1 \times 10^{-4}\), un máximo de un millón de iteraciones, y una semilla fija.
- Se calcula el error cuadrático medio (MSE) en los conjuntos de entrenamiento, validación y prueba para establecer una línea base.

### Evaluación del Modelo Base

- Se genera una gráfica que muestra las predicciones del modelo frente a los valores reales para los conjuntos de entrenamiento, validación y prueba.

### Análisis con Diferentes Tamaños de Muestra

- Se crea una lista de 20 tamaños de muestra únicos entre 2 y 39.
- Para cada tamaño, se entrenan 100 modelos usando subconjuntos aleatorios del conjunto de entrenamiento.
- Se calcula el MSE promedio para cada tamaño de muestra en los conjuntos de entrenamiento y validación.

### Visualización de Errores

- Se genera una gráfica que muestra la evolución del error promedio de entrenamiento y validación en función del tamaño de la muestra.

### Análisis de Sesgo y Varianza

- Se analiza el grado de sesgo (bias) y varianza para los modelos entrenados con diferentes tamaños de muestra.
- Se explica el nivel de ajuste del modelo y cómo cambia a medida que se incrementa el número de muestras.

### Selección del Tamaño Óptimo de Muestra

- Se identifica y justifica la cantidad de muestras más adecuada para el entrenamiento del modelo.
- Se entrena un nuevo modelo con el tamaño óptimo de muestra y se comparan los errores con los obtenidos para el modelo base.

### Comparación y Conclusión

- Se comparan los errores del modelo final con los del modelo base para determinar cuál configuración funcionó mejor y por qué.

## Resultados Clave

- **MSE Entrenamiento, Validación y Prueba:** Los valores obtenidos para el modelo base y los modelos entrenados con diferentes tamaños de muestra.
- **Gráficas de Predicciones:** Visualización de cómo el modelo se ajusta a los datos de entrenamiento, validación y prueba.
- **Errores Promedio por Tamaño de Muestra:** Evolución del MSE en función del tamaño de la muestra.

## Requisitos

- Python 3.x
- NumPy
- pandas
- scikit-learn
- matplotlib
