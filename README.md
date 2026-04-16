💳 **Credit Card Fraud Detection Using Machine Learning**

📌 **Project Overview**<br>
This project builds an end-to-end Machine Learning pipeline to detect fraudulent credit card transactions in the finance and banking domain. The goal is to classify transactions as Fraud (1) or Legitimate (0) using transactional and behavioral features.

🎯 **Objectives**
Perform structured data cleaning and preprocessing
Conduct Exploratory Data Analysis (EDA)
Handle class imbalance effectively
Train and compare multiple ML models
Evaluate models using business-relevant metrics

📊 **Dataset Information**
500,000 credit card transactions
15 predictor features + 1 target variable (Fraud_Flag)
Mix of numeric and categorical features
Highly imbalanced dataset

🛠️ **Data Preprocessing Steps**
Missing value validation
Duplicate removal
Outlier removal (IQR Method)
Skewness correction (Yeo-Johnson Transformation)
Label encoding for categorical variables
Feature scaling using StandardScaler
Class imbalance handling using undersampling

🤖 **Models Implemented**
Logistic Regression
Naive Bayes
Support Vector Machine (SVM)
Random Forest
AdaBoost
XGBoost
K-Nearest Neighbors (KNN)
Voting Classifier (Ensemble)
Stacking Classifier

📈 **Evaluation Metrics**
Models were compared using:
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
ROC-AUC

Tree-based ensemble models (especially Random Forest and Voting Classifier) delivered the best fraud detection performance by effectively balancing precision and recall.

🚀 **Tech Stack**
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
XGBoost

📌 **Conclusion**
This project demonstrates how proper data preprocessing, imbalance handling, and ensemble modeling significantly improve fraud detection performance. It provides a scalable and reproducible framework for real-world financial risk analytics.
