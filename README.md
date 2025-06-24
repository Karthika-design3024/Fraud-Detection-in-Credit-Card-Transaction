# 💳 Fraud Detection in Credit Card Transactions

A machine learning project that detects fraudulent credit card transactions using anomaly detection and supervised learning techniques. The project includes a Streamlit-based web app for real-time predictions.

---

## 📌 Project Overview

- Detect fraudulent credit card transactions using the **Credit Card Fraud Detection Dataset** from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud).
- Built an anomaly detection pipeline with:
  - Isolation Forest
  - Local Outlier Factor (LOF)
  - XGBoost Classifier
- Developed a **Streamlit web app** for making real-time fraud predictions based on transaction input values.

---

## 📂 Project Structure
Fraud-Detection-in-Credit-Card-Transactions/ ├── app.py                      # Streamlit app for real-time fraud detection ├── fraud_detection.ipynb       # Jupyter notebook for training and evaluation ├── xgb_model.pkl               # Trained XGBoost model (Pickle format) ├── requirements.txt            # Required Python libraries └── README.md                   # Project description and guide
---

## 🚀 How to Run This Project

1. **Clone the repository**

 git clone https://github.com/your-username/Fraud-Detection-in-Credit-Card-Transactions.git

2. **Install required libraries**

pip install -r requirements.txt

3. **Run the Streamlit app**

streamlit run app.py

4. **Enter transaction details** in the web app to predict whether it’s a fraudulent or legitimate transaction.

---

## 📊 Dataset Source

- [Credit Card Fraud Detection Dataset (Kaggle)](https://www.kaggle.com/mlg-ulb/creditcardfraud)

---

## 📌 Author

**Karthika S**  
[GitHub Profile](https://github.com/Karthika-design3024)

---

## ❤️ Built With

- Python
- Pandas, NumPy, Scikit-learn, XGBoost
- Streamlit
- Jupyter Notebook


---
