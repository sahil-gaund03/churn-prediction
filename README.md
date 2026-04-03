# churn-prediction
# 📊 Customer Churn Prediction

## 🚀 Project Overview
This project focuses on predicting customer churn using machine learning techniques. The goal is to identify customers who are likely to leave a service based on their demographic and usage data.

---

## 📁 Dataset
The dataset contains 1000 customer records with the following features:
- Age
- Gender
- Tenure
- Monthly Charges
- Contract Type
- Internet Service
- Tech Support
- Total Charges
- Churn (Target Variable)

---

## 🔍 Key Steps Performed

### 1. Data Preprocessing
- Handled missing values in `InternetService`
- Checked for duplicates
- Converted categorical variables into numerical format

### 2. Exploratory Data Analysis (EDA)
- Churn distribution visualization
- Correlation analysis
- Grouping insights:
  - Customers with higher monthly charges churn more
  - Customers with lower tenure are more likely to churn

### 3. Feature Engineering
- Selected important features:
  - Age
  - Gender
  - Tenure
  - Monthly Charges
- Encoded categorical data

### 4. Model Building
Trained multiple machine learning models:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

### 5. Model Optimization
- Used GridSearchCV for hyperparameter tuning

### 6. Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 📈 Best Model Performance
- Logistic Regression Accuracy: **85%**
- SVM Accuracy: **95%**
- KNN Accuracy: **94%**

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Streamlit

---

## 💾 Model Deployment
- Saved model using `joblib`
- Built a simple UI using Streamlit for predictions
https://churnprediction-app0310.streamlit.app/
---

## 📌 How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
