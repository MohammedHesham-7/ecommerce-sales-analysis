# ecommerce-sales-analysis# 🛒 E-Commerce Sales Data Analysis & Cleaning

## 📌 Project Overview
This project focuses on cleaning, processing, and analyzing an e-commerce dataset containing customer order details. The goal is to handle missing values, correct data types, and prepare the dataset for exploratory data analysis (EDA) and insights generation.

---

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, DateTime

---

## 🔍 Key Data Processing Steps
1. **Data Cleaning:**
   - Stripped unnecessary white spaces and standardizing text formats.
   - Handled missing values (`NaN`) across key columns using median imputation and data filtering.
2. **Data Type Conversion:**
   - Converted `order_date` to `datetime` format.
   - Converted numerical features (`quantity`, `price`) to appropriate numeric types (`Int64`, `float`).
3. **Group-based Imputation:**
   - Filled missing price values based on product-specific median pricing.

---

## 📊 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/MohammedHesham-7/ecommerce-sales-analysis.git](https://github.com/MohammedHesham-7/ecommerce-sales-analysis.git)
End-to-End Data Analysis project using Python &amp; Pandas
