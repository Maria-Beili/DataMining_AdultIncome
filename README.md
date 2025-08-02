# DataMining_AdultIncome
📊 Binary Classification of Annual Income – Data Mining Project

🔍 Project Overview

This project, developed as part of the Data Mining course at the University of Mannheim, aims to predict whether an individual's annual income exceeds $50,000 based on demographic and occupational data. It leverages advanced preprocessing techniques, feature selection, and multiple machine learning models including Gradient Boosting, Random Forest, SVM, and Naïve Bayes.

The final model achieves a weighted F1-score of 0.84, outperforming 88% of existing models on Kaggle’s benchmark dataset.

🧠 Technologies & Methods

Python, scikit-learn, pandas, matplotlib

Data Cleaning, One-Hot Encoding, Feature Engineering

Model Evaluation: Stratified Sampling, Cross-Validation

Hyperparameter Tuning: Randomized Search

Final Model: Gradient Boosting Classifier

📁 Dataset

Source: 1994 U.S. Census Income Data on Kaggle

Size: 31,947 entries, 12 attributes

Target: Income (>50K vs ≤50K)

📈 Model Results

Gradient Boosting Classifier achieved the best performance.

Evaluation based on weighted F1-score to address class imbalance.

Error analysis and feature importance analysis included.

📦 How to Run

pip install -r requirements.txt
python model_pipeline.py

📜 Authors

Miguel Mendes, João Ferreira, Maria Beili Mena, Paola Tomorri, Klea Hoxha, Sueda Sogutlu

📊 Clasificación Binaria de Ingresos Anuales – Proyecto de Minería de Datos

🔍 Descripción del Proyecto

Este proyecto, desarrollado para la asignatura de Minería de Datos en la Universidad de Mannheim, tiene como objetivo predecir si el ingreso anual de una persona supera los $50,000 a partir de datos demográficos y laborales. Se aplicaron técnicas avanzadas de preprocesamiento, selección de características, y se probaron varios modelos de aprendizaje automático, destacando Gradient Boosting, Random Forest, SVM y Naïve Bayes.

El modelo final alcanzó un F1-score ponderado de 0.84, superando al 88% de los modelos de referencia en Kaggle.

🧠 Tecnologías y Métodos

Python, scikit-learn, pandas, matplotlib

Limpieza de datos, codificación One-Hot, ingeniería de características

Evaluación: muestreo estratificado, validación cruzada

Ajuste de hiperparámetros: Randomized Search

Modelo final: Gradient Boosting Classifier

📁 Conjunto de Datos

Fuente: Datos de ingresos del censo de EE.UU. de 1994 en Kaggle

Tamaño: 31,947 registros, 12 atributos

Variable objetivo: Ingreso (>50K vs ≤50K)

📈 Resultados del Modelo

El modelo Gradient Boosting obtuvo el mejor desempeño.

Evaluación basada en F1-score ponderado para abordar el desbalance de clases.

Incluye análisis de errores y análisis de importancia de características.

📦 Cómo Ejecutar

pip install -r requirements.txt
python model_pipeline.py

📜 Autores

Miguel Mendes, João Ferreira, Maria Beili Mena, Paola Tomorri, Klea Hoxha, Sueda Sogutlu

