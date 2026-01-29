# E-commerce-Sales-Data-Analysis

## Project Overview
This project analyzes e-commerce transaction data to understand sales performance, customer purchasing behavior, and key revenue drivers.  
The workflow includes data cleaning, feature engineering, exploratory data analysis (EDA), and visualization using Python.  
The cleaned dataset is prepared for further dashboard creation using Power BI.

---

## Objectives
- Clean and preprocess raw e-commerce transaction data
- Calculate key business KPIs
- Analyze sales trends and customer behavior
- Visualize relationships between price, quantity, and revenue
- Generate actionable business insights

---

## Dataset Description
The dataset contains transactional-level e-commerce data with the following fields:

- `InvoiceNo` – Unique order identifier  
- `StockCode` – Product code  
- `Description` – Product description  
- `Quantity` – Number of items sold  
- `InvoiceDate` – Date and time of transaction  
- `UnitPrice` – Price per unit  
- `CustomerID` – Unique customer identifier  
- `Country` – Customer country  

### Engineered Feature:
- `Revenue = Quantity × UnitPrice`

---

## Data Cleaning & Preparation
The following steps were performed:
- Removed unnecessary index columns
- Handled missing values in critical fields
- Converted columns to correct data types
- Removed invalid quantity and price values
- Removed duplicate records
- Reset index for a clean data structure

---

## Key Performance Indicators (KPIs)
- **Total Revenue**
- **Total Orders**
- **Average Order Value (AOV)**

These KPIs provide a high-level view of overall business performance.

---

## Exploratory Data Analysis & Visualizations
The analysis includes:
- Revenue by Country
- Top Products by Revenue
- Price vs Quantity Relationship (Scatter Plot)
- Revenue Distribution
- Correlation Analysis (Heatmap)

### Key Insights:
- Revenue is primarily driven by sales volume rather than price
- The United Kingdom is the dominant market
- Revenue distribution is right-skewed, with few high-value transactions
- Customers show weak price sensitivity
- A small number of products contribute significantly to total revenue

---

## Business Recommendations
- Increase sales volume through bundles and promotions
- Focus inventory planning on top-performing products
- Retain high-value customers
- Apply cautious pricing strategies due to weak price sensitivity

---

## Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

