# E-Commerce Sales Dashboard

An end-to-end data analytics project using PostgreSQL, SQL, and Power BI to analyze e-commerce sales performance, product trends, and seller performance.

## Project Overview

This project analyzes the Brazilian E-Commerce Public Dataset (Olist) to identify sales trends, evaluate product performance, and understand seller contributions through an interactive Power BI dashboard.

## Tools & Technologies

- **PostgreSQL** – Database management and data storage
- **SQL** – Data cleaning, transformation, validation, and analysis
- **Power BI** – Interactive dashboards and visualizations
- **DAX** – Measures and business calculations
- **DBeaver** – SQL development and database management

## Project Workflow

1. **Data Import:** Imported nine raw CSV datasets into PostgreSQL.
2. **Data Profiling:** Examined data quality, missing values, duplicates, and distributions.
3. **Data Cleaning:** Standardized data types, handled missing values, and cleaned text fields.
4. **Data Modeling:** Designed a star schema with fact and dimension tables.
5. **SQL Analysis:** Created analytical views for sales, products, sellers, payments, and reviews.
6. **Dashboard Development:** Built interactive Power BI dashboards using DAX measures and slicers.

## Dashboard Pages

### 1. Executive Overview
- Total Sales Value
- Total Orders
- Total Product Revenue
- Average Order Value
- Monthly Sales Trend
- Orders by Status
- Top 10 States by Sales

### 2. Product Performance
- Total Products
- Units Sold
- Product Revenue
- Revenue by Product Category
- Top 10 Products by Revenue
- Units Sold by Product Category

### 3. Seller Performance
- Total Sellers
- Total Orders
- Seller Revenue
- Top 10 Sellers by Revenue
- Seller Revenue by State
- Top 10 Sellers by Orders

## Key Business Metrics

| Metric | Value |
|---|---:|
| Total Sales Records | 112,650 |
| Total Orders (with items) | 98,666 |
| Total Products | 32,951 |
| Total Sellers | 3,095 |
| Product Revenue | R$13,591,643.70 |
| Total Freight | R$2,251,909.54 |
| Total Sales Value | R$15,843,553.24 |

## Database Design

The project uses a star schema consisting of:

**Fact Table**
- `fact_sales`

**Dimension Tables**
- `dim_customers`
- `dim_products`
- `dim_sellers`
- `dim_date`
- `dim_orders`

Additional SQL analytical views were created for monthly sales, product performance, seller performance, payment analysis, and review analysis.

## Repository Structure

```text
Sales-Performance-Dashboard/
├── SQL/
├── Screenshots/
├── Sales_Performance_Dashboard.pbix
└── README.md
```

## Dataset

**Source:** [Brazilian E-Commerce Public Dataset by Olist – Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The dataset contains approximately 100,000 orders from a Brazilian e-commerce platform, covering multiple aspects of its operations.

## Skills Demonstrated

- SQL querying and data transformation
- Data cleaning and validation
- Relational database design
- Star schema and dimensional modeling
- Data analysis and business metrics
- Power BI dashboard development
- DAX calculations and interactive reporting

---

**Project Type:** Data Analytics & Business Intelligence
