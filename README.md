# Superstore Sales Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a global superstore retail dataset containing four years of sales data. The goal is to analyze sales performance, identify patterns, and extract meaningful business insights that can help organizations make data-driven decisions.

The dataset includes information about orders, customers, products, regions, and sales values.

---

## Dataset Information

* **Total Records:** 9,800
* **Total Columns:** 18
* **Time Period:** 2015 – 2018

### Main Features in Dataset

* Order ID
* Order Date
* Ship Date
* Customer Name
* Segment
* Country
* City
* State
* Region
* Category
* Sub-Category
* Product Name
* Sales

---

## Objectives of the Analysis

The main objectives of this project are:

* Understand overall sales distribution
* Identify the best performing product categories
* Analyze regional sales performance
* Identify top selling products
* Discover the most profitable cities
* Understand customer segment contribution
* Identify yearly sales trends

---

## Tools and Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## Data Analysis Steps

### 1. Data Loading and Inspection

* Loaded dataset using Pandas
* Checked dataset structure using `.info()`
* Identified data types and missing values

### 2. Data Exploration

* Examined unique values in categorical columns
* Checked dataset shape and summary statistics

### 3. Category Wise Sales Analysis

Analyzed sales for the following product categories:

* Furniture
* Office Supplies
* Technology

### 4. Regional Sales Analysis

Compared sales across regions:

* Central
* East
* South
* West

### 5. Customer Segment Analysis

Analyzed sales contribution from:

* Consumer
* Corporate
* Home Office

### 6. Product Analysis

Identified top 10 products generating the highest revenue.

### 7. City Analysis

* Top 10 cities by sales
* Bottom 10 cities by sales

### 8. Sub-Category Analysis

Analyzed which product sub-categories contribute most to total sales.

### 9. Sales Trend Analysis

Examined yearly sales performance to understand growth trends.

### 10. Sales Distribution

Analyzed how sales values are distributed using histogram visualization.

---

## Key Insights

* **Technology** is the highest performing product category.
* **West region** generates the highest total sales.
* **New York City** is the top performing city in terms of sales.
* **Consumer segment** contributes the largest portion of revenue.
* **Phones** are the highest selling sub-category.
* Sales increased significantly from **2017 to 2018**.

---

## Visualizations Included

The project includes several visualizations:

* Category-wise sales bar chart
* Region-wise sales comparison
* Top selling products chart
* Yearly sales trend line plot
* Region vs category heatmap
* Top and bottom cities by sales
* Customer segment analysis chart
* Sub-category sales comparison
* Sales distribution histogram

---

## Project Structure

```
superstore-sales-analysis
│
├── Superstore_Sales_EDA_Project.ipynb
├── superstore_dataset.csv
└── README.md
```

---

## Conclusion

This project demonstrates how exploratory data analysis can help uncover valuable insights from retail sales data. The analysis highlights key revenue drivers, top performing regions, and customer purchasing behavior.

Such insights help businesses make informed decisions related to marketing strategy, inventory management, and customer targeting.

---

## Author

Abdul Qadoos
Aspiring Data Analyst
