# 📊 Telecom Customer Churn Analysis Using Python

## 📌 Project Overview

Customer churn occurs when customers stop using a company's services. Understanding customer churn helps telecom companies improve customer satisfaction, retain existing customers, and reduce revenue loss.

This project analyzes telecom customer data using Python to identify customer behaviour, understand the major reasons for churn, and provide business recommendations to improve customer retention.

## 📂 Dataset Information

- **Dataset Name:** Telecom Customer Churn
- **Source:** [Maven Analytics – Telecom Customer Churn](https://mavenanalytics.io/data-playground/telecom-customer-churn)
- **File Format:** CSV
- **Total Records:** 7,043 customers
- **Total Columns:** 38

The dataset includes customer demographics, service subscriptions, contract details, billing information, tenure, customer status, churn categories, and churn reasons.

## 🎯 Project Objectives

- Calculate the overall customer churn rate.
- Identify customer groups with higher churn rates.
- Analyze the relationship between customer tenure and churn.
- Understand how contract types influence customer churn.
- Analyze monthly charges and total revenue.
- Identify the most common reasons for customer churn.
- Understand how internet and additional services influence customer retention.
- Provide business recommendations to reduce customer churn.

## 🛠️ Tools and Technologies

- **Python** – Data analysis and programming
- **Pandas** – Data cleaning and manipulation
- **NumPy** – Numerical calculations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Google Colab** – Development environment

## 🔍 Project Workflow

### 1. Data Loading

- Imported the dataset using Pandas.
- Examined the dataset structure, columns and data types.
- Checked the number of records and attributes.

### 2. Data Cleaning

- Identified and handled missing values.
- Checked duplicate records.
- Investigated negative monthly charge values.
- Replaced missing categorical and numerical values appropriately.

### 3. Data Transformation

- Converted Customer ID into string format.
- Created a separate dataset for existing customers.
- Created a numerical Churn Flag.

### 4. Feature Engineering

Created additional features:

- Tenure Group
- Age Group
- Monthly Charge Category
- Additional Services Count
- Churn Flag

### 5. Exploratory Data Analysis (EDA)

Performed analysis on:

- Overall customer churn rate
- Customer demographics
- Customer tenure
- Contract types
- Monthly charges and total revenue
- Churn reasons
- Internet services
- Additional services

### 6. Statistical Analysis

Calculated:

- Mean
- Median
- Mode
- Variance
- Standard Deviation
- Skewness
- Kurtosis

### 7. Data Visualization

Created visualizations using Matplotlib and Seaborn to understand customer behaviour and churn patterns.

## 📈 Summary of Key Findings

## 🔍 Key Findings
 
**Overall churn rate: 28.37%** among existing customers (1,869 of 6,589).
 
### Churn by Customer Segment
 
| Segment | Churn Rate |
|---|---|
| Married: No | 36.69% |
| Married: Yes | 20.16% |
| Age: Above 60 | 37.90% |
| Age: 26–40 | 25.99% |
| Gender: Female / Male | 28.65% / 28.08% |
 
### Churn by Tenure
 
| Tenure | Churn Rate |
|---|---|
| 0–12 months | **59.87%** |
| 13–24 months | 28.71% |
| 25–48 months | 20.39% |
| 49–72 months | 9.51% |
 
### Churn by Contract Type
 
| Contract | Churn Rate |
|---|---|
| Month-to-Month | **51.69%** |
| One Year | 10.88% |
| Two Year | 2.58% |
 
### Churn by Internet Type
 
| Internet Type | Churn Rate |
|---|---|
| Fiber Optic | **42.13%** |
| Cable | 27.52% |
| DSL | 19.97% |
| No Internet Service | 8.41% |
 
### Revenue Comparison
 
| Status | Avg Monthly Charge | Avg Total Revenue |
|---|---|---|
| Churned | 73.35 | 1,971.35 |
| Stayed | 61.74 | 3,735.68 |
 
### Top Churn Reasons
 
| Reason | Customers |
|---|---|
| Competitor had better devices | 313 |
| Competitor made better offer | 311 |
| Attitude of support person | 220 |
| Don't know | 130 |
| Competitor offered more data | 117 |
 
### Additional Services
 
Customers with more add-on services generally churn less — from **48.11%** (1 service) down to **5.06%** (7 services).
 

### Revenue Analysis

| Customer Status | Average Monthly Charge | Average Total Revenue |
| --------------- | ---------------------- | --------------------- |
| Churned         | 73.35                  | 1,971.35              |
| Stayed          | 61.74                  | 3,735.68              |

Stayed customers generate higher average total revenue than churned customers.

## 💡 Business Recommendations

Based on the analysis, the following recommendations are suggested:

1. **New Customer Retention:** Provide welcome offers and onboarding support during the first 12 months.
2. **Contract Improvement:** Encourage customers to choose long-term contracts through attractive benefits.
3. **Internet Service Improvement:** Investigate Fiber Optic service quality, pricing and customer satisfaction.
4. **Competitive Offers:** Introduce attractive pricing and better service packages.
5. **Customer Support:** Improve customer service quality and response time.
6. **Additional Services:** Promote useful additional services based on customer needs.
7. **Revenue Protection:** Focus on retaining valuable existing customers.

## 🚀 Future Enhancements

- Develop an interactive Power BI dashboard.
- Integrate customer data using SQL.
- Build a machine learning model to predict customer churn.
- Identify customers with a high risk of leaving.
- Develop advanced customer segmentation.
- Automate regular customer churn reporting.
- Evaluate customer retention campaign performance.

## 📝 Project Conclusion

This project helped identify important factors associated with telecom customer churn using Python.

The analysis revealed that new customers, Month-to-Month contract customers and Fiber Optic customers have relatively higher churn rates.

Competitor offers, device quality and customer support are also important areas requiring attention.

The findings can help telecom companies improve customer satisfaction, strengthen customer loyalty and reduce revenue loss.

## 👩‍💻 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualization
- Business Insights
- Data-Driven Decision Making

## 👩‍💻 Author

**Revathi Sulochana**

Aspiring Data Analyst | Python | SQL | Power BI | Advanced Excel

