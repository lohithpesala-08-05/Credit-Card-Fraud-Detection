# Credit Card Fraud Detection

## Project Overview
This project aims to detect fraudulent credit card transactions using Machine Learning techniques.

## Features
- Data Preprocessing
- SMOTE for Class Imbalance Handling
- Logistic Regression
- Classification Report
- Confusion Matrix
- ROC Curve & AUC Score

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Imbalanced-Learn

## Workflow
1. Data Collection
2. Data Cleaning
3. Train-Test Split
4. SMOTE Oversampling
5. Feature Scaling
6. Model Training
7. Model Evaluation

## Results

| Metric        | Score  |
| ------------- | ------ |
| Test Accuracy | 98.95% |
| Precision     | 99.43% |
| Recall        | 98.47% |
| F1 Score      | 98.95% |
| ROC-AUC Score | 99.85% |

### Performance Summary

The Logistic Regression model achieved excellent performance on the test dataset. By applying SMOTE to address class imbalance, the model was able to effectively detect fraudulent transactions while maintaining high precision and recall. The ROC-AUC score of 99.85% indicates a strong ability to distinguish between fraudulent and legitimate transactions.


## Future Improvements
- Random Forest
- XGBoost
- Hyperparameter Tuning
- Model Deployment

## Dataset

This project uses the Credit Card Fraud Detection dataset available on Kaggle.

Dataset Link:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
