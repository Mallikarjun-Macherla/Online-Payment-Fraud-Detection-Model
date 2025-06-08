
# 🛡️ Online Payment Fraud Detection

This project focuses on detecting fraudulent transactions in online payments using machine learning techniques. It aims to classify whether a given transaction is fraudulent or legitimate, helping fintech companies and banks improve security and trust.

## 📊 Dataset

- The dataset used includes anonymized transaction features.
- Common features may include: `step`, `amount`, `type`, `oldbalanceOrg`, `newbalanceOrig`, `oldbalanceDest`, `newbalanceDest`, etc.
- The target variable is `isFraud`, where `1` indicates a fraudulent transaction.

> You can use the dataset from [Kaggle - Fraud Detection]([https://www.kaggle.com/datasets/ealaxi/paysim1](https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset)) or any similar dataset.

## 🧠 Model Used
- Random Forest
- Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, ROC-AUC

## 🔍 Features of the Project

- Data Cleaning and Exploration
- Class Imbalance Handling (SMOTE, Undersampling)
- Feature Engineering and Selection
- Model Comparison and Hyperparameter Tuning
- Fraud Probability Analysis

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Mallikarjun-Macherla/online-payment-fraud-detection.git
   cd online-payment-fraud-detection
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   Open `Online_Payment_Fraud_Detection.ipynb` using Jupyter Notebook or Colab.

## 📌 Future Improvements
- Can be improved by training on different datasets
- Deploy as a web app using Streamlit or Flask
- Real-time fraud detection with streaming data
