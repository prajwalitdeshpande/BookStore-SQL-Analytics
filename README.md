# BookStore-Management


A structured SQL analytics project to manage and derive insights from bookstore data. This project focuses on analyzing books, customers, and orders using optimized SQL queries to help drive inventory decisions, customer profiling, and revenue analysis.

---

## 🚀 Project Highlights

📦 **Inventory Insights**
- Filtered and tracked 400+ book records by genre, publication year, price, and stock level.
- Identified low-stock and high-value books to guide restocking and pricing strategy.

🧾 **Sales & Revenue Analysis**
- Analyzed monthly sales (e.g., November 2023) to detect peak order periods.
- Calculated total revenue, best-selling books, and genre-wise performance using SQL aggregations and joins.
- Derived stock movement and current availability using `LEFT JOIN` and `COALESCE`.

👥 **Customer Segmentation**
- Profiled customer behavior based on location (city/country), order frequency, and spending patterns.
- Identified top spenders and frequent buyers using grouped summaries with `HAVING` filters.

📊 **Trend Discovery**
- Found most frequently ordered books and top genres like "Fantasy" using advanced query logic.
- Mapped total quantity sold by each author—key for royalty and promotion decisions.

🌍 **Location-Based Insights**
- Discovered cities with high customer spending (e.g., >$30), useful for regional campaigns and delivery expansion.

✅ **Final Outcome**
Delivered a production-ready `.sql` solution file with **20+ business-focused queries** covering KPIs like:
- 📈 Revenue
- 🧠 Customer Value
- 📚 Inventory Turnover
- 🔄 Order Patterns

---

## 🧠 Tools & Skills Demonstrated

- **SQL Joins** (INNER, LEFT), **GROUP BY**, **HAVING**, **DISTINCT**, **ORDER BY**, **Aggregate Functions**
- Real-world data modeling: `Books`, `Customers`, `Orders`
- Scenario-driven problem solving for **business intelligence use cases**
- Clean, readable, and modular SQL scripts

----

## 📂 File Structure

- `Books data.sql` — Create and populate `Books` table
- `Customers data.sql` — Create and populate `Customers` table
- `Orders data.sql` — Create and populate `Orders` table
- `Solutions BookStore-Management.sql` — 20+ business queries and insights
- `Solutions BookStore-Management.pdf` — PDF version of the queries and analytics 
- `README.md` — Project documentation

---


