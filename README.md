## 📌 Contexto

El presente proyecto aborda el problema de clasificación de imágenes utilizando redes neuronales artificiales, específicamente una arquitectura de tipo **Multilayer Perceptron (MLP)**. Para ello, se utiliza el dataset **CIFAR-10**, el cual contiene imágenes a color de baja resolución (32x32 píxeles) distribuidas en 10 clases.

El objetivo principal es analizar cómo distintos elementos del diseño de una red neuronal influyen en su desempeño, tales como:

- Funciones de activación (ReLU, Sigmoid)
- Hiperparámetros (learning rate, batch size, épocas)
- Técnicas de regularización (Dropout, L2, Batch Normalization)

A lo largo del desarrollo, se construyen y comparan distintos modelos, comenzando por una arquitectura base sin regularización y avanzando hacia versiones optimizadas. Finalmente, se evalúan los resultados mediante métricas y visualizaciones, identificando las limitaciones del enfoque MLP en tareas de visión computacional.

---

## ⚙️ Tecnologías y herramientas utilizadas

El proyecto fue desarrollado utilizando las siguientes tecnologías:

- **Python** → lenguaje principal de programación  
- **TensorFlow / Keras** → construcción y entrenamiento de modelos de deep learning  
- **NumPy** → manipulación y procesamiento de datos  
- **Matplotlib** → visualización de métricas y resultados  
- **Scikit-learn** → cálculo de métricas de evaluación (precision, recall, F1-score)

---

## 🧠 Enfoque técnico

- Preprocesamiento de datos:
  - Normalización a rango [0,1]
  - Estandarización (media y desviación estándar)

- Arquitectura:
  - Redes densas (Dense)
  - Capas de activación (ReLU / Sigmoid)
  - Regularización (Dropout, L2)

- Evaluación:
  - Accuracy
  - Loss
  - Precision, Recall, F1-score
  - Matriz de confusión

---

## 🎯 Objetivo del estudio

> Comprender el comportamiento de una red neuronal MLP en clasificación de imágenes, analizar sus limitaciones y justificar la necesidad de arquitecturas más avanzadas como las redes convolucionales (CNN).
