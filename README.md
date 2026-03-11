# Sales Forecasting for Retail Stores

## Project Overview

This project focuses on predicting future retail sales using historical store sales data. Sales forecasting helps retailers manage inventory efficiently and avoid problems such as overstocking or understocking.

## Dataset

The dataset used in this project is **sales.csv**, which contains aggregated daily sales information.

**Columns:**

* `date` – Sales date
* `item_id` – Unique product identifier
* `quantity` – Quantity sold per day
* `price_base` – Average price per day
* `sum_total` – Total daily sales amount
* `store_id` – Store identifier

## Project Workflow

1. Data Loading and Inspection
2. Data Preprocessing

   * Convert date column to datetime
   * Handle missing values
   * Sort data by date
3. Exploratory Data Analysis (EDA)

   * Visualize sales trends over time
4. Feature Engineering

   * Day of week
   * Month
   * Lag features (previous sales)
   * Rolling average sales
5. Model Building

   * Train a regression model to predict sales
6. Sales Forecasting

   * Predict sales for the next 30 days

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Results

The model predicts future sales based on historical trends and engineered time-series features. The forecast helps estimate upcoming demand for better retail planning.

## Author

Rithanya K T K

