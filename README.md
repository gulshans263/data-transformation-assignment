# 🔍 SQL-Based Data Comparison Using Python

This project demonstrates how to use Python and SQL to compare two datasets (e.g., `old_table` and `new_table`) for:

- 🔄 Full row changes (added or removed rows)
- 🧬 Column-level differences (updated field values)

It is built using **Pandas** and **SQLite** for quick in-memory analysis but can be adapted to PostgreSQL, MySQL, or other databases.

---

## 📁 Project Structure


---

## 🚀 Features

- ✅ Load two versions of a dataset into SQL tables
- ✅ Detect rows that were **added** or **removed**
- ✅ Identify **column-level updates** using SQL JOINs
- ✅ Output two clean result tables:
  - `full_row_changes`: with `change_type` (`ADDED` / `REMOVED`)
  - `column_changes`: with `old_value`, `new_value`, and `column_name`

---

## Use Case Example

**Scenario**: You have two data snapshots — one before and one after — and need to identify:
- Which rows were added or deleted
- Which existing rows were modified at a column level

This is especially useful in:
- Data pipeline testing
- Regression analysis
- Version comparison
- Change tracking

---

## 📦 Requirements

- Python 3.7+
- pandas
- sqlite3 (built-in)

Install dependencies:

```bash
pip install pandas


🧼 Sales Data Cleaning & Transformation with Python

## 📌 Features

✅ Extract raw sales data from a CSV  
✅ Clean and convert data types (integers, floats, dates)  
✅ Fill missing values with defaults  
✅ Calculate `total_price = quantity * price_per_unit` using a UDF  
✅ Export the cleaned dataset to a new CSV file
