# Amazon Orders Data Analysis (Excel Project)

## Overview

This project performs **data analysis on an Amazon Orders dataset using Microsoft Excel**.
The goal was to clean the dataset, perform exploratory analysis, and generate business insights using **Excel formulas, pivot tables, and visualizations**.

The analysis focuses on order trends, customer demographics, and sales performance.

---

## Tools Used

* Microsoft Excel
* Pivot Tables
* Excel Formulas (IF, SUMIFS, COUNTIFS, AVERAGEIFS)
* Data Cleaning Techniques
* Data Visualization

---

## Dataset

The dataset contains information about customer orders including:

* Customer ID
* Customer Country
* Order Date and Time
* Order Source
* Sales Representative (Sales POC)
* Order Value
* Customer Age
* Sales Targets

---

## Data Preparation

Before performing analysis, several preprocessing steps were performed:

* Split **Order Datetime** into **Order Date** and **Order Time**
* Created **Month** and **Day** columns
* Handled missing **Age values** using moving average
* Detected outliers using the **IQR method**
* Created **Age Groups** for customer segmentation

---

## Analysis & Visualizations

### Orders Trend

This analysis shows the **number of orders and average order value by month**.

![Orders Trend](charts/orders-trend.png)

---

### Orders by Country

Orders were grouped by **customer country** to identify the countries generating the most orders.

![Orders by Country](charts/orders-country.png)

---

### Orders by Hour

This analysis identifies **peak ordering hours during the day**.

![Orders by Hour](charts/orders-hour.png)

---

### Age Group Analysis

Customers were segmented into age groups to understand which segments contribute the most orders.

![Age Group Analysis](charts/age-group-analysis.png)

---

### Sales Target Analysis

Sales representatives were evaluated based on **achieved sales vs target sales**.

![Sales Target Status](charts/sales-target-status.png)

---

## Key Insights

* A significant portion of orders occur during **late-night hours**
* Some countries generate **much higher order volume**
* Customers aged **30–40 contribute a large portion of orders**
* Several sales representatives **exceeded their targets**
* However, more representatives **did not meet their targets**

---

## Project Workflow

1. Data Cleaning
2. Feature Engineering
3. Pivot Table Analysis
4. Data Visualization
5. Sales Performance Analysis

---

## Skills Demonstrated

* Data Cleaning
* Excel Data Analysis
* Pivot Tables
* Conditional Logic
* Aggregation Functions
* Data Visualization

---

## Repository Structure

```
amazon-orders-data-analysis
│
├── charts
│   ├── orders-trend.png
│   ├── orders-country.png
│   ├── orders-hour.png
│   ├── age-group-analysis.png
│   └── sales-target-status.png
│
├── Amazon Orders Dataset.xlsx
└── README.md
```

---

## Conclusion

This project demonstrates how Excel can be used for **end-to-end data analysis**, including data cleaning, pivot analysis, and visualization to generate business insights.
