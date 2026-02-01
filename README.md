# Customer Churn Prediction

## Project Overview
This project aims to predict customer churn using machine learning models.
Churn prediction helps businesses identify customers who are likely to leave and take preventive actions.

## Dataset
The dataset contains customer information such as demographics, services used, and account details.
The target variable is **Churn**:
- 0 → Customer did not churn
- 1 → Customer churned

## Data Preprocessing
- Handled missing values
- Encoded categorical variables using One-Hot Encoding
- Feature scaling
- Handled class imbalance using SMOTE

## Models Used
- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

## Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- classification Report

### Random Forest Results
- Accuracy: 0.77
- Recall (Churn class): 0.62


## Model Comparison
While Random Forest achieved good overall accuracy,XGBoost performed better in identifying churn customers, which is crucial from a business perspective.

## Final Model Selection
XGBOOST Boosting algorithm was selected as the final model due to its better balance between precision and recall for churn prediction.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn

## Conclusion
The project successfully demonstrates how machine learning models can be used to predict customer churn and support data-driven decision-making.
