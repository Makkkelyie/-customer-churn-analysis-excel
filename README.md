
# 📊 Customer Churn Analysis (Excel Project)

**Author:** Kelly Mao  
**Date:** June 2025  

This project analyzes customer churn behavior in a telecommunications company using Excel.

## 📁 Dataset
- Source: [Telco Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Rows: 7,032 customer records
- Features include: contract type, monthly charges, tenure, internet service, and churn label

## 🎯 Project Objectives
- Calculate the overall churn rate
- Identify which customer groups are more likely to churn
- Visualize churn behavior by contract type using pivot tables and charts
- Suggest potential strategies to reduce churn

## 🛠 Tools & Techniques
- Microsoft Excel (Mac version)
- Data Cleaning (removing nulls, formatting columns)
- Formulas: `COUNTIF`, `COUNTA`, ratio calculations
- Pivot Tables
- Stacked Column Chart
- Markdown for documentation

## 📊 Key Insights
- The overall churn rate is **26.6%**
- Customers with **month-to-month contracts** churn the most
- Long-term contracts (1-year, 2-year) are associated with significantly lower churn rates

## 📸 Visualization

**Churn by Contract Type:**

![Churn Chart](charts/contract-vs-churn.png)

## 📂 File Structure

```
customer-churn-analysis-excel/
├── Telco-Churn-Cleaned.xlsx        # Cleaned Excel file with pivot tables and charts
├── charts/
│   └── contract-vs-churn.jpg      # Exported chart showing churn vs contract type
└── README.md                       # This documentation file
```

## ✅ Conclusion
This project demonstrates how Excel can be used for exploratory data analysis and visualization in business contexts. Churn behavior is strongly correlated with contract type, and visual tools can help identify patterns to support business decisions.
