# Sales Data Analysis Project

## Project Overview

This project analyzes historical sales data  which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. to uncover key business insights, identify trends, and highlight top-performing products and customers. The primary goal is to provide actionable recommendations for business strategy and performance improvement.

## Objectives

* Identify **top-selling products** and categories.
* Analyze **customer revenue** and highlight **top customers**.
* Examine **sales trends** over time (monthly, quarterly, yearly).
* Detect anomalies such as **returns or negative sales**.
* Build a **dashboard for interactive visualization** in Tableau.

## Data Description

The dataset contains transactional sales data with the following columns:

| Column Name   | Description                                 |
| ------------- | ------------------------------------------- |
| `InvoiceNo`   | Unique identifier for each transaction      |
| `StockCode`   | Unique code for each product                |
| `Description` | Product name                                |
| `Quantity`    | Number of units sold (negative for returns) |
| `InvoiceDate` | Date of the transaction                     |
| `UnitPrice`   | Price per unit                              |
| `CustomerID`  | Unique identifier for each customer         |
| `Country`     | Country of the customer                     |

## Data Cleaning & Preparation

* Removed duplicate transactions.
* Handled missing or null values.
* Corrected data types 
* Created calculated fields:
* Filtered out negative quantities where necessary for certain visualizations.

## Analysis & Insights

1. **Top Products**: Identified the highest-selling products by quantity and revenue.
2. **Top Customers**: Highlighted customers generating the most revenue.
3. **Sales Trends**: Visualized monthly/quarterly/yearly sales trends.
4. **Returns Analysis**: Examined transactions with negative quantities to understand returns.
5. **Geographical Analysis**: Analyzed sales performance across different countries.

## Tools & Technologies

* **Python**: Pandas, Matplotlib, Seaborn for initial analysis.
* **Tableau Desktop**: Dashboard creation and interactive visualizations.


## Dashboard Features

* Top 10 Products by Quantity and Revenue.
* Top 10 Customers by Revenue.
* Monthly Revenue Trend chart.
* Positive vs. Negative Quantity (Sales vs. Returns) visualization.
* Country-wise sales analysis map.
* Interactive filters for Product Category, Country, and Time Period.



## Conclusion

This project provides a comprehensive view of sales performance, customer behavior, and product trends. By leveraging these insights, the business can:

* Optimize inventory and product offerings.
* Focus on high-value customers.
* Identify seasonal trends for better planning.
* Reduce returns and improve customer satisfaction.


