# Sales Summary with SQLite, Python, and Matplotlib

This project demonstrates how to create a basic sales summary report using a small SQLite database and Python. The goal was to pull simple sales data, such as total quantity sold and total revenue by product, and visualize the results with multiple types of charts.

## What was done

- Created a SQLite database (`sales_data.db`) with a `sales` table containing sample product sales data.
- Used Python's `sqlite3` library to connect to the database and execute SQL queries.
- Queried total quantity sold and total revenue for each product using SQL `GROUP BY`.
- Loaded SQL query results into pandas DataFrames for easier data manipulation.
- Printed sales summaries in tabular form.
- Visualized data with various matplotlib charts:
  - Bar chart showing revenue by product.
  - Bar chart showing average price per product.
  - Scatter plot displaying the quantity sold per product for each sale record.
- Installed and configured matplotlib correctly to display and save charts without errors.
- Saved the main revenue bar chart as `sales_chart.png`.
- Managed database connection lifecycle properly (open-before, close-after queries).

## How to run

1. Ensure Python and required packages (`pandas`, `matplotlib`, `sqlite3`) are installed.
2. Run the Python script or Jupyter notebook that:
   - Creates and populates the SQLite database (only once).
   - Executes SQL queries for sales summary, averages, and quantities.
   - Prints query outputs.
   - Generates and shows multiple visualizations.
3. View the printed summaries and chart images generated during execution.

---

This extended workflow offers beginners a practical example of combining SQL querying inside Python with versatile visualizations to analyze sales data comprehensively and clearly.
