# AspireNex Task 1
# Credit Card Fraud Detection

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset used is highly imbalanced, with fraudulent transactions accounting for a very small percentage of 0.17%. To address this imbalance, oversampling using the Synthetic Minority Over-sampling Technique (SMOTE) was employed. Various classification models including Logistic Regression (LR), Decision Tree (DT), and Random Forest (RF) were implemented to build and evaluate the detection system.

## Table of Contents
- [Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- [Models](https://colab.research.google.com/github/AnshikaaAgarwal/AspireNex/blob/main/CreditCard_FraudDetection.ipynb#scrollTo=2bgOe_eMX6K_)
- [SMOTE](https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.SMOTE.html)
- [Evaluation](https://colab.research.google.com/github/AnshikaaAgarwal/AspireNex/blob/main/CreditCard_FraudDetection.ipynb#scrollTo=2bgOe_eMX6K_)
- [Results](https://colab.research.google.com/github/AnshikaaAgarwal/AspireNex/blob/main/CreditCard_FraudDetection.ipynb#scrollTo=2bgOe_eMX6K_)


## Dataset
The dataset contains transactions made by credit cards in September 2013 by European cardholders. It is highly imbalanced, with fraudulent transactions representing a small fraction of all transactions.

## Balancing Technique
The imbalanced nature of the dataset was addressed using the Synthetic Minority Over-sampling Technique (SMOTE) to improve model performance on fraudulent transactions.

## Models
The following models were used in this project:

Logistic Regression (LR)
Decision Tree (DT)
Random Forest (RF)

## Evaluation
The models were evaluated using metrics such as accuracy, precision, recall, and F1-score. The evaluation focused on the ability to correctly classify fraudulent transactions while minimizing false positives.

## Results
he performance of each model was compared, and the results were summarized to identify the most effective model for fraud detection.






