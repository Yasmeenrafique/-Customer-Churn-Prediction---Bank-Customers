# 🏦 Customer Churn Prediction - Bank Customers

## 📌 Objective

The goal of this project is to build a machine learning model to **predict whether a customer will leave (churn)** from a bank, using their account and demographic information. Early prediction of customer churn allows banks to take strategic actions to retain customers and improve revenue.

---

## 📈 Approach

1. **Dataset Used**:  
   - `Churn_Modelling.csv` containing 10,000 bank customer records.
   - Target column: `Exited` (1 = Churned, 0 = Retained)

2. **Steps Followed**:
   - **Data Cleaning**:
     - Dropped irrelevant columns like `RowNumber`, `CustomerId`, and `Surname`.
     - Encoded `Gender` using `LabelEncoder`.
     - One-hot encoded `Geography` column.
   - **Data Preparation**:
     - Split dataset into features (`X`) and target (`y`).
     - Divided data into training (80%) and testing (20%) sets.
   - **Model Building**:
     - Used `RandomForestClassifier` for training.
     - Made predictions on test data.
   - **Model Evaluation**:
     - Used metrics like Accuracy, Confusion Matrix, and Classification Report.
   - **Feature Importance**:
     - Analyzed key features affecting customer churn.

---

## ✅ Results and Insights

- **Model Accuracy**: ~86%
- **Top Influential Features**:
  - `Age`, `Balance`, and `Number of Products` were the most important factors.
- **Observation**:
  - Customers aged 40+ with high balances and fewer bank products were more likely to churn.

---

## 📊 Visuals

- Bar chart showing feature importance.
- churn by age group
- churn by gender
---

## 🤝 Contact

*Created by Yasmeen Rafique 

---

