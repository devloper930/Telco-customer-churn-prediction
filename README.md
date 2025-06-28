# 🔍 TECO Customer Churn Prediction – Subscription-Based Service


![Dashboard](Telco_Customer_Churn%20Dashboard.png)

## 📝 Introduction

Customer churn is a critical challenge for subscription-based businesses, where long-term revenue and growth depend on retaining existing customers. This project aims to **analyze historical customer behavior** and develop a predictive model to **identify at-risk customers** for **TECO**, a simulated telecom and internet service provider.

Leveraging **machine learning**, we provide actionable insights to reduce churn, optimize retention strategies, and improve customer experience through data-driven interventions.

---

## 📦 About the Dataset

The dataset contains **demographic, usage, and interaction data** of TECO's customers. It represents a diverse base of users subscribed to various telecom/internet plans, capturing their service patterns and engagement.

### 📁 Key Features

| Column                     | Description                                                  |
|---------------------------|--------------------------------------------------------------|
| `CustomerID`              | Unique customer identifier                                   |
| `Gender`                  | Male / Female                                                |
| `SeniorCitizen`           | Binary flag (0 = No, 1 = Yes)                                |
| `Partner`                 | Whether the customer has a partner (Yes/No)                  |
| `Dependents`              | Whether the customer has dependents (Yes/No)                 |
| `Tenure`                  | Number of months the customer has been with the company      |
| `PhoneService`            | Whether the customer has phone service (Yes/No)              |
| `MultipleLines`           | Whether they have multiple phone lines                       |
| `InternetService`         | DSL / Fiber optic / No                                       |
| `OnlineSecurity`          | Online security addon (Yes/No/No Internet)                  |
| `OnlineBackup`            | Online backup service status                                 |
| `DeviceProtection`        | Whether the customer has device protection                   |
| `TechSupport`             | Availability of tech support                                 |
| `StreamingTV`             | Access to streaming TV service                               |
| `StreamingMovies`         | Access to streaming movies                                   |
| `Contract`                | Month-to-month / One year / Two year                         |
| `PaperlessBilling`        | Whether billing is paperless                                 |
| `PaymentMethod`           | Payment type (Credit card / Bank / Electronic / Mailed)      |
| `MonthlyCharges`          | Monthly subscription cost                                    |
| `TotalCharges`            | Lifetime charges                                             |
| `Churn`                   | Target variable: whether the customer churned (Yes/No)       |

---

## 🎯 Project Objectives

- 📊 **Understand churn patterns** based on demographics, services, and usage.
- 🧠 **Develop a classification model** to predict customer churn.
- 📌 **Identify key churn drivers** for targeted business strategies.
- 🛠️ Recommend actions to improve **customer retention and satisfaction**.

---

## ⚙️ Methodology

1. **Data Preprocessing**
   - Handle missing values & data types
   - Encode categorical variables
   - Scale numerical features

2. **Exploratory Data Analysis (EDA)**
   - Churn rate distribution
   - Impact of tenure, charges, contract type, and services on churn

3. **Modeling Techniques**
   - Logistic Regression  
   - Decision Trees & Random Forest  
   - Gradient Boosting (XGBoost)  
   - Support Vector Machines  
   - Neural Networks (optional for advanced extension)

4. **Evaluation Metrics**
   - Accuracy, Precision, Recall, F1 Score
   - ROC-AUC Curve
   - Confusion Matrix

---

## 📈 Key Findings & Visualizations

### 1. Churn Distribution  
🧮 Approximately **26%** of customers have churned – a significant business concern.

### 2. Impactful Factors  
- 🚨 **Month-to-Month contracts** show high churn rates.
- 📉 Customers with **short tenure (<12 months)** are more likely to churn.
- ❌ **No online security, tech support, or streaming services** correlate with higher churn.
- 💸 **Higher monthly charges** are associated with increased churn probability.

### 3. Model Performance  
| Model               | Accuracy | Precision | Recall | F1 Score | AUC  |
|--------------------|----------|-----------|--------|----------|------|
| Logistic Regression| 79.4%    | 71.2%     | 64.3%  | 67.6%    | 0.83 |
| Random Forest       | 82.1%    | 75.8%     | 66.5%  | 70.8%    | 0.86 |
| XGBoost             | **83.7%**| **77.3%** | **69.1%**| **73.0%**| **0.88** |

---

## ✅ Recommendations

| Area              | Action Item                                                   |
|-------------------|---------------------------------------------------------------|
| 📄 Contracts       | Promote **long-term plans** with loyalty rewards              |
| 💰 Billing         | Offer **discounts** for high-value monthly customers          |
| 💡 Value Add-ons   | Bundle **Tech Support, Online Security, and Streaming**       |
| 📲 Customer Touch  | Proactively engage with **new and short-tenure customers**    |
| 🧠 ML Deployment   | Integrate model into **CRM system** for real-time churn flagging |

---

## 📂 Folder Structure

