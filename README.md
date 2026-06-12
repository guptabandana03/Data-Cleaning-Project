
# Data Cleaning & Preparation Project

## Overview

This project was completed as part of the DecodeLabs Data Analytics Internship Program.

The objective was to clean and prepare a raw e-commerce sales dataset by handling missing values, removing duplicates, correcting invalid entries, and standardizing data formats.

---

## Dataset

**Dataset:** Snitch Fashion Sales Dataset

### Columns

* Order_ID
* Customer_Name
* Product_Category
* Product_Name
* Units_Sold
* Unit_Price
* Discount_%
* Sales_Amount
* Order_Date
* City
* Segment
* Profit

---

## Tasks Performed

### Missing Value Handling

* Filled missing numerical values using Median Imputation
* Filled missing categorical values using Mode Imputation

### Duplicate Removal

* Removed duplicate records
* Verified zero duplicate Order_ID values

### Data Validation

* Corrected negative Units_Sold values
* Corrected negative Sales_Amount values
* Corrected invalid discount values

### Data Standardization

* Standardized city names
* Converted dates to YYYY-MM-DD format
* Cleaned text fields

---

## Final Validation

| Check                   | Result |
| ----------------------- | ------ |
| Missing Values          | 0      |
| Duplicate Rows          | 0      |
| Duplicate Order_ID      | 0      |
| Invalid Dates           | 0      |
| Negative Units_Sold     | 0      |
| Negative Sales_Amount   | 0      |
| Invalid Discount Values | 0      |

---

## Tools Used

* Python
* Pandas
* NumPy
* Google Colab

---

## Author

Bandana Gupta
B.Tech CSE | Aspiring Data Analyst
