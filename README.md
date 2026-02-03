#  Customer Churn Prediction using Scikit-learn Pipeline

## Objective of the Task
The objective of this project is to build a reusable and production-ready machine learning pipeline to predict customer churn. The focus is on applying best practices in preprocessing, model selection, hyperparameter tuning, and model deployment.

## Methodology / Approach
- Used the Telco Customer Churn dataset for binary classification.
- Performed automated preprocessing using scikit-learn’s Pipeline and ColumnTransformer.
- Applied feature scaling for numerical variables and one-hot encoding for categorical variables.
- Trained and tuned Logistic Regression and Random Forest models using GridSearchCV.
- Selected the best model based on cross-validated F1-score.
- Exported the complete preprocessing and modeling pipeline using joblib for reusability.

## Key Results / Observations
- Logistic Regression achieved the best cross-validated F1-score and was selected as the final model.
- The final model achieved approximately 79% accuracy and a test F1-score of 0.58.
- Results highlight the importance of F1-score for imbalanced classification problems like churn prediction.
- The pipeline-based approach ensures scalability, consistency, and production readiness.
