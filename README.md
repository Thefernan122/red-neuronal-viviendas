# 🧠 Predicción de Precios de Viviendas con Redes Neuronales

Este proyecto tiene como objetivo implementar modelos de machine learning, específicamente regresión lineal y redes neuronales, para predecir el precio medio de viviendas en California usando Python y TensorFlow/Keras. El desarrollo fue realizado en Google Colab y gestionado con control de versiones en GitHub.

---

## 📌 Objetivos

- Cargar un dataset real de viviendas.
- Aplicar regresión lineal simple con una variable predictora.
- Desarrollar una red neuronal con múltiples variables.
- Visualizar y comparar los resultados de ambos modelos.
- Utilizar estructuras básicas de programación (condicionales, bucles, listas).
- Controlar versiones del proyecto con GitHub.

---

## 📁 Dataset Utilizado

Se utilizó el dataset **California Housing** disponible en `sklearn.datasets`, que contiene variables como:

- Ingreso medio (`MedInc`)
- Edad promedio de las casas (`HouseAge`)
- Habitaciones promedio (`AveRooms`)
- Habitaciones por dormitorio (`AveBedrms`)
- Población (`Population`)
- Ocupantes promedio (`AveOccup`)
- Latitud y longitud (`Latitude`, `Longitude`)

---

## 🛠️ Tecnologías

- Python 3
- Google Colab
- Scikit-learn
- TensorFlow / Keras
- Pandas, NumPy, Matplotlib
- Git y GitHub

---

## 📈 Resultados

### Regresión Lineal Simple
- Variable usada: `AveRooms` (habitaciones promedio).
- Resultado visual: dispersión de datos con tendencia lineal limitada.

### Red Neuronal
- Modelo entrenado con todas las variables del dataset.
- Se obtuvo un **Error Absoluto Medio (MAE)** de aproximadamente `0.34` (equivale a $34,000).
- Mejor ajuste visual entre valores reales y predichos.

---

## 📊 Resultados Visuales

### Regresión Lineal:
![Gráfico Lineal](https://github.com/user-attachments/assets/d45462dd-e159-4428-ad41-c5fde3343294)


### Red Neuronal:
![Gráfico Red Neuronal](https://github.com/user-attachments/assets/13b8503b-c00b-4ac8-94dc-776e04944349)
 

---

## 💡 Conclusión Personal

A lo largo de este proyecto aprendí a aplicar conceptos fundamentales de machine learning, como la regresión lineal y las redes neuronales, en un caso práctico de predicción de precios de viviendas.

Al comparar los resultados, noté que la regresión lineal simple tiene limitaciones cuando se usa solo una variable, ya que no capta toda la complejidad del problema. En cambio, la red neuronal entrenada con múltiples variables ofreció resultados mucho más precisos, lo cual demuestra la ventaja de modelos más complejos para este tipo de tareas.

Además, reforcé mis habilidades en programación con Python, especialmente en el manejo de estructuras de datos, condicionales y bucles. El uso de TensorFlow/Keras resultó ser intuitivo y muy potente para la construcción de modelos. Finalmente, comprendí la importancia de gestionar proyectos con GitHub, ya que facilita la organización, documentación y control de versiones del código.

---
