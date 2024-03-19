# Fraud-Detection-Project
Detect Fraudulent applications for a bank account via diverse machine-learning models

Fraudulent applications for a new bank account are major concerns for banks and financial institutions. Fraudsters use various techniques (identity theft, account takeover, phishing) to apply for fake bank accounts and do illegal activities. In this project, we will explore a dataset containing Bank Account Application records and build models to predict fraudulent applications in the bank account opening process.

Here, we will use the Kaggle dataset Bank Account Fraud (BAF) dataset (https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022) which comprises:
1 million instances, out of which 11029 are fraudulent (1.1%);
30 realistic features used in the fraud detection use-case; 
A column of “month”, providing temporal information about the dataset;
Protected attributes, (age group, employment status and % income).

We will start with data cleaning and exploratory data analysis (EDA) to get a better understanding of the data. Secondly, we will perform data processing, feature engineering and modeling where we will build several classification models to identify fraudulent behaviors. We will also address the issue of imbalanced classes by using undersampling, oversampling, and SMOTE. Thirdly, we will evaluate the performance of the models and choose the best one based on various evaluation metrics such as PR-AUC and ROC-AUC, and establish the threshold by carefully balancing the trade-off between precision and recall to achieve the best overall performance. Finally, we will interpret the best model via shap to find the top 10 important features.
