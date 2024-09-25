# Superstore Sales Analysis Project

## Overview
This project aims to analyze the Superstore dataset to gain insights into sales performance, customer behavior, and product trends. The dataset contains records of orders from a fictional retail store, including information about products, customers, and their respective sales transactions. The analysis involves various stages, including data cleaning, feature engineering, and model training to predict sales.

## Dataset Columns
The dataset consists of the following columns:

- **Order ID**: Unique identifier for each order.
- **Order Date**: The date when the order was placed.
- **Ship Date**: The date when the order was shipped.
- **Sales**: Total sales amount for the order.
- **Quantity**: Number of items sold.
- **Discount**: Discount applied to the order.
- **Profit**: Profit earned from the order.
- **Category**: Category to which the product belongs (e.g., Furniture, Office Supplies, Technology).
- **Sub-Category**: More specific classification under each category.
- **Region**: Geographical region where the order was delivered.
- **Customer ID**: Unique identifier for each customer.

## Methodology
The following steps were taken during the analysis:

- **Data Preprocessing**: The dataset was cleaned by handling missing values and converting data types for further analysis.
- **Feature Engineering**: New features were created, including time-based features (month, day, year) and lag features to capture trends over time.
- **Sales Prediction**: Machine learning models, including linear regression, CatBoost, and Random Forest, were employed to predict future sales based on historical data.
- **Visualization**: Visual representations were created to illustrate sales distributions and trends, such as histograms and time series plots.
- **Insights Generation**: The analysis drew insights to support decision-making regarding sales strategies and marketing campaigns.

### Note on Model Limitations
Due to the diverse range of products, prices, and categories within the dataset, the predictive accuracy of the models may be limited. This analysis serves as an example of applying machine learning techniques to sales data, despite potential shortcomings in model performance.
