#  Credit Score Classification

A machine learning-based system to predict individuals' credit scores (Poor, Standard, Good) using financial and personal attributes. This project automates creditworthiness assessment, supporting faster and more consistent financial decision-making.

---

##  Problem Statement

Build a robust model to classify credit scores using a dataset with diverse customer attributes like income, loan history, credit usage, and payment behavior.

---

##  Dataset Overview

- 30+ features including:
  - Annual Income
  - Number of Loans
  - Credit History Age
  - Credit Utilization Ratio
  - Payment Behavior
- Target variable: **Credit Score** (`Poor`, `Standard`, `Good`)

---

##  Workflow

1. Data Cleaning (missing values, outliers, type conversion)
2. Feature Engineering & Encoding
3. Handling Imbalanced Classes (Oversampling)
4. Power Transformation for normalization
5. Model Building: **Random Forest**, **XGBoost**, **Logistic Regression**
6. Evaluation using Accuracy, Precision, Recall, F1 Score, and AUC

---

##  Best Model

- **Random Forest Classifier**
- **AUC Score:** 0.98  
- **F1 Score:** High macro-average score on balanced dataset

---


## 📌 Future Improvements

- Deploy as a Streamlit or Flask web app
- Use SHAP/LIME for model explainability
- Incorporate temporal patterns or credit trends
- Add external features like credit bureau scores

---



