# Olist Data Cleaning using Python

## Overview

This notebook focuses on cleaning and preparing the Olist Brazilian E-Commerce dataset for analysis. The goal is to make the data structured, consistent, and ready for SQL-based analysis.

---

## Dataset

The dataset contains information about Brazilian e-commerce orders, customers, products, sellers, payments, reviews, and geolocation data.

---

## Objective

To clean, validate, and prepare the datasets while preserving meaningful information for further SQL-based analysis.

---

## Data Cleaning Steps

- Audited dataset structure, including rows, columns, missing values, and duplicates
- Validated missing values to determine whether they required correction or preservation
- Checked duplicate records and important identifier columns
- Removed exact duplicate geolocation records
- Created a ZIP-level geolocation lookup table for efficient joins
- Validated relationships between related datasets
- Converted date and timestamp columns to the appropriate datetime format
- Preserved meaningful missing values instead of removing valid records
- Exported the prepared datasets as CSV files for SQL analysis

---

## Outcome

The datasets were validated, cleaned, and standardized while preserving meaningful missing information. A derived geolocation lookup was also created, and the prepared datasets are ready for SQL-based analysis.

---

## Tools Used

- Python
- Pandas
- Jupyter Notebook

---

## Next Step

The prepared datasets will be loaded into MySQL for SQL-based analysis of customers, orders, products, sellers, payments, reviews, delivery performance, and other e-commerce trends.
