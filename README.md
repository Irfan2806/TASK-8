# 🧾 Simple Sales Dashboard Design (Power BI)

## 📊 Project Overview
This project presents an **interactive Power BI dashboard** that visualizes Superstore sales performance by **region**, **category**, and **month**.  
The goal is to provide quick insights into sales trends, top-performing regions, and product categories.

---

## 🧰 Tools & Dataset
- **Tool Used:** Power BI Desktop  
- **Dataset:** `Superstore_Sales.csv`  
  *(Columns: Order Date, Region, Category, Sales, Profit)*

---

## 🪜 Steps to Recreate

### 1. Import Data
1. Open Power BI Desktop.  
2. Navigate to **Home → Get Data → Text/CSV**.  
3. Load the dataset `Superstore_Sales.csv`.

---

### 2. Data Transformation
- Convert the `Order Date` field to **Month-Year** format using:
  ```DAX
  MonthYear = FORMAT('Superstore_Sales'[Order Date], "MMM-YYYY")
