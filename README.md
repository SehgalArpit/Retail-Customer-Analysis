# Retail Customer Analysis

This repository contains the analysis and insights derived from a retail customer dataset, where data is merged and processed to derive valuable insights for business intelligence. The data provided is divided into three primary categories: Customers, Transactions, and Product Hierarchy, which are merged to create a comprehensive analysis.

## Overview

The primary objective of this analysis is to merge and clean the data to create useful metrics and reports that can help retail managers make informed decisions about customers, product preferences, store performance, and sales. This analysis covers several aspects such as customer demographics, sales by category, and store performance.

## Files & Data

The dataset used for this analysis includes three key sheets:

1. **Customer**: Information about customers including demographics such as age, gender, location, etc.
2. **Transaction**: Transaction details such as transaction date, amount, product purchased, etc.
3. **Product Hierarchy**: Details about products such as category, sub-category, and product information.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook (optional for visualization)
- Other required Python libraries can be installed using `requirements.txt`

## Steps & Tasks

The analysis follows a structured workflow that includes the following tasks:

### 1. Data Merging
- Merge the `Customer`, `Product Hierarchy`, and `Transaction` datasets into a new dataset called `Customer_Final`. Ensure that all customers who have made transactions are included.

### 2. Summary Report
- **Get column names and data types**.
- **Top/Bottom 10 Observations**: Display the first and last 10 rows of the dataset.
- **Five-number Summary**: Provide the min, Q1, median, Q3, and max for continuous variables.
- **Frequency Tables**: Generate frequency distributions for all categorical variables.

### 3. Data Visualizations
- Generate histograms for all continuous variables.
- Generate frequency bars for all categorical variables.

### 4. Business Metrics Calculation
- **Transaction Data Period**: Calculate the time range of the available transaction data.
- **Negative Transactions Count**: Count the number of transactions with a negative amount.

### 5. Gender-based Product Analysis
- Identify product categories that are more popular among female versus male customers.

### 6. City-based Customer Analysis
- Identify which city has the most customers and calculate the percentage of customers from that city.

### 7. Store Performance Analysis
- Determine which store type sells the maximum number of products by value and quantity.

### 8. Category-based Earnings from Flagship Stores
- Calculate the total earnings from the "Electronics" and "Clothing" categories for Flagship Stores.

### 9. Earnings from Male Customers in Electronics Category
- Calculate the total amount earned from male customers under the "Electronics" category.

### 10. High-Transaction Customers
- Identify customers who have more than 10 unique transactions after removing all transactions with negative amounts.

### 11. Specific Customer Group Analysis (Aged 25-35)
- For customers aged between 25-35:
  - Calculate the total amount spent on “Electronics” and “Books” product categories.
  - Calculate the total amount spent between 1st Jan 2014 to 1st Mar 2014.

## How to Run

1. Clone this repository using `git clone <repo-url>`.
2. Install the required libraries using:

   ```bash
   pip install -r requirements.txt

## Contact Information

For any queries or clarifications, you can reach out via email:

**Email**: arpitsehgal987@gmail.com
