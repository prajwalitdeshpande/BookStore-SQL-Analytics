# BookStore-Management

🗂️ Queried and filtered 400+ book records by genre, publication year, stock, and price to support inventory decisions.

🌍 Segmented customer base across countries and cities (e.g., Canada), enabling localized marketing opportunities.

🕒 Analyzed monthly order activity (e.g., November 2023) to identify peak periods for demand forecasting.

📦 Tracked total book stock and flagged low-stock titles to assist in restocking and supply chain planning.

💰 Identified highest revenue-generating and most expensive books for pricing and promotional strategies.

🧾 Evaluated order volume by quantity and amount, surfacing high-value and bulk order trends.

📚 Profiled genre-level sales with total books sold, supporting curated recommendations and genre-based marketing.

📉 Detected lowest-performing stock using `ORDER BY stock LIMIT 1` logic to reduce dead inventory.

🧠 Found top customers and frequent buyers using aggregate joins and `HAVING` clauses to boost loyalty programs.

🔁 Highlighted the most frequently ordered book and top fantasy books for trend-based merchandising.

👤 Mapped customer spending behavior (e.g., $30+ spenders and top spender), informing high-LTV customer targeting.

📈 Summarized sales by genre, author, and customer, building a foundation for dashboards and author-level analytics.

📉 Calculated real-time stock balance post-orders using `LEFT JOIN` + `COALESCE`, enabling accurate inventory snapshots.


