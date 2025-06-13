# Tarea 2 - Aprendizaje Profundo

Este repositorio contiene la solución desarrollada para la **Tarea 2** del curso Redes Neuronales Profundas, organizada en dos secciones principales, cada una implementada en su respectivo archivo Jupyter Notebook (`.ipynb`).

## Contenido del Repositorio

### 1. Predicción de Radiación Solar con RNNs

- **Objetivo**: Predecir los niveles de radiación solar para las próximas 24 horas utilizando datos meteorológicos de una estación.
- **Técnicas utilizadas**:
  - Arquitecturas RNN: **LSTM** y **GRU**
  - Preparación y limpieza de datos secuenciales multivariados
  - Generación de ventanas de tiempo y normalización
  - Ajuste de hiperparámetros y comparación de desempeño
- **Dataset**: `SolarPrediction2.csv`, con mediciones de:
  - Radiación, Temperatura, Presión, Humedad, Dirección y Velocidad del viento
- **Evaluación**: Se evalúa el desempeño predictivo comparando los resultados entre LSTM y GRU.

Archivo: `Tarea 2 - RNP_DL-1-2025.ipynb`

---

### 2. Clasificación Jerárquica de Imágenes de Animales

- **Objetivo**: Desarrollar un modelo de clasificación jerárquica para predecir simultáneamente la **clase general** (mamífero, ave, reptil, etc.) y la **especie específica** (perro, pavo, cocodrilo, etc.) a partir de imágenes.
- **Técnicas utilizadas**:
  - Redes neuronales convolucionales (CNN)
  - Transfer learning con modelos preentrenados (e.g., ResNet50)
  - Uso de arquitecturas con múltiples ramas (B-CNN)
  - Manejo de pérdida ponderada y coherencia jerárquica
- **Evaluación**: Métrica principal: **Macro F1-score**, adecuada para clases desbalanceadas y coherencia jerárquica.

Archivo: `Animal_Classification.ipynb`

---

## Requisitos

- Python 3.8+
- Bibliotecas principales:
  - TensorFlow / Keras
  - NumPy, Pandas, Matplotlib, Scikit-learn
  - PIL (Pillow)
  - Jupyter Notebook
