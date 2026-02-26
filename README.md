# Bank-Customer-Churn-Prediction
Predicting bank customer churn using Machine Learning models

Overview:  
Predict whether a bank customer will leave (churn) using machine learning. Helps the bank retain valuable customers.

Dataset:  
- Source: Kaggle  
- Target: Exited (1 = churned, 0 = retained)  
- Key Features: CreditScore, Geography, Gender, Age, Tenure, Balance, NumOfProducts, IsActiveMember, EstimatedSalary  

Preprocessing:  
- Dropped irrelevant columns: CustomerID, Surname  
- Encoded Gender (LabelEncoder) and Geography (One-Hot)  
- Train-test split applied  

Models Used:  
- Logistic Regression  
- Random Forest
- SVM  
- XGBoost  

Evaluation:  
- Accuracy, Confusion Matrix, ROC-AUC  
- Best Model: XGBoost (Accuracy: 0.90, AUC: 0.93)  

Notes:  
- Ensemble methods performed best  
- Features like Balance and IsActiveMember are most predictive  

Links:  
- Kaggle Notebook: https://www.kaggle.com/code/dildoratoxtasinova/bank-customer-churn-prediction-amaliyot

Author: Dildora / Kaggle Username : dildoratoxtasinova
