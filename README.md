# 💼 Customer Churn Prediction (Bank Customers)

This project predicts whether a customer is likely to leave a bank (churn) based on various demographic and account-related features. It uses machine learning techniques to train a classification model and understand feature importance.

## 📊 Dataset

- **Name:** Churn Modelling Dataset  
- **Source:** [Kaggle - Churn Modelling](https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling)
- **File Used:** `Churn_Modelling.csv`

## 🎯 Objective

The goal is to predict which customers are likely to **exit** the bank, based on features like age, balance, credit score, and location.

---

## 🧹 Data Cleaning & Preprocessing

- Removed unnecessary columns: `RowNumber`, `CustomerId`, `Surname`
- Encoded categorical features:
  - `Gender`: Label Encoding
  - `Geography`: One-Hot Encoding
- Handled class imbalance (if any)
- Scaled features (optional step depending on model)

---

## 🤖 Model Used

- **Random Forest Classifier**
- (Optional): Logistic Regression, Decision Tree

---

## 🧪 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

---

## 📈 Feature Importance

Visualized which features most influence the churn prediction using feature importance from Random Forest.

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab

---

## 🚀 How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/churn-prediction.git
    cd churn-prediction
    ```

2. Open the notebook in Google Colab or Jupyter:
    - `Churn_Prediction.ipynb`

3. Upload the dataset:
    - `Churn_Modelling.csv`

4. Run all cells

---

## 📌 Project Structure

