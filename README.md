# Customer Churn Analysis | Power BI Project  

## Overview  
This Power BI project focuses on analyzing customer churn data to uncover meaningful insights into customer behavior, service usage, and billing patterns.  
The primary goal is to identify key factors that contribute to customer churn and help the telecom company design effective, data-driven retention strategies.  



## Project Objective  
- Analyze customer churn trends and patterns.  
- Identify key factors influencing churn such as tenure, contract type, and payment method.  
- Visualize customer demographics, subscription preferences, and billing insights.  
- Develop interactive dashboards to support strategic business decisions.  
- Support retention initiatives to reduce churn and improve customer satisfaction.  

---

## Dataset Information  
**Source:** Innomatics Research Labs – Telco Customer Churn Dataset  
**File Type:** CSV / Excel  
**Total Records:** 7,043 customers  
**Total Columns:** 21 fields  

### Key Columns  
- **Customer Info:** customerID, gender, SeniorCitizen, Partner, Dependents  
- **Services:** PhoneService, InternetService, StreamingTV, OnlineSecurity, TechSupport  
- **Billing & Contract:** Contract, PaymentMethod, PaperlessBilling, MonthlyCharges, TotalCharges  
- **Target Variable:** Churn (Yes/No)  

---

## Data Preparation  
- Cleaned and transformed the dataset using Power Query Editor.  
- Converted data types where necessary (e.g., TotalCharges → numeric).  
- Handled missing and blank values.  
- Created calculated columns such as tenure categories and total subscribed services.  
- Built DAX measures for key performance indicators (KPIs), including:  
  - Churn Rate  
  - Average Monthly Charges  
  - Average Tenure  
  - Total Customers / Churned Customers  

---

## Data Modeling  
- Built a single dataset model (flat structure).  
- Established logical relationships between demographic, service, and billing fields.  
- Created DAX relationships for data segmentation and comparative analysis.  

---

## Dashboard Visualizations  

### 1. Customer Demographics Dashboard  
- Gender distribution and senior citizen churn comparison.  
- Tenure-based churn analysis.  
- Key metrics: Total Customers, Churned Customers, Average Monthly Charges, Average Tenure.  

### 2. Service Subscription Dashboard  
- Churn rate by phone and internet service types.  
- Comparison between DSL and Fiber Optic users.  
- Add-on services (Online Security, Device Protection) and their relation to churn.  
- Interactive slicers for gender, senior citizen status, and contract type.  

### 3. Contract and Billing Insights Dashboard  
- Churn rate by contract type and payment method.  
- Average total charges by contract.  
- Relationship between paperless billing and churn.  
- Tenure distribution visualizations for different customer segments.  

---

## Key Insights  
- Overall churn rate is approximately **26.5%**.  
- **Month-to-Month** contract customers show the highest churn.  
- **Fiber Optic** users are more likely to churn than **DSL** users.  
- **Senior citizens** and customers **without dependents** tend to churn more frequently.  
- Customers with **multiple services** and **longer tenure** show higher loyalty.  
- **Paperless billing** and **electronic payment methods** are associated with higher churn rates.  

---

## Business Impact  
- Identifies high-risk churn segments for targeted intervention.  
- Enables focused marketing and retention campaigns.  
- Improves understanding of customer lifetime value (CLV).  
- Supports data-driven decisions across business units.  

---

## Tools and Technologies  
- Power BI Desktop  
- Power Query (for data cleaning and transformation)  
- DAX (for calculated measures and KPIs)  
- Excel / CSV Dataset  

---

## KPIs Included  
- Total Customers  
- Churned Customers  
- Churn Rate (%)  
- Average Monthly Charges  
- Average Tenure  
- Total Revenue  

---

## Recommendations  
- Encourage long-term contracts through loyalty discounts.  
- Promote bundled service packages to improve customer retention.  
- Offer personalized plans for senior citizens and high-charge customers.  
- Enhance the user experience for electronic payment options to reduce churn.  

---

## Conclusion  
This project demonstrates how Power BI can transform raw telecom data into actionable business insights.  
By identifying the key drivers of churn and visualizing important trends, businesses can proactively reduce customer churn, enhance satisfaction, and boost profitability.  
