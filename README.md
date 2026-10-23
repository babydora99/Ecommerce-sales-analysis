# E-commerce Sales Analysis and Business Intelligence Dashboard

## Project Overview

This project analyzes retail sales data using Python and Microsoft Power BI to understand sales performance, profitability, product categories, and customer segments.

The project includes data cleaning, exploratory data analysis (EDA), data visualization, and an interactive Power BI dashboard. The objective is to transform raw sales data into meaningful business insights that can support data-driven decision-making.

## Objectives

- Inspect and clean the sales dataset.
- Analyze sales, profit, quantity, and discount information.
- Compare performance across product categories and sub-categories.
- Evaluate regional profitability and customer segment contributions.
- Build visualizations using Python.
- Develop an interactive Power BI dashboard.
- Identify business insights and recommend improvements.

## Technologies Used

- Python — data analysis and preprocessing
- Jupyter Notebook — interactive coding and analysis
- Pandas — data manipulation and aggregation
- NumPy — numerical operations
- Matplotlib — data visualization
- Seaborn — statistical visualization
- Microsoft Power BI Desktop — interactive dashboard
- Git and GitHub — version control and project hosting

## Dataset Description

The project uses a Sample Superstore retail sales dataset.

## Important columns include:

- Ship Mode
- Segment
- Country
- City
- State
- Postal Code
- Region
- Category
- Sub-Category
- Sales
- Quantity
- Discount
- Profit

The dataset does not contain an order-date column, so the analysis focuses on product, regional, customer-segment, and discount-related performance rather than time-based trends.

## Project Workflow

1. Data Loading: Imported the CSV dataset into a Pandas DataFrame.
2. Data Inspection: Examined column names, data types, missing values, duplicates, and summary statistics.
3. Data Cleaning: Checked data quality and prepared the dataset for analysis.
4. Exploratory Data Analysis: Summarized sales, profit, quantity, and discount information.
5. Data Visualization: Created charts to compare product categories, sub-categories, regions, customer segments, and discounts.
6. Dashboard Development: Built an interactive Power BI dashboard with KPI cards, charts, and filters.
7. Business Analysis: Interpreted the results and developed recommendations based on the observed data.

## Dashboard Features

The Power BI dashboard presents key business performance indicators, including:

- Total Sales
- Total Profit
- Total Quantity

The dashboard also supports comparisons such as:

- Sales by Category
- Profit by Region
- Sales by Customer Segment
- Sales by Sub-Category
- Discount versus Profit, where included

Interactive slicers allow users to explore selected categories, regions, and customer segments, depending on the final dashboard configuration.

## Business Insights

The analysis is designed to identify:

- Product categories contributing the most sales.
- Regional differences in profitability.
- Customer segments contributing to revenue.
- Sub-categories with comparatively high or low sales.
- Potential relationships between discounts and profit.

Specific findings should be reported using the actual values and rankings obtained from the analysis.

How to Run the Analysis

1. Clone or download this repository.

2. Install Python and Jupyter Notebook.

3. Install the required libraries:
   
   pip install pandas numpy matplotlib seaborn jupyter

4. Open Jupyter Notebook.

5. Open "sales_analysis.ipynb".

6. Ensure the dataset path in the notebook matches the location of your CSV file.

7. Run the notebook cells in order.

To view the dashboard, download "Superstore_Sales_Dashboard.pbix" and open it using Microsoft Power BI Desktop.

Learning Outcomes

This project provided practical experience in data cleaning, exploratory data analysis, data visualization, business intelligence, dashboard development, and project documentation. It also improved my understanding of how analytical results can be used to support business decisions.

Author

V Baby Dora

GitHub: "babydora99" (https://github.com/babydora99)

Tools and References

- Pandas: https://pandas.pydata.org/docs/
- NumPy: https://numpy.org/doc/
- Matplotlib: https://matplotlib.org/stable/
- Seaborn: https://seaborn.pydata.org/
- Power BI: https://learn.microsoft.com/power-bi/
