
# 🔍 Credit Card Fraud Detection using Deep Learning

## 🧠 Problem Statement
Credit card fraud poses a significant threat to financial institutions and consumers alike. 
This project aims to **detect fraudulent credit card transactions** using deep learning techniques, including unsupervised and supervised methods.

## 🎯 Objective
To explore and implement multiple deep learning models to identify anomalous transactions and evaluate their effectiveness in fraud detection.

## 📊 Techniques Used
- **Autoencoder (Unsupervised Anomaly Detection)**: Learns to reconstruct non-fraudulent transactions and flags deviations.
- **LSTM Autoencoder**: Models sequential dependencies to detect subtle fraud patterns over time.
- **Feedforward Neural Network (FFNN)**: A supervised classification model trained to distinguish between fraudulent and legitimate transactions.

## 📁 Dataset
The dataset is publicly available on Kaggle:  
🔗 [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Transactions:** 284,807
- **Fraud Cases:** 492 (highly imbalanced)
- **Features:** 30 (anonymized + Amount & Time)

## 🧪 Evaluation Metrics
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC

## 🚀 How to Use
1. Download the dataset from the above link and place `creditcard.csv` in the same directory as the notebook.
2. Run the Jupyter notebook to train and evaluate the models.

## 📌 Note
This project demonstrates the strength of combining multiple deep learning approaches for high-stakes anomaly detection tasks.

---

📧 Feel free to reach out for collaboration or suggestions!
