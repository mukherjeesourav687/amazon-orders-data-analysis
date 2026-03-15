# Amazon Orders Data Analysis (Excel Project)

## Overview

This project performs data analysis on an Amazon Orders dataset using Microsoft Excel.  
The goal was to clean the dataset, perform exploratory analysis, and generate business insights using Excel formulas, Pivot Tables, and data visualizations.

The analysis focuses on understanding order trends, customer demographics, and sales performance.

---

## Project Objective

The objective of this project is to analyze an ecommerce orders dataset and derive meaningful insights related to customer behavior, ordering patterns, and sales performance using Microsoft Excel.

---

## Tools Used

• Microsoft Excel  
• Pivot Tables  
• Excel Formulas (IF, SUMIFS, COUNTIFS, AVERAGEIFS)  
• Data Cleaning Techniques  
• Data Visualization

---

## Dataset

The dataset contains information about customer orders including:

• Customer ID  
• Customer Country  
• Order Date and Time  
• Order Source  
• Sales Representative (Sales POC)  
• Order Value  
• Customer Age  
• Sales Targets  

The dataset contains three main tables:

• Orders  
• Customers  
• Sales Targets

---

## Data Preparation

Before performing analysis, several preprocessing steps were performed:

• Split Order Datetime into Order Date and Order Time  
• Created Order Month and Order Day columns  
• Handled missing Age values using moving average  
• Detected outliers using the Interquartile Range (IQR) method  
• Created Age Groups for customer segmentation

---

## Analysis & Visualizations

### Orders Trend

This analysis shows the number of orders and average order value by month.

![Orders Trend](charts/Orders%20Trend%20chart.png)

---

### Orders by Country

Orders were grouped by customer country to identify the countries generating the most orders.

![Orders by Country](charts/Orders%20by%20Country%20chart.png)

---

### Orders by Hour

This analysis identifies peak ordering hours during the day.

![Orders by Hour](charts/Orders%20by%20Hour%20chart.png)

---

### Age Group Analysis

Customers were segmented into age groups to understand which segments contribute the most orders.

![Age Group Analysis](charts/Age%20Group%20Analysis%20chart.png)

---

### Sales Target Analysis

Sales representatives were evaluated based on achieved sales vs assigned sales targets.

![Sales Target Status](charts/Sales%20Target%20Status%20chart.png)

---

## Key Insights

• A significant portion of orders occur during late-night hours  
• Certain countries generate higher order volumes compared to others  
• Customers aged 30–40 contribute a large portion of total orders  
• Several sales representatives exceeded their assigned targets  
• However, more sales representatives did not meet their targets

---

## Project Workflow

1. Data Cleaning  
2. Feature Engineering  
3. Pivot Table Analysis  
4. Data Visualization  
5. Sales Performance Analysis  

---

## Skills Demonstrated

• Data Cleaning  
• Excel Data Analysis  
• Pivot Tables  
• Conditional Logic  
• Aggregation Functions  
• Data Visualization  

---

## Repository Structure

```
amazon-orders-data-analysis
│
├── charts
│   ├── Orders Trend chart.png
│   ├── Orders by Country chart.png
│   ├── Orders by Hour chart.png
│   ├── Age Group Analysis chart.png
│   └── Sales Target Status chart.png
│
├── Amazon Orders Dataset.xlsx
└── README.md
```

---

## Conclusion

This project demonstrates how Excel can be used for end-to-end data analysis, including data cleaning, pivot analysis, and visualization to generate actionable business insights.
