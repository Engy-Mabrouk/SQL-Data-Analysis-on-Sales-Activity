# Northwind Sales Activity and Cutomer Behaviour Analysis

## Overview

Welcome to the **Northwind Sales Activity Analysis** project! This project delves into the sales activity of the Northwind dataset using SQL Lite, providing valuable insights into customer behavior, product performance, order trends, and employee efficiency. The findings from this analysis can help businesses enhance their sales strategies and improve customer relationships.

## Table of Contents

- [Project Description](#project-description)
- [Data Source](#data-source)
- [Analysis Methodology](#analysis-methodology)
  - [Customer Segmentation](#customer-segmentation)
  - [Product Analysis](#product-analysis)
  - [Order Analysis](#order-analysis)
  - [Employee Performance](#employee-performance)
- [Results](#results)
- [Visualization](#visualization)
- [PDF Report](#pdf-report)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Description

This project aims to analyze the sales activity data from the Northwind dataset to uncover insights about customer segmentation, product performance, order trends, and employee performance. By leveraging SQL queries, we can categorize customers, evaluate product sales, analyze order patterns, and assess employee efficiency.

## Data Source

The Northwind dataset is a sample database provided by Microsoft, commonly used for demonstrating database management systems. It contains data related to customers, orders, products, and employees.

## Analysis Methodology

### Customer Segmentation

1. **RFM Analysis**:
   - **Recency**: Days since the last order.
   - **Frequency**: Total number of orders.
   - **Monetary Value**: Total amount spent (revenue).

   **Customer Segments Created**:
   - **Champions**: Customers who bought most recently, most often, and spent the most.
   - **Potential Loyalists**: Customers who buy most frequently or spend the most.
   - **At Risk**: Customers who do not fit into the above categories.

2. **Order Value**:
   - Categorized customers into High-Value, Medium-Value, and Low-Value based on their average order revenue.

### Product Analysis

1. **High Revenue Value**: Identified the top 10 revenue-generating products.
2. **High Sales Volume**: Determined the top 10 most frequently ordered products.
3. **Slow Movers**: Identified 5 products with low sales volume.

### Order Analysis

1. **Seasonality**: Identified seasonal fluctuations in order volume.
2. **Day-of-the-Week Analysis**: Determined the most popular order days.
3. **Order Size Analysis**: Analyzed the distribution of order quantities.

### Employee Performance

Evaluated employee performance based on:
- Total Revenue Generated.
- Total Sales Volume (Number of orders processed).
- Average Order Value.

## Results

The analysis revealed significant insights into customer behavior, product performance, and employee efficiency. Detailed findings can be found in the exported Excel files and the comprehensive PDF report.

## Visualization

Results from the analysis have been visualized and exported to Excel for easy interpretation. This includes charts and graphs that illustrate key trends and patterns.

## PDF Report

A comprehensive report summarizing the findings from the SQL queries has been created. The report includes:
1. All SQL queries and detailed explanations of the results.
2. Graphs generated to explain the results visually.
3. Discussion of the business implications of the findings, including how the Northwind company can use this information to improve sales and customer relationships.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/northwind-sales-analysis.git
