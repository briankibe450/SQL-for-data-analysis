# SQL-for-data-analysis
SQL (Structured Query Language) is a powerful tool for data analysis, particularly when working with structured data in relational databases. You can use SQL to retrieve, transform, summarize, and analyze data. Here are some common SQL queries and techniques for data analysis:

1. **Data Retrieval**:
   - **SELECT**: Retrieve data from one or more tables.
     ```sql
     SELECT * FROM employees;
     ```

2. **Filtering Data**:
   - **WHERE**: Filter data based on specified conditions.
     ```sql
     SELECT * FROM sales WHERE date >= '2023-01-01';
     ```

3. **Aggregation**:
   - **GROUP BY**: Group data for summary statistics.
     ```sql
     SELECT department, AVG(salary) FROM employees GROUP BY department;
     ```
   - **SUM, COUNT, AVG, MAX, MIN**: Calculate aggregate values.
     ```sql
     SELECT COUNT(*) FROM orders;
     ```

4. **Sorting**:
   - **ORDER BY**: Sort data in ascending or descending order.
     ```sql
     SELECT product_name, price FROM products ORDER BY price DESC;
     ```

