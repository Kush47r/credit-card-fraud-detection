# Credit Card Fraud Detection

## Overview
Fraud detection model built on 284,807 real bank transactions 
to identify fraudulent activity on a severely imbalanced dataset.

## Key Results
- Analyzed 284,807 transactions with only 0.17% fraud rate
- Applied SMOTE to balance training data from 394 → 227,451 fraud cases
- Achieved 80.6% fraud recall — catching 79/98 real fraud cases
- Only 0.03% false alarm rate
- V14 identified as top fraud signal (22% feature importance)

## Tools Used
Python, Pandas, Scikit-learn, SMOTE, Random Forest, Matplotlib, Seaborn

## Dataset
Kaggle Credit Card Fraud Detection Dataset
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## How to Run
1. Download dataset from Kaggle link above
2. Place creditcard.csv in data/ folder
3. Run fraud_detection.ipynb top to bottom
