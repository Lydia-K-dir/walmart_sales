# Walmart Data Analysis: SQL + Python Project 

## Project Overview

This project is an end-to-end data analysis solution designed to extract critical business insights from Walmart sales data. I utilized Python for data processing and analysis, SQL for advanced querying, and structured problem-solving techniques to solve key business questions.

---

## Project Steps

### 1. Set Up the Environment
   - **Tools Used**: Visual Studio Code (VS Code), Python, SQL (MySQL and PostgreSQL)
   - **Goal**: I created a structured workspace within VS Code and organized project folders for smooth development and data handling.

### 2. Download Walmart Sales Data
   - **Data Source**: I used the Kaggle API to download the Walmart sales datasets from Kaggle.

### 3. I installed the following Required Libraries using bash and Loaded Data 
     pip install pandas numpy sqlalchemy mysql-connector-python psycopg2
     ```
   - **Loading Data**: This enabled me read the data into a Pandas DataFrame for initial analysis and transformations.

### 4. Explore the Data
   - **Goal**: Conduct an initial data exploration to understand data distribution, check column names, types, and identify potential issues.
   - **Analysis**: Use functions like `.info()`, `.describe()`, and `.head()` to get a quick overview of the data structure and statistics.

### 5. Data Cleaning
   - I identified and removed duplicate entries to avoid skewed results.
   - I dropped rows or columns with missing values if they are insignificant; fill values where essential.
   - I checked for any remaining inconsistencies and verify the cleaned data.

### 6. Feature Engineering
   - I calculated the `Total Amount` for each transaction by multiplying `unit_price` by `quantity` and adding this as a new column.

### 7. Load Data into MySQL
   - I connected to MySQL using `sqlalchemy` and load the cleaned data into each database.
   - I set up tables in both MySQL using Python SQLAlchemy to automate table creation and data insertion.
   - I run initial SQL queries to confirm that the data has been loaded accurately.

### 9. I answered the following business questions using SQL queries
   - **Business Problem-Solving**: Write and execute complex SQL queries to answer critical business questions, such as:
     - Revenue trends across branches and categories.
     - Identifying best-selling product categories.
     - Sales performance by time, city, and payment method.
     - Analyzing peak sales periods and customer buying patterns.
     - Profit margin analysis by branch and category.

---

## Requirements

- **Python 3.8+**
- **SQL Databases**: MySQL
- **Python Libraries**:
  - `pandas`, `numpy`, `sqlalchemy`, `mysql-connector-python`, `psycopg2`
- **Kaggle API Key** (for data downloading)

## Acknowledgments

- **Data Source**: Kaggle’s Walmart Sales Dataset
- **Inspiration**: Generation Ghana
-                  

---
