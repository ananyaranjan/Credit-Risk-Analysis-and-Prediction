# Credit-Risk-Analysis-and-Prediction
Credit risk prediction using Logistic Regression, Decision Tree, Random Forest, and XGBoost.

## Overview
This project focuses on building a machine learning-based system to predict loan default risk using borrower financial and demographic data. The goal is to classify whether a loan applicant is likely to default or not based on historical patterns in the dataset.

---

## Problem Statement
Loan default prediction is a binary classification problem where the objective is to predict:

- 0 → No Default  
- 1 → Default  

Accurate prediction helps financial institutions reduce credit risk and make informed lending decisions.

---

## Dataset Description
The dataset contains 11 independent features and 1 target variable:

### Features:
- person_age  
- person_income  
- person_home_ownership  
- person_emp_length  
- loan_intent  
- loan_grade  
- loan_amnt  
- loan_int_rate  
- loan_percent_income  
- cb_person_default_on_file  
- cb_person_cred_hist_length  

### Target:
- loan_status (0 = non-default, 1 = default)

---

## Machine Learning Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost  

---

## Data Preprocessing
- Handling missing values  
- Treating unrealistic values and outliers  
- Encoding categorical variables  
- Feature scaling using standardization  
- Train-test split for evaluation  

---

## Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  

---

## Results Summary

| Model                | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|---------------------|----------|-----------|--------|----------|---------|
| Logistic Regression | 0.8533   | 0.7346    | 0.5123 | 0.6036   | 0.8597  |
| Decision Tree       | 0.9102   | 0.9553    | 0.6172 | 0.7499   | 0.8836  |
| Random Forest       | 0.9337   | 0.9759    | 0.7136 | 0.8244   | 0.9306  |
| XGBoost             | 0.9343   | 0.9853    | 0.7094 | 0.8249   | 0.9438  |

---

## Key Insight
Ensemble models (Random Forest and XGBoost) perform significantly better than linear models due to their ability to capture complex non-linear relationships in financial data.

---

## Best Model
**XGBoost** achieved the highest ROC-AUC and overall balanced performance, making it the most effective model for credit risk prediction.

---

## Conclusion
This project demonstrates how machine learning can be effectively applied to credit risk assessment, helping financial institutions make more informed and data-driven lending decisions.
