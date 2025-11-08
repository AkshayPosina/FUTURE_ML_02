# 🧠 Customer Churn Prediction System  
### 🚀 Task 2 – Machine Learning Internship (Future Interns)

This research relies on utilizing **XGBoost** to anticipate customer churn, which means locating customers who are likely to stop subscribing to a service.  
The purpose is to provide businesses with an opportunity to enhance customer retention by means of data-driven insights and visual analyses in **Power BI**.

---

## 📂 Project Files

| File Name | Description |
|------------|-------------|
| **Customer_Churn.csv** | Raw dataset consisting of client backgrounds and account particulars. |
| **Churn_prediction.py** | Python program for data preprocessing, XGBoost model training, and evaluation. |
| **Churn_Predictions.csv** | Result of the model indicating the level of churn per customer. |
| **Feature_Importance.csv** | Scores of feature importance taken from the model. |
| **Task-2_Churn_Prediction_Akshay_Posina.pbix** | Power BI report that shows visualizations of insights and results from the model. |
| **Task 2 – Churn Prediction System.txt** | Project's summary and documentation. |

---

## 🧩 Tech Stack Used

- **Python ** – Model Building & Data Processing  
  - Pandas | NumPy | Scikit-Learn | XGBoost | Seaborn | Matplotlib  
- **Power BI 📊** – Dashboard Visualization  
- **Excel / CSV 📁** – Data Preparation & Output Storage  

---

## ⚙️ Workflow Overview

1. **Data Cleaning & Exploration**  
   - Read `Customer_Churn.csv` and processed categorical columns with LabelEncoder.  
   - Applied StandardScaler for scaling numerical features.  

2. **Feature Engineering**  
   - Identified attributes such as CreditScore, Age, Gender, Balance, Tenure, NumOfProducts, IsActiveMember, and EstimatedSalary as relevant choices.  

3. **Model Training**  
   - Developed **XGBoost Classifier** to predict churn.  
   - Divided the dataset into training/testing parts (80 / 20).
