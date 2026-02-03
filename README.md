# 🛒 Superstore Sales Data Analysis using Python (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Superstore Sales dataset using **Python, Pandas, and Matplotlib** to uncover meaningful business insights from retail sales data.

The objective of this project is to clean raw data, perform grouping and aggregation, analyze sales trends across categories and regions, and visualize patterns that support business decision-making.

---

## 📂 Dataset Information

The dataset contains retail transaction records with the following important fields:

- Order Date
- Category and Sub-Category
- Region, State, City
- Product Name
- Sales Amount

---

## 🧹 Data Cleaning & Preparation

- Handled **date format issues** using `dayfirst=True`
- Removed duplicates and checked missing values
- Converted dates for **time-series analysis**
- Prepared structured data for aggregation and visualization

---

## 📊 Visual Analysis & Insights

### 🔹 Total Sales by Category

<img width="597" height="545" alt="Bar Chart" src="https://github.com/user-attachments/assets/c6ada698-b935-4314-a71e-163e8e2c44a0" />


- **Technology** category generates the highest sales.
- Followed by **Furniture** and **Office Supplies**.
- Indicates strong customer demand for tech-related products.

---

### 🔹 Top 10 Sub-Categories by Sales

<img width="604" height="508" alt="Bar Chart 2" src="https://github.com/user-attachments/assets/d1eb9804-81e9-4118-89fd-9c80d1c87920" />


- **Phones** and **Chairs** are the highest revenue-generating sub-categories.
- Shows concentration of sales around specific product types.

---

### 🔹 Sales Distribution (Histogram)

<img width="580" height="455" alt="Histogram" src="https://github.com/user-attachments/assets/7544056f-dbac-4120-b49c-9317ea02f57e" />


- Sales data shows a **right-skewed distribution**.
- Most transactions are low-value, while few high-value orders contribute heavily to total sales.

---

### 🔹 Monthly Sales Trend (Time-Series)

<img width="597" height="471" alt="Line Chart" src="https://github.com/user-attachments/assets/328e90cf-f896-4b80-9e54-731c77970fff" />


- Clear fluctuations in monthly sales.
- Indicates **seasonality** and peak sales periods across years.

---

### 🔹 Sales Distribution by Region (Pie Chart)

<img width="389" height="411" alt="Pie Chart" src="https://github.com/user-attachments/assets/edd566a2-7cd5-4d3b-b483-994d39b3bd5a" />

- **West** region contributes the highest share (~31%).
- Followed by **East**, **Central**, and **South**.
- Highlights geographical demand concentration.

---

## 🔍 Key Business Insights

- Technology products dominate overall revenue.
- Phones and Chairs are key drivers of sales performance.
- Certain regions and states contribute disproportionately to sales.
- Monthly trends reveal seasonal purchasing behavior.
- Sales distribution confirms dependency on few high-value orders.

---

## 💼 Business Implications

- Helps in **inventory planning** for high-demand categories.
- Supports **regional marketing and targeting strategies**.
- Useful for **seasonal forecasting** and stock management.
- Dataset is ready for **Power BI dashboard development**.

---

## 🛠️ Tools & Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---
👤 Author
Abhishek Dhole
Aspiring Data Analyst | Python | SQL | Power BI
