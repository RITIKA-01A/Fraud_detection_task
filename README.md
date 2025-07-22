# 🛡️ Fraud Detection Using Machine Learning

This project involves detecting fraudulent financial transactions using machine learning techniques on a dataset of 6.3 million transactions.

## 📂 Dataset

- 6,362,620 rows × 11 columns
- Features include transaction type, amount, sender/receiver balances, and fraud labels
- Target variable: `isFraud`

## ⚙️ Techniques Used

- Exploratory Data Analysis (EDA)
- One-Hot Encoding for categorical variables
- SMOTE for class imbalance handling
- Feature engineering (e.g., balance error fields)
- Feature selection using Random Forest
- Model training with Random Forest Classifier
- Evaluation using Precision, Recall, F1-Score, and ROC-AUC

## 📊 Model Performance

- **ROC-AUC**: `0.9988`
- **Recall (fraud)**: `95.17%`
- **F1-Score (fraud)**: `0.75`
- Very low false negatives and strong detection performance

## 📌 Highlights

- Only `TRANSFER` and `CASH_OUT` types had fraud
- Fraud patterns include draining balances to zero
- Used SMOTE to handle 0.13% fraud class imbalance

