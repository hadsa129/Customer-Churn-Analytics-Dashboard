# Customer-Churn-Analytics-Dashboard

## Project Overview
This project focuses on **analyzing customer churn in a retail bank** to identify key factors contributing to customer attrition and propose actionable insights for retention.  
Using **Tableau**, I developed a series of **interactive dashboards** and a **dynamic data story** to visualize customer behavior, satisfaction, and engagement.

The dataset contains customer demographic and behavioral information such as credit score, age, tenure, complaints, satisfaction score, and more.

---

## Goal
The main goal of this project is to build **analytical visualizations** and **interactive dashboards** that help understand:
- Where and why the bank loses its customers.
- The key drivers behind customer churn.
- Strategies to improve customer retention and satisfaction.

---

## Dataset Description

| Column Name | Description |
|--------------|-------------|
| RowNumber | Row index |
| CustomerId | Unique identifier for each customer |
| Surname | Customer’s surname |
| CreditScore | Credit rating of the customer |
| Geography | Country of residence |
| Gender | Male/Female |
| Age | Age of the customer |
| Tenure | Number of years as a bank customer |
| Balance | Account balance |
| NumOfProducts | Number of products held by the customer |
| HasCrCard | Whether the customer has a credit card (Yes/No) |
| IsActiveMember | Whether the customer is an active member (Yes/No) |
| EstimatedSalary | Estimated annual salary |
| Exited | Customer churn status (1 = Left, 0 = Retained) |
| Complain | Whether the customer made a complaint (Yes/No) |
| Satisfaction Score | Satisfaction level (1–5) |
| Card Type | Type of card held (Silver, Gold, Platinum, etc.) |
| Point Earned | Loyalty or reward points earned |

---

## Process

### 1️⃣ Data Cleaning
- Connected the dataset to Tableau and checked for missing or inconsistent data.  
- Converted binary fields (`Complain`, `IsActiveMember`) from **0/1 to Yes/No** for better readability.  
- Ensured that all data types were correct and consistent across the dataset.

### 2️⃣ Data Processing
- Verified total and unique customer count.  
- Calculated:
  - Total number of churners.
  - Churn rate (% of customers who left the bank).
  - Key descriptive statistics (mean, median, variance) for major numeric features.

### 3️⃣ Data Visualization
To gain deeper insights, I created various visualizations using:
- **Dual-axis charts** to compare churn rate with age and tenure.  
- **Scatter plots** to analyze satisfaction and complaint behavior.  
- **Heat maps** to identify trends and correlations.  
- **Geographical maps** to observe churn by region.  

All visualizations were combined into **three interactive dashboards** and a **dynamic Tableau story**.

---

## 📈 Key Performance Indicators (KPIs)

| KPI | Description |
|------|-------------|
| 🧍 Number of Customers | Total active customers in the dataset |
| 💰 Average Balance | Mean account balance |
| 👶 Average Age | Mean customer age |
| 💵 Average Estimated Salary | Mean estimated salary |
| ⭐ Average Points Earned | Average loyalty/reward points |
| 🧾 Average Credit Score | Mean credit rating |
| 🚪 Number of Churners | Count of customers who exited |
| 📉 Churn Rate | Percentage of customers who left the bank |

---

## 📊 Dashboards & Insights

### 1️⃣ Customer Overview Dashboard
- KPIs and customer metrics overview.  
- **Churn by Geography** – visualizing churn distribution across countries.  
- **Customer Demographics** – analyzing churn by gender and age group.
- **Credit Score by Churn Status** – correlation between risk level and churn.
  
### 2️⃣ Customer Behavior Dashboard
- **Churn by Active Member & Complaint** – analyzing how engagement affects churn.  
- **Satisfaction Score by Churn Status** – showing the impact of satisfaction on retention.  
- **Complaint Behavior** – understanding the link between complaints and churn.
- **Churn vs Tenure** – exploring how long-term relationships influence churn.  

### 4️⃣ Dynamic Story
A step-by-step Tableau story presenting:
- Churn overview  
- Root-cause analysis  
- Strategic recommendations

---

## 💡 Insights & Recommendations
- Customers with **low satisfaction** and **high complaint rates** are more likely to churn.  
- **Inactive members** have significantly higher churn rates.  
- **Younger customers** and those with fewer products tend to leave more often — offering personalized packages could help retain them.  
- **Credit score** and **geography** play key roles — retention strategies should be customized per segment.

---

## 🧠 Tools Used
- **Tableau Desktop** – for dataset preparation and data analysis and dashboard creation  

---


---

## 🚀 Conclusion
This project provides a **data-driven view of customer churn**, helping identify key pain points and actionable strategies for retention.  
With **interactive Tableau dashboards**, decision-makers can monitor churn trends, understand customer behavior, and design **proactive strategies** to reduce attrition.

---

👩‍💻 **Author:** Hadil Sahraoui  
📧 **Contact:** hadil.sahraoui129@gmail.com  
🔗 **LinkedIn:** [linkedin.com/in/hadil-sahraoui](https://linkedin.com/in/hadil-sahraoui)

