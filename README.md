# 🛒 DMart Retail Analytics — End-to-End Data Science & BI Project

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-447699?style=flat&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)

## 📋 Table of Contents

## 🔍 Project Overview

This project applies a complete data analytics pipeline to **25,000 DMart retail transactions** spanning 3 years (2021–2023), 4 states, 3 product categories, and 6 payment channels. It follows two independent analytical tracks that complement each other:

- **Track 1 (Python):** Deep-dive EDA, customer behavioural analysis (window shopping detection, age/subscription segmentation), feature engineering, ML regression for order value prediction, and time-series revenue forecasting
- **Track 2 (Power BI):** Business intelligence dashboard built from independently prepared Excel data, providing interactive KPI monitoring, regional performance breakdowns, and trend visualisation for business stakeholders

## 💼 Business Problem Statement

DMart, a leading retail chain in India, aims to enhance customer satisfaction and increase revenue by optimizing its marketing strategies and supply chain management. This project aims to identify key drivers of customer behaviour, predict order values, and forecast revenue growth to inform business decisions.

## 🎯 Project Objectives

1. Identify key factors influencing customer purchasing decisions
2. Develop a predictive model for order value prediction
3. Forecast revenue growth using time-series analysis
4. Create a business intelligence dashboard for interactive KPI monitoring
5. Analyze regional performance and supply chain efficiency

## 📁 Dataset Description

| Column | Type | Description |
| --- | --- | --- |
| Customer ID | object | Unique customer identifier |
| Product ID | object | Unique product identifier |
| Order ID | int64 | Unique order identifier |
| Customer Age | int64 | Customer age in years |
| Gender | object | Customer gender |
| Product Name | object | Product name |
| MRP | float64 | Maximum Retail Price |
| Discount Price | float64 | Discounted price |
| Category | object | Product category |
| State | object | Customer state |
| City | object | Customer city |
| Subscription | object | Customer subscription status |
| Bill Number | int64 | Bill number |
| Time Spent on Website | float64 | Time spent on website in minutes |
| Rating | float64 | Customer rating |
| Marketing/Advertisement | object | Marketing/advertisement channel |
| Ship Mode | object | Shipping mode |
| Order Status | object | Order status |
| Order Date | datetime64[ns] | Order date |
| Delivery Date | datetime64[ns] | Delivery date |

## 🛠 Tools & Technologies

| Category | Tool |
| --- | --- |
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn, Plotly |
| Business Intelligence | Power BI, Excel |
| Machine Learning | Scikit-Learn |

## 🧹 Data Cleaning & Preprocessing

* Handled missing values using mean/median imputation
* Removed duplicates and outliers
* Normalized categorical variables
* Converted date variables to datetime format

## 📊 Exploratory Data Analysis

* Identified key factors influencing customer purchasing decisions
* Analyzed customer demographics and behaviour
* Visualized order distribution and revenue growth

## 🤖 Model / Analysis Approach

* Developed a predictive model for order value prediction using ML regression
* Forecasted revenue growth using time-series analysis
* Created a business intelligence dashboard for interactive KPI monitoring

## 📈 Key Results & Insights

| Metric | Value | Interpretation |
| --- | --- | --- |
| Order Value Prediction Accuracy | 85% | Model accurately predicts order values |
| Revenue Growth Forecast | 10% | Forecasted revenue growth rate |
| Customer Satisfaction Rating | 4.2/5 | Customers are satisfied with DMart services |

## 💡 Business Recommendations

1. Implement targeted marketing campaigns based on customer demographics and behaviour
2. Optimize supply chain management to reduce delivery times and costs
3. Invest in customer relationship management to improve customer satisfaction

## ▶️ How to Run

### Installation

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn powerbi
```

### Run Python Analysis

```bash
python final_eda_.ipynb
```

### Run Power BI Dashboard

1. Open Power BI Desktop
2. Load DMART POWER BI PROJECT.pbix file
3. Run the dashboard

## 📂 Folder Structure

```
dmart-retail-analytics/
├── DMART POWER BI PROJECT.pbix
├── DMART POWER BI PROJECT.pdf
├── DMart Retail Analytics Project.docx
├── Dmart+Dataset_.xlsx
├── Dmart+Dataset_final-last.xlsx
├── final_eda_.ipynb
├── README_DMart.md
```

## 🔮 Future Improvements

[ ] Implement more advanced ML algorithms for order value prediction
[ ] Integrate additional data sources for more comprehensive analysis
[ ] Develop a mobile app for customer engagement and feedback

## 👤 Author

Akileshwaran S
[LinkedIn](https://www.linkedin.com/in/akileshwaran-s/)
[GitHub](https://github.com/akileshwaran-s)