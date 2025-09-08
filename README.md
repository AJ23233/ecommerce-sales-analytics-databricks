# Databricks ETL Pipeline (E-Commerce Sales Analytics)

🚀 This project demonstrates an **end-to-end ETL pipeline** on **Databricks** using the **Medallion Architecture** (Bronze → Silver → Gold).

## 📂 Project Structure
- **Bronze Layer**: Ingest raw e-commerce sales CSV into Delta format.
- **Silver Layer**: Data cleaning, timestamp formatting, null handling, price-per-unit calculation.
- **Gold Layer**: Aggregations (Revenue per Category, Last Purchase Date).

## 🛠️ Tech Stack
- **Databricks (PySpark)**
- **Delta Lake**
- **SQL + Spark DataFrame API**

## 📊 Example Output
- Total Revenue by Category
- Last Invoice Date by Country
- Customer-Level KPIs

![ETL Flow](images/bronze_layer.png)

## 📎 Notebook Exports
- [View HTML Notebook](Ecommerce_ETL_Databricks.html)
- [Download PDF](Ecommerce_ETL_Databricks.pdf)

---
✨ Connect with me on [LinkedIn](your-linkedin-url) for more data engineering projects!
