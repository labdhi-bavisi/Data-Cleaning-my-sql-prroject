# 🧹 SQL Data Cleaning Project – Layoffs Dataset

## 📌 Description
This project demonstrates a complete data cleaning process using **MySQL** on a real-world layoffs dataset. The goal is to transform messy, inconsistent data into a clean, analysis-ready format using pure SQL techniques.

---

## 🛠️ Tools & Technologies
- MySQL
- SQL Window Functions
- CTEs (Common Table Expressions)

---

## 📊 Key Cleaning Steps
- Removed duplicates using `ROW_NUMBER()` and CTE
- Trimmed whitespaces and standardized text entries (e.g., company, industry, country)
- Cleaned inconsistent values (like 'Crypto%' → 'Crypto')
- Converted date strings to proper `DATE` format
- Handled NULLs and empty values appropriately
- Replaced missing industry values using self-joins
- Dropped unnecessary helper columns

---

## ✅ Output
A clean and structured version of the layoffs dataset ready for analysis, visualization, or reporting.







