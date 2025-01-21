---

# Predicción de Abandono de Clientes en Beta Bank

---

## 🔖 Descripción del Proyecto
Este proyecto se centra en desarrollar un modelo predictivo para identificar clientes de Beta Bank que podrían abandonar el servicio. Utilizando datos financieros y demográficos, el modelo ayuda al banco a implementar estrategias proactivas para retener a sus clientes y reducir la pérdida de ingresos. Este Proyecto se realizo con TripleTen.

---

## 💻 Funcionalidades
- **Preprocesamiento de Datos:** Manejo de valores nulos, eliminación de columnas irrelevantes y creación de variables dummys para categorías.
- **Modelado Predictivo:**
  - Implementación de modelos de regresión logística y Random Forest.
  - Ajuste de hiperparámetros para mejorar el rendimiento del modelo.
- **Manejo de Desbalanceo:**
  - Uso de `class_weight='balanced'` y sobremuestreo para equilibrar las clases.
- **Evaluación del Modelo:** Cálculo de métricas como F1-score, ROC-AUC y accuracy.

---

## 🛠️ Tecnologías Utilizadas
- Python
- Pandas
- NumPy
- Scikit-learn 
- Matplotlib 
- Seaborn

---

## 🔢 Resultados
- **Mejor Modelo:** Random Forest Classifier
  - Hiperparámetros: `n_estimators=200`, `max_depth=10`, `class_weight='balanced'`.
  - **Métricas:** F1-score: **0.616**, ROC-AUC: **0.854**.
- Los resultados superaron el umbral de F1 requerido (0.59), lo que valida la capacidad del modelo para predecir el abandono de clientes.

---

## ✨ Conclusiones
- **Impacto del Proyecto:**
  Este modelo permite a Beta Bank identificar clientes en riesgo de abandono con alta precisión, optimizando los esfuerzos de retención.
- **Elección del Modelo:**
  El Random Forest con ajuste de hiperparámetros y manejo de desbalanceo demostró ser el más efectivo para este caso de uso.
- **Estrategia de Retención:**
  Los resultados obtenidos proporcionan una base sólida para que el banco implemente estrategias personalizadas y proactivas que reduzcan la pérdida de clientes.

---

