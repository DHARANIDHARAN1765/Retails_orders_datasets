# 📊 Retail Orders Data Analysis | End-to-End Python + SQL Server Project

## 📖 Project Overview

This project demonstrates an **End-to-End Retail Orders Data Analysis** workflow using **Python, Pandas, SQL Server, SQLAlchemy, and Jupyter Notebook**.

The project starts by downloading the dataset from **Kaggle** using the **Kaggle API**. The dataset is then loaded into **Python**, where data cleaning, preprocessing, feature engineering, and exploratory data analysis (EDA) are performed using **Pandas**.

After preparing the dataset, it is loaded into **SQL Server** using **SQLAlchemy** and **PyODBC**. Finally, multiple real-world business problems are solved using SQL queries involving aggregations, window functions, CTEs, ranking functions, and date functions to extract meaningful business insights.

---

# 🐍 Python (Jupyter Notebook) Workflow

The following tasks were completed in the Jupyter Notebook:

- Downloaded the Retail Orders dataset using the **Kaggle API**.
- Imported the dataset into a **Pandas DataFrame**.
- Performed Exploratory Data Analysis (EDA).
- Inspected the dataset using:
  - `head()`
  - `info()`
  - `describe()`
  - `shape`
  - `columns`
- Removed duplicate records.
- Handled missing values.
- Renamed column names.
- Cleaned currency symbols from price columns.
- Converted data types.
- Formatted date columns.
- Created new calculated columns:
  - Unit Selling Price
  - Unit Profit
  - Total Selling Price
  - Total Profit
- Validated the cleaned dataset.
- Connected Python to SQL Server using **SQLAlchemy** and **PyODBC**.
- Loaded the cleaned dataset into SQL Server using **Pandas `to_sql()`**.

---

# 🗄️ SQL Server Workflow

After loading the cleaned data into SQL Server, business problems were solved using SQL.

The SQL analysis includes:

- Data Retrieval using `SELECT`
- Data Filtering using `WHERE`
- Removing duplicate values using `DISTINCT`
- Data Aggregation using:
  - `SUM()`
  - `AVG()`
  - `COUNT()`
  - `MIN()`
  - `MAX()`
- Data Grouping using `GROUP BY`
- Sorting results using `ORDER BY`
- Conditional Logic using `CASE WHEN`
- Data Type Conversion using `CAST()`
- Numeric Formatting using `ROUND()`
- Date Functions:
  - `YEAR()`
  - `MONTH()`
  - `FORMAT()`
- Window Functions:
  - `ROW_NUMBER()`
  - `RANK()`
  - `DENSE_RANK()`
- Common Table Expressions (CTEs)
- Month-over-Month Sales Analysis
- Product Performance Analysis
- Regional Sales Analysis
- Revenue & Profit Analysis
- Category & Sub-Category Analysis

---

# 📈 Business Problems Solved

- List all distinct cities where orders have been shipped.
- Calculate the total selling price and total profit for every order.
- Find Technology category orders shipped using Second Class.
- Calculate the Average Order Value (AOV).
- Find the city with the highest quantity of products ordered.
- Rank orders within each region by quantity sold.
- Retrieve all orders placed during the first quarter (January–March).
- Identify the Top 10 highest profit-generating products.
- Find the Top 3 highest-selling products in each region.
- Compare Month-over-Month sales growth between 2022 and 2023.
- Find the highest sales month for each product category.
- Identify the sub-category with the highest sales growth from 2022 to 2023.

---

# 💡 Skills Demonstrated

- Python
- Pandas
- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- SQL Server
- SQL Query Writing
- Window Functions
- Common Table Expressions (CTEs)
- SQLAlchemy
- PyODBC
- Business Analytics
- ETL Process
- Git & GitHub
