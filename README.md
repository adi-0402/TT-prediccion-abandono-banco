# Predicción de Abandono de Clientes
![GitHub](https://img.shields.io/badge/GitHub-Repository-lightgrey)
![Estado](https://img.shields.io/badge/Estado-Terminado-brightgreen)

## 📖 Descripción del Proyecto
El objetivo de este proyecto fue desarrollar un modelo de machine learning para predecir el abandono de clientes en un banco. La empresa quiere identificar patrones que indiquen si un cliente dejará el banco, para poder implementar medidas preventivas. Este proyecto se realizo con Tripleten.

## 💻 Funcionalidades
- `Limpieza y Preparación de Datos`: Preprocesamiento de los datos de comportamiento de clientes para su uso en el modelo.
- `Modelos de Clasificación`: Implementación de varios modelos de machine learning para predecir el abandono de clientes.
- `Métricas de Evaluación`: Evaluación del modelo utilizando las métricas **F1** y **ROC-AUC**.

## 🛠 Tecnologías Utilizadas
- Python
- Pandas
- Scikit-learn

## ✨ Conclusiones
- `Segmentación de Datos`: Los datos fueron correctamente divididos en conjuntos de entrenamiento, validación y prueba.
- `Evaluación de Modelos`: Se implementaron y compararon varios modelos de clasificación, destacando el **RandomForestClassifier** con los siguientes hiperparámetros: n_estimators: 200 y max_depth: 10.
- `Desempeño del Modelo`: El modelo final alcanzó un valor **F1 de 0.616** y una métrica **ROC-AUC de 0.854**, superando el umbral mínimo requerido de F1 (0.59).
