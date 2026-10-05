# E-Commerce Sales Data Cleaning

## Project Overview

Cleaning and preprocessing an e-commerce sales dataset to make it suitable for Machine Learning.

## Data Cleaning & Preprocessing

* Removed duplicate records.
* Handled missing values.
* Reviewed and handled invalid values and potential outliers.
* Converted `Order_Date` to datetime format.
* Cleaned and standardized text features.
* Corrected an invalid `Sales_EGP` value based on `Quantity × Unit_Price_EGP`.
* Analyzed sales by category.
* Applied One-Hot Encoding to selected categorical features.
* Prepared the cleaned dataset for Machine Learning.

## Files

* `data/ecommerce_sales_clean.csv` — Cleaned dataset.
* `code/clean_sales_data.py` — Python code used for cleaning and preprocessing.

## Notes

The original data was preserved as much as possible, and data modifications were limited to values that required cleaning or correction.
