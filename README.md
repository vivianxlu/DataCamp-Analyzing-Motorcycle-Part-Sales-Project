# DataCamp-Analyzing-Motorcycle-Part-Sales-Project

# 🏍️ Motorcycle Parts Sales Analysis – SQL DataLab Project

## 📖 Project Summary

This project is a guided SQL data analysis challenge set in a fictional company that sells motorcycle parts. The goal was to leverage SQL for analyzing sales data and supporting various departments—like Finance and Marketing—in making informed, data-driven decisions.

The analysis was performed in a Jupyter Notebook using PostgreSQL-style SQL queries to address practical business questions.

---

## ✅ What I Did

Over the course of this project, I:

- Explored a sales table containing transaction-level data from three warehouses.
- Wrote SQL queries to:
  - Filter data by client type (retail vs. wholesale).
  - Aggregate and group revenue by product line, month, and warehouse.
  - Calculate **net revenue** by subtracting payment fees from total sales.
  - Use **Common Table Expressions (CTEs)** and **window functions** (`RANK()`, `ROW_NUMBER()`) to identify top-performing products and payment methods.
- Tackled additional analytical challenges such as:
  - Ranking payment methods by profitability.
  - Identifying the most popular product lines for each client type.

---

## 🧠 What I Learned

This project helped me deepen my knowledge of:

- Writing efficient, readable SQL queries for business-focused analysis.
- Using aggregate functions (`SUM`, `COUNT`) and date functions (`TO_CHAR`, `EXTRACT`).
- Applying advanced window functions like `RANK()` and `ROW_NUMBER()`.
- Structuring complex queries using **CTEs** for better clarity and modularity.
- Translating business questions into actionable SQL queries.

---

## 📌 Tools & Technologies

- **Jupyter Notebook**
- **SQL** (PostgreSQL-style syntax)
- **Markdown** (for documentation and presentation)

---

## 📊 Dataset Overview

The analysis was performed on a `sales` table with the following key columns:

- `order_number`
- `date`
- `client_type`
- `product_line`
- `payment`
- `total`
- `payment_fee`
- `warehouse`

---

## 🏁 Final Notes

This project provided hands-on experience in using SQL not only to extract data but to **uncover insights, support decisions, and tell compelling business stories**. It served as a strong practical exercise in combining technical querying skills with analytical thinking.
