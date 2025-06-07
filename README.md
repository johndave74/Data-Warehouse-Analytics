# 📦 Data Warehouse Analytics – SQL Project

This project demonstrates advanced SQL analytics within a data warehouse environment. Using complex queries and analytical functions, we uncover insights related to revenue trends, warehouse performance, product sales rankings, and category-level sales patterns.

---

## 🚀 Project Overview

Modern organizations rely on data warehouses to aggregate, manage, and analyze business data from various sources. This project simulates a typical data warehouse scenario and performs analysis that supports decision-making for sales strategy, inventory management, and regional logistics.

---

## 🧱 Dataset Structure

This project assumes a table called `warehouse_sales` with the following schema:

| Column Name         | Data Type | Description                                |
|---------------------|-----------|--------------------------------------------|
| `product_id`        | VARCHAR   | Unique identifier for each product         |
| `part_category`     | VARCHAR   | Category or type of the product            |
| `warehouse_location`| VARCHAR   | Warehouse where the sale was recorded      |
| `sales_date`        | DATE      | Date of the sale                           |
| `revenue`           | NUMERIC   | Revenue generated from the sale            |
| `units_sold`        | INT       | Number of units sold                       |

---

## 🎯 Analytical Objectives

The SQL scripts in this repository answer the following business questions:

1. 📆 What is the **monthly revenue by warehouse**?
2. 🏆 Which products generate the **highest total revenue**?
3. 📦 How do **sales vary by product category and warehouse**?
4. 🔝 What are the **top 5 products by revenue** over the past year?
5. 📈 What are the **net revenue trends** over time?
6. 🏭 How do **warehouse performances compare** based on revenue contribution?

---

## 🛠️ SQL Techniques Used

This project showcases advanced SQL techniques such as:

- **Common Table Expressions (CTEs)**
- **Window Functions** (`RANK()`, `DENSE_RANK()`, `LAG()`)
- **Aggregate Functions** (`SUM()`, `ROUND()`)
- **Date Functions** (`DATE_TRUNC()`, `INTERVAL`)
- **Derived Tables & Subqueries**
- **Performance Comparisons and Ranking**

---

## 📁 Repository Structure

```

data-warehouse-analytics-sql/
│
├── scripts/
│   ├── 01\_monthly\_revenue\_by\_warehouse.sql
│   ├── 02\_top\_revenue\_products.sql
│   ├── 03\_category\_warehouse\_sales\_variation.sql
│   ├── 04\_top\_5\_products\_last\_year.sql
│   ├── 05\_revenue\_trends.sql
│   └── 06\_warehouse\_performance\_comparison.sql
│
├── sample\_data/
│   └── warehouse\_sales\_sample.csv
│
└── README.md

```

---

## 📌 How to Use

1. Load the `warehouse_sales_sample.csv` data into your SQL engine (PostgreSQL recommended).
2. Open each SQL file from the `/scripts/` folder and execute the queries.
3. Modify the queries as needed to match your local schema or database dialect.

---

## 📊 Insights You Can Derive

- Identify the most profitable warehouses by month.
- Highlight top-selling products and categories.
- Compare how each warehouse contributes to overall business revenue.
- Observe revenue growth, stagnation, or decline trends over time.

---

## 📈 Ideal Use Cases

- Data Analytics Portfolios
- SQL Interview Preparation
- Business Intelligence Demonstrations
- Dashboard Prototyping

---

## 🤝 Contributions

Feel free to fork, contribute, or open issues if you’d like to collaborate or extend the project. All feedback is welcome!

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## ⭐ Support

If you find this project helpful, please consider starring the repo! ⭐
