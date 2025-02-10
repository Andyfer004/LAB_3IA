# Laboratorio 3 - Inteligencia Artificial

## Semestre I - 2025

### Introducción
Este laboratorio tiene como objetivo explorar y aplicar diferentes técnicas fundamentales en el ámbito del aprendizaje automático, incluyendo el descenso de gradiente, selección de características y redes neuronales. Se han desarrollado ejercicios teóricos y prácticos para profundizar en estos conceptos y evaluar su impacto en modelos de Machine Learning.

### Contenido
El laboratorio se divide en dos secciones principales:

## **Task 1 - Preguntas Teóricas**
En esta sección se responden preguntas clave sobre los siguientes temas:
1. **Diferencias entre descenso de gradiente, descenso de gradiente por mini batches y descenso de gradiente estocástico.** Se discuten sus ventajas, desventajas y aplicaciones en diferentes escenarios de optimización.
2. **Comparación entre extracción de características (feature extraction) y selección de características (feature selection).** Se presentan ejemplos de cuándo es más apropiada cada técnica.
3. **Arquitectura y funcionamiento de un perceptrón de una sola capa.** Se explica cómo aprende y cómo actualiza sus parámetros sin el uso de backpropagation.

## **Task 2 - Ejercicios Prácticos**
### **Task 2.1 - Gradiente Descendiente Estocástico**
Se implementan tres variantes del descenso de gradiente para optimizar una función polinómica de tercer grado:
- **Descenso de gradiente estándar**
- **Descenso de gradiente por mini batches**
- **Descenso de gradiente estocástico**

Se compara el rendimiento de cada método en términos de:
- **Tiempo de ejecución**
- **Fitness de los modelos obtenidos**
- **Aproximación visual de la función polinómica**

### **Task 2.2 - Feature Selection**
Se aplica selección de características sobre un dataset de partidas de League of Legends, utilizando al menos tres técnicas distintas. Posteriormente, se entrena un modelo de **Support Vector Machine (SVM)** y se evalúa su desempeño. Se comparan:
- El desempeño del modelo original vs. los modelos ajustados con las características seleccionadas.
- El impacto de la reducción de dimensiones en la precisión del modelo.
- La métrica de desempeño utilizada y su justificación.

### **Task 2.3 - Perceptrón**
Se implementa un **perceptrón de una sola capa** para clasificar el dataset de Iris con las siguientes especificaciones:
- Uso de las características **sepal length** y **sepal width**.
- Implementación de los métodos `fit` y `predict`.
- Visualización de la **frontera de decisión**.
- Evaluación del desempeño del modelo utilizando una métrica adecuada y justificación de su elección.

### **Estructura del Proyecto**
El laboratorio fue desarrollado en un **Jupyter Notebook**, donde se incluyen:
- Implementaciones en Python para cada una de las tareas prácticas.
- Gráficos y análisis de resultados.
- Comparaciones de rendimiento entre diferentes métodos.
- Respuestas detalladas a las preguntas teóricas.

### **Requerimientos**
Para ejecutar este laboratorio, se recomienda contar con:
- Python 3.x
- Librerías necesarias: `numpy`, `matplotlib`, `sklearn`, `pandas`
- Jupyter Notebook

### **Conclusiones**
Este laboratorio permite comprender en profundidad técnicas esenciales en Inteligencia Artificial y Machine Learning, aplicando métodos de optimización, selección de características y redes neuronales simples. Se han comparado diferentes enfoques y se han extraído conclusiones sobre su desempeño y aplicabilidad en distintos escenarios.

