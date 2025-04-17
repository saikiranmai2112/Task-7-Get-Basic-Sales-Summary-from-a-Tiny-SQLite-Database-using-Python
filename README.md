# Task-7-Get-Basic-Sales-Summary-from-a-Tiny-SQLite-Database-using-Python

This project demonstrates how to connect Python to an SQLite database, run SQL queries, summarize sales data, and visualize the results using pandas and matplotlib.

🚀 Task Objective

Get a basic sales summary from a small SQLite database using Python.

📁 Project Files

sales_summary.ipynb — Main Python script to create the database, insert data, run queries, and display results.

sales_data.db — SQLite database file.

sales_chart.png — Bar chart showing revenue by product.

README.md — You’re reading it!

🧠 What This Script Does

Creates a SQLite database with a sales table

Inserts sample product sales data

Runs an SQL query to calculate:

Total quantity sold per product

Total revenue per product

Displays the results using print()

Visualizes revenue with a bar chart (using matplotlib)

🔧 Technologies Used

Python 🐍

SQLite (via sqlite3)

pandas

matplotlib

📌 Sample Output (Printed Table)

        product  total_qty  revenue
0        Apples         50     25.0
1       Bananas         85     25.5
2      Cherries         55     55.0
3         Dates         10     15.0
4  Elderberries          5     10.0

📉 Bar Chart Example

 - Sales chart
