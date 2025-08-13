# 📞 Churn Prediction for ConnectSphere Telecom

## 📌 Project Overview
ConnectSphere Telecom, a regional telecom provider, aims to **reduce customer churn** by predicting which customers are likely to leave.  
This project builds an **Artificial Neural Network (ANN)** model to classify customers into:
- **Churn (Yes)** – Likely to leave
- **No Churn (No)** – Likely to stay

By identifying at-risk customers early, the company can implement **retention strategies** to improve customer loyalty.

---

## 🎯 Objectives
- Develop a **binary classification model** using ANN.
- Use customer usage data such as:
  - Call duration
  - Data usage
  - Contract length
  - Payment method, etc.
- Evaluate model performance with **Accuracy** and **F1-score**.
- Generate a list of customers likely to churn.

---

## 📂 Dataset
- **Source:** Telco Customer Churn dataset  
- **File Name:** `Telco-Customer-Churn.csv`  
- **Target Variable:** `Churn` (Yes/No)  
- **Size:** ~7043 rows × 21 columns  
- **Features:**  
  - Customer ID
  - Gender
  - SeniorCitizen
  - Partner
  - Dependents
  - Tenure
  - PhoneService
  - InternetService
  - Contract
  - PaymentMethod
  - MonthlyCharges
  - TotalCharges
  - Churn

---

## 🛠 Tech Stack
- **Language:** Python
- **Libraries:**
  - Pandas (Data preprocessing)
  - NumPy (Numerical operations)
  - Matplotlib / Seaborn (Data visualization)
  - Scikit-learn (Model evaluation, preprocessing)
  - TensorFlow / Keras (Building ANN model)

---

## 📊 Workflow
1. **Data Loading** – Load dataset and inspect data.
2. **Data Cleaning** – Handle missing values, convert datatypes.
3. **Encoding** – Convert categorical variables into numerical form.
4. **Feature Scaling** – Standardize features.
5. **Model Building** – Create ANN with Keras.
6. **Model Training** – Train model on training dataset.
7. **Evaluation** – Use Accuracy and F1-score to assess performance.
8. **Prediction** – Predict churn for unseen data.

---

## 📈 Model Performance
- **Accuracy:** ~85% (varies depending on hyperparameters)
- **F1-score:** ~0.82 (for churn class)

---


