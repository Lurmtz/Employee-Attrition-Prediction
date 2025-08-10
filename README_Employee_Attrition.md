
# Employee Attrition Prediction – Final Project

This repository contains my final project for the Neoland Data Analytics Bootcamp: a predictive model to estimate the probability of employee turnover, combined with a Power BI dashboard for visualizing results and KPIs.

---

## 🛠 Technologies and Libraries

**Python:** pandas, numpy, matplotlib, seaborn, scikit-learn

**Power BI:** Visualization of KPIs and predictions

---

## 📌 Methodology

**Objective:** Predict the probability of employee attrition.

**Data Cleaning:** Handling missing values, encoding categorical variables, and data normalization.

**EDA:** Analysis of correlations and detection of relevant patterns.

**Modeling:** Tested different machine learning models (Logistic Regression, Random Forest).

**Visualization:** Interactive Power BI dashboard with key metrics and prediction results.

---

## 📊 Key Results

**Best Model:** *Logistic Regression*
- **Accuracy:** 0.71
- **F1-score (macro avg):** 0.67
- **F1-score (weighted avg):** 0.73

**Metrics by class:**

| Class | Precision | Recall | F1-score | Support |
|-------|-----------|--------|----------|---------|
| 0.0   | 0.90      | 0.70   | 0.79     | 3441    |
| 1.0   | 0.43      | 0.74   | 0.55     | 1063    |

**Most influential variables:**
- last_new_job
- experience
- city_development_index

