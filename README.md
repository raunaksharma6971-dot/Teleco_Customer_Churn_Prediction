# Telecom Customer Churn Prediction

## Overview
This project focuses on predicting **customer churn** in the telecommunications industry using historical customer data. Customer churn—when users discontinue a service—is a critical business problem, as retaining existing customers is often more cost-effective than acquiring new ones.

The objective of this analysis is to identify **key factors driving churn** and build predictive models that can help businesses proactively retain high-risk customers.

---

## Customer Churn Dashboard

An interactive dashboard was created to summarize key churn metrics and model insights, enabling quick exploration of high-risk customer segments and churn drivers.

**Dashboard Highlights**
- Overall churn rate overview
- Churn distribution by contract type and tenure
- Monthly charges vs churn patterns
- High-risk customer segments identified by the model

🔗 **View Dashboard:**  

https://lookerstudio.google.com/reporting/03e30ce2-78fd-4d90-b077-9a17d6dda9bd



![Dashboard Overview](Teleco_customer_churn.png)




---

## Objectives
- Explore customer behavior and service usage patterns
- Identify drivers of customer churn
- Build and evaluate predictive machine learning models
- Translate model results into **actionable business insights**
- Demonstrate an end-to-end supervised learning workflow

---

## Dataset
- **Source:** Public Telecom Customer Churn Dataset
- **Records:** Individual customer-level observations
- **Target Variable:** `Churn` (Yes / No)
- **Key Features:**
  - Demographics (gender, senior citizen status)
  - Account information (tenure, contract type, payment method)
  - Service usage (internet service, streaming, phone services)
  - Billing information (monthly charges, total charges)

---

## Tech Stack
- **Python**
- **Pandas & NumPy** – data manipulation
- **Matplotlib / Seaborn** – data visualization
- **Scikit-learn** – machine learning models
- **Jupyter Notebook** – analysis and experimentation

---

## Methodology

### 1. Data Preprocessing
- Handled missing and inconsistent values
- Encoded categorical variables
- Scaled numerical features where required
- Defined churn as a binary classification problem

### 2. Exploratory Data Analysis (EDA)
- Analyzed churn distribution across customer segments
- Examined relationships between churn and:
  - Contract type
  - Tenure
  - Monthly charges
  - Internet and add-on services

### 3. Feature Engineering
- Transformed tenure and billing variables
- Grouped service usage indicators
- Prepared final feature set for modeling

### 4. Modeling
Built and evaluated multiple classification models, including:
- Logistic Regression
- Tree-based models (Decision Tree / Random Forest)

### 5. Model Evaluation
Models were evaluated using:
- Accuracy
- Precision & Recall
- ROC–AUC
- Confusion Matrix

---

## Key Insights
- Customers on **month-to-month contracts** are significantly more likely to churn
- **Shorter tenure** strongly correlates with higher churn probability
- Higher **monthly charges** increase churn risk
- Certain service combinations (e.g., lack of add-ons) are associated with attrition

---

## Business Applications
- **Customer retention strategies:** Identify high-risk customers for targeted offers
- **Pricing optimization:** Adjust plans for price-sensitive users
- **Contract strategy:** Encourage longer-term contracts to reduce churn
- **Customer experience improvements:** Address service gaps linked to churn

---

## Key Skills Demonstrated
- Supervised machine learning (classification)
- Feature engineering and preprocessing
- Model evaluation and interpretation
- Business-driven analytics
- Translating predictive results into strategic insights

---

## Author
Raunak Sharma  
MS in Business Analytics
