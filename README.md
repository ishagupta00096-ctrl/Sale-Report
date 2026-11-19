# Mobile Sales Analysis Dashboard 

## 1. Project Title / Headline

Mobile Sales Analysis Dashboard – Business Intelligence & Data Analytics using Power BI

## 2. Project Description / Purpose

The Mobile Sales Analysis Dashboard is an interactive Business Intelligence project developed using Microsoft Power BI. The project focuses on analyzing mobile sales data to understand revenue performance, customer purchasing behavior, mobile model performance, payment preferences and geographical sales distribution.

The main purpose of this dashboard is to transform raw sales data into meaningful business insights through interactive visualizations, KPI cards and filters.

## 3. Technology Stack

- Microsoft Power BI – Dashboard development and visualization.
- Power Query – Data cleaning and transformation.
- DAX – Calculated measures and KPI development.
- Microsoft Excel – Dataset source.
- Data Modeling – Organizing and managing sales data.
- Data Visualization – Interactive charts, maps and reports.

## 4. Data Source

Dataset Name: Mobile Sales Data

Data Source: Excel Dataset (Sheet1)

The dataset contains the following fields:

- Transaction ID
- Date
- Day Name
- Brand
- Units Sold
- Price Per Unit
- Customer Name
- Customer Age
- City
- Payment Method
- Customer Ratings
- Mobile Model

## 5. Business Problem

Mobile retail businesses generate large amounts of sales data. However, analyzing sales performance, customer preferences, product performance and geographical distribution manually can be difficult.

Businesses need an interactive solution to understand:

- Which mobile models generate the highest revenue?
- Which brands contribute to overall sales?
- Which cities generate mobile sales?
- Which payment methods are preferred by customers?
- How does sales performance change across different days?
- What are the customer ratings?
- How many units are sold and how many transactions occur?

This project addresses these challenges through an interactive Power BI dashboard.

## 6. Goal of the Dashboard

The primary goals of this dashboard are:

- Monitor overall mobile sales performance.
- Track total revenue and quantity sold.
- Analyze mobile model performance.
- Compare brand-wise sales performance.
- Understand city-wise sales distribution.
- Analyze customer payment preferences.
- Track daily and quarterly sales patterns.
- Evaluate customer ratings.
- Support data-driven business decisions.

## 7. Features & Dashboard Highlights

  ### A. KPI Cards
  
  The dashboard includes four important Key Performance Indicators:
  
  1. Total Sales – Calculates total revenue generated from mobile sales.
  2. Total Quantity – Displays the total number of mobile units sold.
  3. Average – Calculates the average price per unit.
  4. Transaction – Displays the total number of transactions.
  
  ### B. Geographical Sales Analysis
  
  - Displays city-wise sales distribution using a map.
  - Helps identify geographical sales patterns.
  - Supports location-based business analysis.
  
  ### C. Mobile Model Performance
  
  - Compares mobile models based on total sales.
  - Identifies the top-performing mobile models.
  - Helps understand product revenue contribution.
  
  ### D. Payment Method Analysis
  
  - Analyzes transaction distribution by payment method.
  - Helps identify customer payment preferences.
  - Compares different payment options.
  
  ### E. Daily Sales Trend
  
  - Displays total sales by day name.
  - Helps analyze daily revenue patterns.
  - Supports sales performance monitoring.
  
  ### F. Quarterly and Yearly Analysis
  
  - Analyzes total quantity across quarters and years.
  - Helps compare sales quantity over different periods.
  - Supports trend analysis.
  
  ### G. Customer Ratings Analysis
  
  - Uses a funnel visualization to analyze customer ratings.
  - Helps understand customer feedback patterns.
  
  ### H. Brand Performance Analysis
  
  - Displays brand-wise total sales.
  - Compares total quantity sold.
  - Analyzes transaction counts across brands.
  
  ### I. Interactive Filters and Slicers
  
  The dashboard provides interactive filters for:
  
  - Date
  - Brand
  - Mobile Model
  - Day Name
  - Payment Method
  
  These filters allow users to explore sales performance based on different business requirements.

## 8. Walkthrough of Key Visuals

1. KPI Cards: Provide an overview of total sales, total quantity, average price and transactions.

2. Map Visualization: Shows geographical sales distribution across cities.

3. Clustered Bar Chart: Compares mobile models based on total sales and identifies top-performing models.

4. Pie Chart: Displays transaction distribution across different payment methods.

5. Area Chart: Shows total sales by day name to understand daily sales performance.

6. Line Chart: Analyzes total quantity across quarters and years.

7. Funnel Chart: Visualizes customer ratings distribution.

8. Table Visualization: Provides brand-wise comparison of total sales, total quantity and transactions.

9. Slicers: Allow users to interactively filter the dashboard by date, brand, mobile model, day and payment method.

## 9. DAX Measures

  ### Total Sales
  
  Total Sales = SUMX(Sale_Date2, Sale_Date2[Units Sold] * Sale_Date2[Price Per Unit])
  
  Purpose: Calculates total revenue by multiplying units sold by price per unit.
  
  ### Total Quantity
  
  Total Quantity = SUM(Sale_Date2[Units Sold])
  
  Purpose: Calculates the total number of units sold.
  
  ### Transaction
  
  Transaction = COUNTROWS(Sale_Date2)
  
  Purpose: Calculates the total number of sales records.
  
  ### Average
  
  Average = AVERAGE(Sale_Date2[Price Per Unit])
  
  Purpose: Calculates the average price per unit.

## 10. Business Impact & Insights

  ### Revenue Analysis
  - Helps monitor overall revenue performance.
  - Identifies mobile models contributing to sales.
  - Supports product performance comparisons.
  
  ### Customer Behavior Analysis
  - Provides insights into customer payment preferences.
  - Helps analyze customer ratings.
  - Supports customer-focused business strategies.
  
  ### Geographical Analysis
  - Helps understand city-wise sales distribution.
  - Supports location-based marketing decisions.
  
  ### Sales Performance
  - Helps monitor daily sales trends.
  - Supports quarterly and yearly sales analysis.
  - Helps businesses make informed sales and inventory planning decisions.
  
  ### Business Decision-Making
  - Provides a centralized view of sales performance.
  - Reduces the effort required for manual reporting.
  - Helps management make data-driven decisions.

## 11. Skills Demonstrated

- Data Analytics
- Business Intelligence
- Microsoft Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- KPI Development
- Data Visualization
- Business Analysis
- Analytical Thinking

## 12. Project Objective

To develop an interactive Power BI dashboard that transforms mobile sales data into meaningful business insights, helping businesses monitor revenue, analyze customer behavior, compare product performance and improve decision-making.

## 13. Project Information

Project Name: Mobile Sales Analysis Dashboard

Project Category: Data Analytics / Business Intelligence

Tool Used: Microsoft Power BI

Dataset: Mobile Sales Data

Project Type: Interactive Dashboard

# Screensort: https://github.com/ishagupta00096-ctrl/Sale-Report/blob/main/Sale_Dasboard.png
**Author:** Isha Gupta
