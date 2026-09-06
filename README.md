# Sales Database Exploration

This project involves exploring and analyzing the `sales` database using SQL queries. The database contains multiple tables related to customers, products, markets, dates, and transactions. Below is a summary of the queries executed and their purpose.

---

## 📂 Database Tables Queried
1. **sales.customers**
   - Query: `SELECT * FROM sales.customers LIMIT 0, 1000`
   - Result: 38 rows returned
   - Purpose: Retrieve customer information.

2. **sales.date**
   - Query: `SELECT * FROM sales.date LIMIT 0, 1000`
   - Result: 1000 rows returned
   - Purpose: Explore date dimension for transaction analysis.

3. **sales.markets**
   - Query: `SELECT * FROM sales.markets LIMIT 0, 1000`
   - Result: 17 rows returned
   - Purpose: Understand available markets and regions.

4. **sales.products**
   - Query: `SELECT * FROM sales.products LIMIT 0, 1000`
   - Result: 279 rows returned
   - Purpose: Retrieve product catalog details.

5. **sales.transactions**
   - Query: `SELECT * FROM sales.transactions LIMIT 0, 1000`
   - Result: 1000 rows returned
   - Purpose: Access transaction records for analysis.

---

## 🔎 Filtered Queries
- **Transactions in USD**
  ```sql
  SELECT * FROM sales.transactions WHERE currency = "USD" LIMIT 0, 1000;
