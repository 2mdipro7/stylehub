# Case Study: Optimizing Inventory Management for StyleHub

# Table of Contents
1. [Background](#background)
2. [Problem Statement](#problem-statement)
3. [Objective](#objective)
4. [Data Overview](#data-overview)
    - 4.1. [Customer Data](#customer-data)
    - 4.2. [Product Data](#product-data)
    - 4.3. [Inventory Data](#inventory-data)
    - 4.4. [Sales Data](#sales-data)
5. [Methodology](#methodology)
6. [Results and Insights](#results-and-insights)
7. [Conclusion](#conclusion)

## Background

StyleHub, a medium-sized retail fashion store with a strong presence both online and in physical outlets, faces significant challenges in inventory management. The store's inventory dynamics have been fluctuating, resulting in frequent overstock and stockout situations. These issues have led to lost sales opportunities and increased holding costs, adversely affecting the store's profitability and operational efficiency.

## Problem Statement

The core challenge for StyleHub lies in achieving an optimized inventory level that aligns with fluctuating demand patterns. The store's management system needs to be capable of accurately predicting demand across multiple sales channels, both online and offline. StyleHub's goal is to minimize instances of overstock and stockouts, thereby reducing unnecessary costs and maximizing sales opportunities.

## Objective

The objective of this case study is to develop a data-driven approach for StyleHub's inventory management. By leveraging sales, product, customer, and inventory data, the aim is to build an analytical framework that can:

- Accurately forecast product demand.
- Optimize stock levels in accordance with predicted demand.
- Provide insights into customer purchasing behavior.
- Identify trends and patterns in sales data to inform inventory decisions.

## Data Overview

Since we do not have real world data, we will use synthetic data carefully prepared to simulate realistic market trends. You can find the data generation process right below.

[![Synthetic Data Generation](https://img.shields.io/badge/Data%20Generation-yellow?logo=Google-Colab)](https://colab.research.google.com/drive/1EHGjwo323nD9McHyVJi-u0EdfYW2I_ub?usp=sharing)

The case study utilizes four primary datasets to conduct a comprehensive analysis of StyleHub's inventory management. Each dataset plays a crucial role in understanding different facets of the business operations:

### Customer Data
- **Customer ID**: A unique identifier assigned to each customer.
- **Age**: The age of the customer.
- **Gender**: The gender of the customer, with possible values including 'Male', 'Female', and 'Other'.
- **Location**: The geographical location of the customer, categorized as 'Urban', 'Suburban', or 'Rural'.

This dataset provides insights into the customer demographics that StyleHub serves, essential for understanding purchasing patterns and preferences.

### Product Data
- **Product ID**: A unique identifier for each product in StyleHub's inventory.
- **Product Category**: The category of the product, which includes a range of categories like 'Electronics', 'Clothing', 'Home & Kitchen', 'Toys', and 'Books'.
- **Initial Stock Level**: The quantity of the product available at the start of the observation period.
- **Reorder Point**: The inventory level at which a new order is triggered to replenish the stock.
- **Lead Time (days)**: The time it takes, in days, from placing a product order to its arrival in the inventory.

This dataset is crucial for analyzing the inventory composition and determining the stock management strategy for different product types.

### Inventory Data
- **Product ID**: Corresponds to the Product ID in the Product Data, uniquely identifying each product.
- **Historical Stock Levels**: Records of stock levels for each product over a historical period, providing a day-by-day inventory count.

The inventory data is instrumental in understanding the stock flow dynamics and identifying patterns in stock levels over time.

### Sales Data
- **Date**: The date on which each sales transaction occurred.
- **Product ID**: The identifier for the product being sold, corresponding to the Product ID in the Product Data.
- **Product Category**: The category of the sold product.
- **Quantity Sold**: The number of units of the product sold in each transaction.
- **Sales Channel**: The channel through which the sale was made, categorized as either 'Online' or 'Offline'.
- **Price**: The sale price of the product.
- **Customer ID**: The identifier of the customer who made the purchase, linking back to the Customer ID in the Customer Data.

The sales dataset provides a detailed account of every transaction, essential for understanding sales trends, customer buying behavior, and product performance.

---

These datasets form the backbone of the analysis and are used to create a comprehensive data model in Power BI, enabling a detailed exploration of inventory management strategies.

## Methodology

The methodology adopted for this case study involves a series of structured steps aimed at transforming raw data into actionable insights. Utilizing Power BI as the primary analytical tool, the approach encompasses data segmentation, feature engineering through DAX (Data Analysis Expressions), and the development of interactive dashboards. The key steps in the methodology include:

1. **Data Import and Initial Assessment**:
   - Importing the Customer, Product, Inventory, and Sales datasets into Power BI.
   - Conducting an initial review of the data to understand its structure, quality, and potential areas of interest.

2. **Data Segmentation and Feature Engineering Using DAX**:
   - Employing DAX to create new calculated columns and measures that segment the data into more meaningful categories and metrics.
   - Examples of segmentation include categorizing customers by age group, classifying products based on sales velocity, and segmenting sales data by time periods and channels.
   - Feature engineering through DAX allows for the creation of new data points such as stock turnover rates, profitability metrics, and customer purchasing patterns.

3. **Exploratory Data Analysis (EDA)**:
   - Using Power BI visuals to explore relationships, patterns, and trends in the data.
   - Identifying key drivers of inventory inefficiencies, such as products prone to stockouts or overstock.

4. **Demand Forecasting and Inventory Optimization**:
   - Analyzing sales trends to forecast future demand for different product categories.
   - Correlating sales forecasts with inventory data to identify optimal reorder points and stock levels.

5. **Dashboard Development**:
   - Designing and creating interactive Power BI dashboards that provide real-time insights into inventory status, sales performance, and customer demographics.
   - Ensuring that dashboards are user-friendly and offer drill-down capabilities for detailed analysis.

6. **Insights and Recommendations**:
   - Drawing conclusions from the analysis and providing actionable recommendations for optimizing inventory levels.
   - Highlighting opportunities for improving demand forecasting and inventory replenishment strategies.

The application of DAX for data segmentation and feature engineering is central to this methodology, enabling a deeper and more nuanced analysis of StyleHub's inventory management system. By transforming the raw datasets into a series of interconnected insights, the case study aims to deliver a comprehensive solution to the challenges faced by StyleHub.

---

*Throughout this case study, a keen focus is maintained on ensuring data accuracy, relevancy, and consistency, which are critical for drawing reliable conclusions and making informed business decisions.*


## Results and Insights

*Upcoming in the next update*

## Conclusion

This case study provides StyleHub with actionable insights and a robust framework for inventory management, addressing the critical challenges of overstocking and stockouts, and paving the way for enhanced operational efficiency and cost-effectiveness.

---

**Note**: The datasets and analyses are for demonstration purposes and do not contain real customer data.

---
