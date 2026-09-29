# Farmatting-PowerBI
Sales Performance Dashboard – Power BI

Project Overview

This project focuses on importing, cleaning, analyzing, and visualizing sales data using Microsoft Power BI. The goal is to create a polished and interactive dashboard that provides a clear overview of sales performance, order volume, product categories, and regional performance.

Objective

To apply Power BI data import, data cleaning, DAX measures, visualization, formatting, and interactive filtering techniques to build an executive-style sales dashboard.

Dataset

Source: Excel sales dataset

File: Power_Query_Raw_Sales_200_Rows(1).xlsx

Raw records: 200

Fields: Order ID, Order Date, Customer Name, Product, Category, Region, Salesperson, Quantity, Unit Price, Discount, Payment Mode, City, Sales Amount

Data Cleaning

The dataset was cleaned using Power Query.

Corrected column data types.

Removed duplicate rows.

Trimmed and cleaned text fields.

Standardized text capitalization for Region, Product, Category, City, and Payment Mode.

Handled missing Discount values.

Replaced missing Salesperson and Payment Mode values with Unknown.

Kept missing Order Date and Sales Amount values blank where the original data was unavailable.

Standardized Discount values so percentage values are represented consistently as decimals.

Converted Sales Amount into a numeric format suitable for analysis.

DAX Measures

Total Sales = SUM(sales_data[Sales_Amount])

Total Orders = DISTINCTCOUNT(sales_data[Order_ID])

Total Quantity = SUM(sales_data[Quantity])

Average Order Value = DIVIDE([Total Sales], [Total Orders])

Dashboard Components

KPI Cards

Total Sales

Total Orders

Total Quantity

Average Order Value

Visualizations

Sales by Category – Clustered bar chart

Monthly Sales Trend – Line chart

Sales by Region – Column chart

Interactive Filters

Region slicer

Category slicer

Payment Mode slicer

The slicers allow users to filter the dashboard dynamically and explore different parts of the sales data.

Dashboard Design

The dashboard was designed with an executive-friendly layout:

Dashboard title and subtitle

KPI cards

Interactive slicers

Sales category analysis

Monthly sales trend

Regional sales analysis

Consistent formatting, spacing, alignment, titles, axis labels, data labels, and tooltips were applied to improve readability.

Business Questions Addressed

What is the total sales generated?

How many orders were placed?

How many units were sold?

What is the average order value?

Which product categories generate higher sales?

How does sales performance change over time?

How do sales compare across regions?

How does performance change when filtering by region, category, or payment mode?

Tools Used

Microsoft Power BI Desktop

Power Query

DAX

Microsoft Excel

Project Outcome

The final Power BI dashboard provides an interactive summary of sales performance and allows users to explore the data using slicers. The project demonstrates practical skills in data preparation, DAX calculations, visualization, and dashboard design.

Files

Power_Query_Raw_Sales_200_Rows(1).xlsx – Raw source dataset

Sales Performance Dashboard.pbix – Final Power BI report

Dashboard screenshot – Final dashboard preview

Skills Demonstrated

Data Import

Data Cleaning

Power Query

Data Type Management

Duplicate Handling

Missing Value Handling

DAX Measures

KPI Development

Data Visualization

Interactive Slicers

Dashboard Formatting

Business Data Analysis
