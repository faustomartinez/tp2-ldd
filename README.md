# Clasificación y Clustering de Jugadores de Fútbol  
# Classification and Clustering of Football Players

Este proyecto fue desarrollado como segundo trabajo práctico de la materia **Laboratorio de Datos** (Licenciatura en Ciencias de Datos, UBA). Aplica técnicas de **clustering no supervisado** y **clasificación supervisada** sobre estadísticas de jugadores de fútbol de la temporada 2020-2021.  
This project was developed as the second assignment for the **Data Lab** course (Data Science BSc, UBA). It applies **unsupervised clustering** and **supervised classification** techniques to football player statistics from the 2020–2021 season.

## 👨‍💻 Integrantes / Team Members

- Fausto Martínez  
- Santiago Oviedo

---

## 📂 Estructura del Proyecto / Project Structure

- `tp2.ipynb`: Notebook principal con preprocesamiento, clustering y clasificación.  
  Main notebook with preprocessing, clustering and classification.
- `imagenes/`: Visualizaciones generadas durante el análisis.  
  Visualizations generated during the analysis.
- `datos/`: Archivos CSV utilizados (no incluidos).  
  CSV files used (not included for size/privacy reasons).

---

## 🎯 Objetivos / Objectives

- Agrupar jugadores con características similares utilizando clustering.  
  Group similar players using unsupervised clustering techniques.
- Predecir la posición de los jugadores (arquero o no) mediante modelos de clasificación.  
  Predict player positions (goalkeeper or not) using classification models.

---

## 🔍 Metodología / Methodology

### 1. Preprocesamiento / Preprocessing
- Filtrado por minutos jugados y limpieza de datos faltantes.  
  Filtering by minutes played and handling missing values.
- Selección de variables numéricas.  
  Selection of numerical features.

### 2. Clustering
- Escalamiento y reducción de dimensión (PCA).  
  Feature scaling and dimensionality reduction (PCA).
- Visualización de jugadores y agrupamiento con:  
  Player visualization and clustering with:
  - **K-Means**
  - **DBSCAN**

### 3. Clasificación / Classification
- Clasificación binaria (arquero vs jugador de campo).  
  Binary classification (goalkeeper vs field player).
- Modelos utilizados:  
  Models used:
  - **K-Nearest Neighbors**
  - **Decision Tree**
  - **Random Forest**
- Métricas: accuracy, F1-score, matriz de confusión.  
  Metrics: accuracy, F1-score, confusion matrix.

---

## 🧰 Herramientas / Tools

- Python 3.x  
- Pandas  
- Numpy  
- Scikit-learn  
- Matplotlib / Seaborn

Instalación de dependencias / Install dependencies:
```bash
pip install -r requirements.txt

