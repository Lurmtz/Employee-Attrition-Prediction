# Predicción de Fuga de Talento – Proyecto Final

Este repositorio contiene mi proyecto final del Bootcamp de Data Analytics de Neoland: un modelo predictivo para estimar la probabilidad de rotación de empleados, junto con un dashboard en Power BI para la visualización de resultados y KPIs.

---

## 🛠 Tecnologías y Librerías

**Python:** pandas, numpy, matplotlib, seaborn, scikit-learn

**Power BI:** Visualización de KPIs y predicciones

---

## 📌 Metodología

**Objetivo:** Predecir la probabilidad de fuga de empleados.

**Limpieza de datos:** Tratamiento de valores nulos, codificación de variables categóricas y normalización de datos.

**EDA:** Análisis de correlaciones y detección de patrones relevantes.

**Modelado:** Prueba de diferentes modelos de Machine Learning (Logistic Regression, Random Forest).

**Visualización:** Dashboard interactivo en Power BI con métricas clave y resultados de predicciones.

---

## 📊 Resultados Clave

**Mejor modelo:** *Logistic Regression*
- **Accuracy:** 0,71
- **F1-score (macro avg):** 0,67
- **F1-score (weighted avg):** 0,73

**Métricas por clase:**

| Clase | Precisión | Recall | F1-score | Soporte |
|-------|-----------|--------|----------|---------|
| 0.0   | 0.90      | 0.70   | 0.79     | 3441    |
| 1.0   | 0.43      | 0.74   | 0.55     | 1063    |

**Variables más influyentes:**
- last_new_job
- experience
- city_development_index
