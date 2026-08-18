# customer-churn-prediction
Customer Churn Prediction using Machine Learning

Project Overview

This project predicts whether a telecom customer is likely to churn using machine learning techniques. The project compares three machine learning models and identifies the best-performing model based on Accuracy, Recall, and ROC-AUC.

Dataset

The project uses the Telco Customer Churn dataset, which contains customer information such as demographics, services, tenure, and churn status.

Machine Learning Models

- Logistic Regression
- Random Forest
- XGBoost

Model Results

| Model | Accuracy | Recall | ROC-AUC |
| --- | --- | --- | --- |
| Logistic Regression | 78.75% | 51.60% | 0.83 |
| Random Forest | 78.92% | 45.84% | 0.84 |
| XGBoost | 79.42% | 52.28% | 0.84 |

Best Model

XGBoost performed the best overall, achieving:

- Accuracy: 79.42%
- Recall: 52.28%
- ROC-AUC: 0.84

Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Google Colab

Project File

The complete implementation is available in the Customer_Churn_Prediction.ipynb notebook included in this repository.
