# Sales Data Analysis
This repository contains a Jupyter notebook (Sales_Analysis.ipynb) that demonstrates how to perform end-to-end sales data analysis using SQLite, Pandas, and Matplotlib. The analysis covers data modeling in SQLite, querying with SQL, data manipulation with Pandas, and visualizing results.

##  Requirements
- Python 3.7+
- Jupyter Notebook
- SQLite3
- pandas
- matplotlib
- os (standard library)

## Notebook Overview

1. Database Setup:
- Connects to sales_data.db using SQLite.
- Drops existing sales table (if any) and creates a new one.
- Inserts sample sales records spanning multiple dates, products, regions, quantities, and prices.

2. Data Extraction & Analysis:
- Executes SQL queries via sqlite3 to calculate:
  - Total quantity and revenue by product
  - Total revenue by region
  - Top-selling products by revenue
  - Daily revenue trend
- Reads query results into Pandas DataFrames for further inspection.

3. Visualization:
- Generates bar charts, pie charts, and line plots using Matplotlib.
- Saves all visualizations under the sales_charts/ folder.

4. Cleanup:
- Commits transactions and closes the database connection.

## Generating Charts

All charts are automatically saved to the sales_charts directory when you run the notebook. Example files:
- revenue_by_product.png
- revenue_by_region.png
- sales_trend_over_time.png


