# Ecommerce.sales-Pandas_Project

# 🛍️ E-commerce Data Analysis using Pandas

This project involves data analysis on an e-commerce dataset using **Python and Pandas**. The goal is to extract insights such as category-wise filtering, high-value orders, and data export tasks like saving to CSV files.

---

## 📁 Dataset Used

- **File Name:** `ecommerce_data.csv`
- **Columns include:** Order ID, Product, Category, Price, Quantity, Total_Amount, Customer, City, Date, etc.

---

## 🔧 Technologies Used

- Python
- Pandas
- Jupyter Notebook

---

## 📌 Key Features / Tasks Done

- Read CSV file using `pandas.read_csv()`
- Filtered orders by category (e.g., Clothing)
- Extracted high-value orders (Total_Amount > 25000)
- Saved filtered data to CSV files
- Cleaned and explored data (like checking for missing values, types, etc.)

---

## 📤 Output Files

- `clothing_orders.csv` → Orders where Category = Clothing
- `high_value_orders.csv` → Orders where Total_Amount > 25000

---

## ▶️ How to Run

1. Clone the repo or download the `.ipynb` file.
2. Make sure `ecommerce_data.csv` is in the same folder.
3. Open Jupyter Notebook and run all cells.

```bash
pip install pandas
jupyter notebook
