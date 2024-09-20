# Power BI 'AdventureWorks' Sales Performance Dashboard

## Overview

This repository contains a Power BI project that analyzes and visualizes sales performance data for a fictional bike retail company. The dashboard provides insights into sales trends, top-performing products, and regional performance, helping stakeholders and executives to make data-driven decisions.

![MavenMarket_exec](https://github.com/user-attachments/assets/f690d097-9fe8-4551-b69a-82c4b783a7f8)


## Features

* Topline Performance: A high-level view of total revenue, number of transactions, and return trends with additional product category detail.
  
* Regional Sales: Geographical analysis showing order performance across different regions and countries.
*	Product Performance: Insights into product revenue, order and profit margins. Adjustable product metric charts over time.
*	Customer Insights: Analysis of customer demographics, buying patterns, and revenue value.
*	Year-over-year and month-over-month sales comparison to track growth.

## 📁 Files in the Repository

*	<a href="https://github.com/Polyee99/MavenMarket_grocery_store_dashboard/blob/main/Maven%20Market%20Dashboard_2024_09.pbix">Maven Market Dashboard_2024_09.pbix</a> - The Power BI file containing the data model and dashboard.
  
* <a href="https://github.com/Polyee99/MavenMarket_grocery_store_dashboard/tree/main/Maven%2BMarket%2BCSV%2BFiles">Maven+Market+CSV+Files</a> - Raw data used for the analysis, including customer details, regoonal, store and product information with a subfolder for sales transactions.
* <a href="https://github.com/Polyee99/MavenMarket_grocery_store_dashboard/blob/main/Maven_Market.png">Maven_Market.png</a> - Image used for grocery logo.

## 📊 Data Sources 

The data used in this project comes from the attached csv files:

*	Transaction Data: Contains details of sales transactions, including product/customer keys and quantity.
  
*	Return Data: Includes date of return and different foreign keys related to products.
*	Lookup Data: Information about customers, products, calendar and regional details.

## 📋 Requirements

*	Power BI Desktop (latest version)
  
*	Microsoft Excel (for reviewing raw data)
*	Basic understanding of DAX and Power BI visuals

## ▶️ Getting Started

To run this Power BI project locally:

1. Clone the repository:
```
git clone https://github.com/Polyee99/MavenMarket_grocery_store_dashboard.git
```
3. Open the <a href="https://github.com/Polyee99/MavenMarket_grocery_store_dashboard/blob/main/Maven%20Market%20Dashboard_2024_09.pbix">Maven Market Dashboard_2024_09.pbix</a> file in Power BI Desktop.

4. Ensure that the data source paths are correct. If needed, modify the data connections in the Transform Data tab to point to the correct file locations.

5. Refresh the data to load the latest data from sales_data.xlsx.

6. Explore the dashboard and interact with the visualizations.

## ⚙️Dashboard Walkthrough

### Topline Performance:
*	Total revenue, profit, sales, and return rate.
*	Monthly KPIs for Transaction, Profit and Returns.
*	Product detail table with additional metrics like brand, transaction, profit, margin and return rate.
*	Map visualization showing sales in stores by state and city.
*	Treemap to show proportion of total visible regions. 
*	Weekly Revenue on a timeline comparison.
*	Breakdown of product revenue vs target on a gauge chart.

## 🚀 Project Methodology

1. Data Cleaning: The raw data was cleaned using Power BI's Power Query Editor, ensuring that all records are complete and formatted properly.
2. Data Modeling: Relationships were created between sales, customers, and product tables to allow for effective slicing and dicing of the data.
3. DAX Calculations: Custom measures were created using DAX (Data Analysis Expressions) to compute KPIs like total revenue, profit margin, and average customer value.
4. Visualization: Multiple Power BI visualizations were used, including bar charts, line graphs, maps, and tables to represent different facets of the data.
