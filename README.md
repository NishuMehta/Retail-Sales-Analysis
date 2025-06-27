# Retail Sales Analysis

This project analyzes a retail dataset to uncover trends in sales performance, customer behavior, and regional patterns. It also includes a Power BI dashboard for business insights.

---

## Dataset

- Source: [Kaggle - Retail Sales Dataset](https://www.kaggle.com/datasets/noir1112/retail-sales-data)
- Columns include:
  - `Sales_ID`, `Product_Category`, `Sales_Amount`, `Discount`
  - `Sales_Region`, `Date_of_Sale`, `Customer_Age`, `Customer_Gender`, `Sales_Representative`

---

## Tools & Technologies Used

- **Python**: pandas, matplotlib, seaborn
- **Power BI**: Dashboard and KPI reporting
- **Jupyter Notebook**: Data cleaning & EDA

---

## Exploratory Data Analysis (Python)

- Sales by Region, Product Category
- Monthly trends (by Year & Month)
- Customer demographics (Age Group, Gender)
- Discount vs Sales correlation
- Top 10 Sales Representatives

---

## Power BI Dashboard

The dashboard includes:
-  Total Sales, Total Discounts, Total Transactions
-  Sales by Region
-  Sales by Product Category
-  Monthly Sales Trends
-  Sales by Gender & Age Group
-  Slicers for Region, Year, Category

**Preview:**

![Dashboard Preview](dashboard/dashboard_screenshot.png)

---

## Key Insights

- **North & East** regions had the highest total sales.
- **Category A** and **Category B** products were the top-performing.
- Customers aged **31–45** generated the highest revenue.
- Discount-heavy regions didn’t always convert to higher sales.
- Sales trends showed a dip in Q3, suggesting seasonality.

---

## What I Learned

- Cleaning and transforming real-world retail data using Python
- Building insightful visualizations with matplotlib & seaborn
- Designing a structured and interactive Power BI dashboard
- Drawing actionable business insights from data

---

## Folder Structure

Retail-Sales-Profit-Analysis/  
│  
├── data/  
│ ├── RetailSalesData.csv  
│ └── cleaned_retail_sales_data.csv  
│  
├── notebooks/  
│ └── analysis.ipynb  
│  
├── dashboard/  
│ ├── Dashboard.pbix  
│ └── Dashboard.png
| └── Dashboard.pdf
│  
└── README.md  
  
---

*This project is part of my Data Analyst Portfolio.*
