# Superstore_sales_report

# 📊 Superstore Sales Report Dashboard – Power BI

Welcome to the **Superstore Sales Report Dashboard** repository!  
This project presents a powerful **Power BI dashboard** that visualizes and analyzes sales performance data for a fictional retail store. It demonstrates data storytelling, dashboard design best practices, and interactive visual analytics.
This repository contains a comprehensive Power BI dashboard designed to analyze and visualize sales performance for a fictional Superstore. The dashboard delivers key insights into sales trends, profitability, customer segments, product categories, and shipping behavior, enabling data-driven decision-making.

---

## 🚀 Project Objectives

- Provide a holistic view of **sales, profit, and customer behavior**
- Deliver **interactive reports** for data-driven decision-making
- Demonstrate best practices in **visual storytelling** and dashboard layout
- Enable easy comparison of **monthly, regional, and product-based sales metrics**

---

## 📌 Key Dashboard Features

- ✅ **KPIs** for Total Sales, Profit, Quantity, and Average Delivery Days  
- ✅ **Sales Breakdown** by Category and Subcategory  
- ✅ **Segment and Region-Level Insights**  
- ✅ **Shipping and Payment Mode Analysis**  
- ✅ **Monthly Sales and Profit Trends (YoY)**  
- ✅ **Top Performing States**  
- ✅ **20-Day Profit Forecast Visualization**

---

## 🛠 Tools & Technologies

- **Power BI Desktop**
- DAX for calculated fields
- Data source (not included): Excel/CSV

---
## 📐 DAX Formulas Used

Below are the key DAX measures created to support the visuals and KPIs in this Power BI dashboard:

Average Delivery Days

Average Delivery Days = AVERAGE('Sales'[Delivery Days])

Sales Forecast Table

SalesForecast = SUMMARIZE(SuperStore_Sales_Dataset , SuperStore_Sales_Dataset[Order Date] , "Total Sales" , SUM('SuperStore_Sales_Dataset'[Sales]))

## 💡 Insights & Learnings

This project showcases how to:
Incorporated data analysis techniques , specializing , in time series analysis , to deliver valuable insights , accurate sales forecasting and interactive dashboard creation , driving business success . 

---

## 📚 Storyboard Summary

 1. Executive Summary

    Highlights total Sales ($252.12K), Profit ($26.55K), and Units Sold (3,529).

    Shows key performance indicators in a high-level snapshot.

    Provides a quick overview of business health and delivery performance (avg. 4 days).

2. Sales by Category and Subcategory

    Breaks down total sales into Office Supplies, Technology, and Furniture.

    Top subcategories include Phones, Tables, and Storage.

    Helps identify which product types drive the most revenue.
   
3. Regional and Segment Analysis

    Maps sales distribution across Central, East, South, and West regions.

    Highlights customer segments:

        Consumer (54%),

        Corporate (30%),

        Home Office (17%).

4. Sales by Shipping and Payment Mode

    Analyzes shipping preferences:

        Standard Class leads at $48K, followed by Second Class and First Class.

    Tracks payment preferences:

        Online (44%), Cards (37%), Cash on Delivery (19%).

5. Time-Based Trends

    Monthly Sales and Profit YoY (2019 vs. 2020) shown with side-by-side comparison.

    Identifies peak months and seasonal trends.

    Profit trend highlights operational or pricing issues in some months.

6. State-Level Sales Distribution

    Visualizes top-performing states:

        California leads with $340K, followed by New York and Texas.

    Allows targeted marketing or regional planning.

7. Sales & Profit Over Time

    Trend line shows day-level sales and profit values from Oct 2020–Jan 2021.

    Detects spikes and dips to investigate key events or campaigns.

8. 20-Day Profit Forecast

    Predicts profit performance based on historical order data.

    Highlights expected gains/losses and variability—useful for short-term strategy planning.

9. Dashboard Design Principles

    Uses clean layout, consistent color schemes, intuitive filters.

    Designed for executive-level consumption and actionable insights.

---

## 📥 How to Use

1. Open `Sales_Report.pdf` to explore the report output  
2. For editable insights, open the Power BI `.pbix` file in Power BI Desktop  
3. Analyze trends, filter segments, and share findings!



