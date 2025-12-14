# Zepto E-Commerce SQL Project

## Project Overview

This project is an SQL-based data analysis case study built on an e-commerce dataset inspired by Zepto. The goal of the project is to demonstrate end-to-end SQL skills including database creation, data exploration, data cleaning, and business-focused data analysis.

The analysis focuses on understanding product pricing, discounts, inventory availability, revenue estimation, and category-level insights. This project is suitable for showcasing practical SQL knowledge required for data analyst roles.

---

## Database Details

* Database Name: sql_project
* Table Name: zepto
* Domain: E-Commerce / Retail Analytics

### Table Schema

The zepto table contains product-level information related to pricing, discounts, stock status, and inventory details.

| Column Name            | Description                              |
| ---------------------- | ---------------------------------------- |
| sku_id                 | Unique identifier for each product       |
| category               | Product category                         |
| name                   | Product name                             |
| mrp                    | Maximum Retail Price (in rupees)         |
| discountPercent        | Discount percentage applied              |
| availableQuantity      | Available inventory quantity             |
| discountedSellingPrice | Selling price after discount (in rupees) |
| weightInGms            | Product weight in grams                  |
| outOfStock             | Stock availability status                |
| quantity               | Quantity per SKU                         |

---

## Data Exploration

Initial data exploration was performed to understand the structure and quality of the dataset. This included:

* Counting total records in the table
* Viewing sample records
* Identifying null values across columns
* Listing distinct product categories
* Analyzing in-stock versus out-of-stock products
* Detecting products with multiple SKUs under the same name

---

## Data Cleaning

To improve data quality and ensure accurate analysis, the following cleaning steps were applied:

* Removed products where MRP or selling price was equal to zero
* Converted price values from paise to rupees
* Verified cleaned price columns for consistency

These steps helped standardize the dataset and eliminate invalid records.

---

## Data Analysis and Business Questions

The following analytical queries were written to answer practical business questions:

1. Identified the top 10 best-value products based on highest discount percentage.
2. Found high-MRP products that are currently out of stock.
3. Calculated estimated revenue for each product category using discounted price and available quantity.
4. Extracted products with MRP greater than 500 and discount below 10 percent.
5. Determined the top five categories offering the highest average discount.
6. Calculated price per gram for products above 100 grams to identify best-value options.
7. Categorized products into Low, Medium, and Bulk based on weight.
8. Computed total inventory weight per category.

---

## Tools and Technologies Used

* SQL (MySQL-compatible syntax)
* Relational Database Concepts
* Data Cleaning and Aggregation Techniques

---

## Key Learnings

* Creating and managing relational database tables
* Writing analytical SQL queries using joins, aggregations, and conditional logic
* Translating business requirements into SQL-based insights
* Performing pricing, discount, and inventory analysis for e-commerce data

---

## How to Use This Project

1. Create a database named sql_project.
2. Run the table creation script.
3. Import the dataset into the zepto table.
4. Execute the exploration, cleaning, and analysis queries sequentially.

---

## Project Title

Zepto E-Commerce SQL Project: Data Exploration, Cleaning, and Business Analysis

---

## Author

Aspiring Data Analyst with hands-on experience in SQL-based data analysis and business insights.

---

## Conclusion

This project demonstrates practical SQL skills applied to a real-world e-commerce use case. It highlights the ability to clean data, perform structured analysis, and derive meaningful insights that support business decision-making.
