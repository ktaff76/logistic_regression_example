# 🔍 Employee Attrition Prediction using Logistic Regression

## 📌 Overview
This project applies **Logistic Regression** to predict employee attrition using HR dataset features. The goal is to build a classification model, evaluate its performance, and interpret coefficients for business insights.

---

## 🛠️ Tech Stack
- Python
- pandas, numpy
- scikit-learn
- statsmodels
- mord
- dmba
- seaborn, matplotlib

---

## ✅ Dataset
- Source: WA_Fn-UseC_-HR-Employee-Attrition_logisticregression.csv
- Target Variable: Attrition (Yes/No)

---

## 🔍 Model Performance
### Confusion Matrix
![Confusion Matrix](confusion_matrix.png)

### Classification Report
![Classification Report](classification_report.png)

**Accuracy:** 86.7%

Observation: Model predicts all cases as "No Attrition," leading to zero precision/recall for "Yes." Indicates class imbalance.

---

## 📈 Insights
- Negative coefficients for Age and TotalWorkingYears suggest lower attrition likelihood for older employees.
- Positive coefficient for DistanceFromHome indicates higher attrition risk for employees living farther away.

---

## 🚀 How to Run
```bash
git clone https://github.com/yourusername/employee-attrition-logistic-regression.git
pip install -r requirements.txt
jupyter notebook logistic_regression_attrition.ipynb
```
