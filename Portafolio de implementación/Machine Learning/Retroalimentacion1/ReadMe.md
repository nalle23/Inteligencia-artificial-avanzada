# 📊 Implementación de Algoritmo de Regresión Lineal desde Cero

Este proyecto forma parte del portafolio de implementación del módulo de Machine Learning y está diseñado para resolver uno de los desafíos iniciales propuestos en clase.

---

## 📝 Instrucciones del Entregable

1. **Seleccionar el Challenge:**
   - Se ha elegido implementar un algoritmo de **Regresión Lineal** para resolver el problema presentado en `Week01_Challenge.pdf`.

2. **Desarrollo del Algoritmo:**
   - **Implementación Manual:** El algoritmo de regresión lineal se ha implementado desde cero sin utilizar ninguna biblioteca o framework de aprendizaje automático.
   - **División del Conjunto de Datos:** 
     - **Entrenamiento:** 80%
     - **Prueba:** 20%
   - **Entrenamiento del Modelo:** 
     - **Tasa de Aprendizaje (`alpha`):** 0.001
     - **Parámetros Iniciales (`theta`):** Inicializados en ceros.
     - **Número de Iteraciones:** 5000

3. **Evaluación del Modelo:**
   - **Predicciones:** Se generaron predicciones para el conjunto de prueba y se compararon con los datos reales mediante una gráfica.
   - **Cálculo de la Función de Costo:** Se calculó el costo para ambos conjuntos de entrenamiento y prueba.

4. **Entrega de Archivos:**
   - **Jupyter Notebook:** `Momento de Retroalimentaación_Modulo2.ipynb` con todo el desarrollo y código comentado.
   - **PDF del Notebook:** `Momento de Retroalimentaación_Modulo2.pdf`.

---

## 📂 Contenido del Repositorio

- `Modulo_ML/Entregable1/`
  - `Momento de Retroalimentaación_Modulo2.ipynb` : Jupyter Notebook con la implementación del algoritmo.
  - `Momento de Retroalimentaación_Modulo2.pdf` : Versión en PDF del Jupyter Notebook.
  - `Valhalla23 (1).csv` : Conjunto de datos utilizado para el entrenamiento y prueba.

   RUTA: Portafolio de implementación/Machine Learning/Retroalimentacion1/Valhalla23 (1).csv


---

## 🔍 Explicación de la Selección de Hiperparámetros

- **Tasa de Aprendizaje (`alpha`):** Se eligió una tasa de aprendizaje de 0.001 para asegurar una convergencia estable del algoritmo. Una tasa más alta podría causar oscilaciones o divergencia, mientras que una tasa más baja ralentiza el proceso de aprendizaje.
  
- **Parámetros Iniciales (`theta`):** Los parámetros se inicializaron en ceros para simplificar el inicio del entrenamiento. Esto es una práctica común cuando no se tiene información previa sobre los valores óptimos.


---

## Cambios
`Momento de Retroalimentaación_Modulo2.ipynb (2)- Colab.pdf`

`Momento de Retroalimentaación_Modulo2 (1)- Colab.ipynb`

- El readme debe decir cuales archivos se van a revisar y la ruta para encontrarlos
- El modelo se entrena sobre un subset de entrenamiento del dataset
- El readme contiene una sección de cambios implementados, donde se mencione el cambio indicado por el docente y lo que se hizo para resolverlo (solo aplica para entrega final)
- Explicar el motivo de la elección de la tasa

---
