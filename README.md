# Hospital Readmission Prediction

## Overview
This project predicts whether a patient will be readmitted to the hospital within 30 days using Logistic Regression with L2 regularization.

## Dataset
The dataset contains patient, hospital admission, and diagnosis information.

## Features Used
- Age
- Gender
- Previous admissions
- Comorbidity count
- Length of stay
- HbA1c
- Creatinine
- Haemoglobin
- Systolic blood pressure
- Diagnosis code
- Diagnosis category

## Methodology
1. Loaded patient, admission, and diagnosis datasets.
2. Performed basic Exploratory Data Analysis (EDA).
3. Selected the primary diagnosis.
4. Merged the datasets using patient and admission IDs.
5. Checked for missing values.
6. Encoded categorical variables using One-Hot Encoding.
7. Split the data into training and testing sets.
8. Applied feature scaling using StandardScaler.
9. Trained Logistic Regression with L2 regularization.
10. Evaluated the model using Accuracy, Precision, Recall, F1-Score, Confusion Matrix and ROC-AUC.

## Model
**Logistic Regression with L2 Regularization**

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC

## Clinical Consideration
False negatives are important in hospital readmission prediction because a patient who is actually at risk of readmission may be missed. This may affect monitoring and follow-up care. False positives may lead to unnecessary monitoring and use of healthcare resources.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Elixir IDE

## Conclusion
The project demonstrates the use of Logistic Regression with L2 regularization for predicting 30-day hospital readmission prediction.
