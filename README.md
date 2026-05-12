# Credit Card Fraud Detection 🚀

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques.

The dataset is highly imbalanced, making fraud detection a challenging real-world problem.

---

## ⚙️ Approach

- Data Cleaning & Preprocessing
- Feature Engineering:
  - Extracted **transaction hour**
  - Computed **customer age**
- Handled class imbalance using **SMOTE**
- Trained a **Logistic Regression model**

---

## 📊 Results

- Initial Model:
  - Failed to detect fraud (0% recall)

- After applying SMOTE:
  - ✅ Fraud Recall: **76%**
  - ✅ Improved detection of fraudulent transactions

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn

---

## 📂 Dataset

Dataset is not included due to size limitations.

You can download it from:
👉 https://www.kaggle.com/datasets/

---

## 🚀 Future Improvements

- Try advanced models (Random Forest, XGBoost)
- Improve precision to reduce false alarms
- Deploy using Streamlit

---

## 📌 Author

**Rani Nunna**