# Real-world-Online-Retail-sales-analysis-using-R

## Project Overview

This project analyzes real-world online retail transactions using R.

The main objective is to transform transaction data into meaningful business insights using data visualization.

A reproducible sample of 60,000 transaction records from the UCI Online Retail dataset was used.

## R Script

Main script:

'_retail_visualization.R`

The script performs:

- Dataset import
- Sales calculation
- Date transformation
- Monthly sales analysis
- Product revenue analysis
- Country sales analysis
- Weekday sales analysis
- Quantity distribution analysis
- Sales vs quantity analysis
- Cancellation analysis
- Customer revenue analysis

## Dataset Source

UCI Machine Learning Repository - Online Retail Dataset.

The original dataset contains transactional data from a UK-based online retailer.

Important variables include:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

A new Sales variable is calculated as:

Sales = Quantity × UnitPrice

## Usage

Place:

`Online_Retail_60k_Sample.csv`

inside the project folder.

Run the R script:

source("week2_retail_visualization.R")

## Required R Packages

Install the required packages using:

install.packages("dplyr")
install.packages("ggplot2")

Load them using:

library(dplyr)
library(ggplot2)

## Important Output Charts

1. Monthly Sales Trend
2. Top 10 Products by Revenue
3. Top 10 Countries by Sales
4. Sales by Day of Week
5. Purchase Quantity Distribution
6. Sales vs Purchase Quantity
7. Completed vs Cancelled Transactions
8. Top 10 Customers by Revenue

## Expected Results

The analysis should show that:

- The United Kingdom generates the majority of sales.
- November 2011 is the strongest complete sales month in the sample.
- A small number of products contribute substantial revenue.
- Tuesday and Thursday show strong sales activity.
- Most transactions involve relatively small quantities.
- Completed transactions greatly outnumber cancelled transactions.
- A small group of customers contributes a significant amount of revenue.

## Author

Suhas D
