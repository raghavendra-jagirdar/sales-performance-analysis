# 📊 Sales Performance Analysis (Power BI)

## 📌 Project Overview

This project analyzes sales data to uncover insights related to revenue, profitability, customer behavior, and operational performance.

## 🎯 Business Problem

Businesses often struggle to understand which regions, products, and time periods drive revenue and profit.
This project aims to identify sales trends, profitability issues, and areas of operational inefficiency to support better decision-making.

## 🚀 Tools Used
- Power BI  
- Excel  
- DAX  

## 📌 Key KPIs

* Total Revenue
* Total Profit
* Profit %
* Total Orders
* Average Order Value

## 📈 Key Insights

* Revenue is heavily concentrated in South America, indicating potential dependency on a single region and associated business risk.
* Sales peak in May while dipping in April, suggesting seasonal demand patterns that can impact inventory and planning.
* A small group of top-performing products contributes significantly to both revenue and profit, highlighting opportunities for product-focused strategies.
* High return and cancellation rates point to operational inefficiencies, potentially impacting overall profitability and customer satisfaction.

## 📐 Key DAX Measures

* Total Revenue = SUM(revenue)
* Total Profit = SUM(profit)
* Profit % = DIVIDE(Total Profit, Total Revenue)
* Average Order Value = DIVIDE(Total Revenue, Total Orders)
* Total Orders = COUNT(order_id)

## 🖼️ Dashboard Preview

### 🔹 Sales Overview

![Sales Overview](screenshots/overview.png)

### 🔹 Product Insights

![Product Insights](screenshots/product_insights.png)


## 🚀 Outcome

This analysis highlights key revenue drivers, identifies dependency on specific regions, and uncovers operational inefficiencies such as high return and cancellation rates.

The insights can help businesses improve product strategy, optimize regional performance, and reduce losses by addressing inefficiencies in order processing and customer experience.

## 📂 Project Structure

* dataset/ → Raw dataset used for analysis
* powerbi/ → Power BI dashboard file (.pbix)
* screenshots/ → Dashboard preview images

