Repository Name: Chocolate-Sales-Analysis-and-Forecasting
Description:
This repository contains a comprehensive suite of Python scripts designed to analyze and derive actionable insights from chocolate sales data (Chocolate Sales.csv). Built for Jupyter Notebook or Kaggle environments, the code leverages libraries like pandas, matplotlib, seaborn, prophet, and statsmodels to perform exploratory data analysis, forecasting, and strategic decision-making. The dataset includes columns such as Sales Person, Country, Product, Date, Amount, and Boxes Shipped, which are used to uncover trends and optimize business operations.
Key Features:
Data Visualizations:
Bar, line, scatter, and heatmap plots to visualize sales by country, product, and time.

Examples: Total sales by country, top products by sales, monthly sales trends.

Sales Forecasting:
Implements Prophet for time series forecasting of future sales (6 months ahead).

Alternative ARIMA model as a fallback for simpler environments.

Visualizes historical data, forecasts, and seasonality components.

Customer Behavior Analysis:
Analyzes purchase frequency, average order value (AOV), and product preferences by country.

Visualizations include heatmaps of product sales by region and correlation plots of sales vs. boxes shipped.

Market Trend Identification:
Identifies growth rates by country, product popularity trends, and seasonal patterns.

Features pie charts for market share and dual-axis plots for sales vs. shipment volume.

Business Decision-Making:
Provides insights for inventory optimization (e.g., top products to stock), pricing strategies (e.g., unit price analysis), and marketing plans (e.g., targeting high-sales regions and peak months).

Includes actionable recommendations based on data-driven metrics.

Usage:
Environment: Designed for Jupyter Notebook or Kaggle; tested with Python 3.x.

Dependencies: Install via pip install pandas matplotlib seaborn prophet statsmodels.

Dataset: Assumes input file at /kaggle/input/chocolate-sales/Chocolate Sales.csv. Adjust file paths as needed.

Instructions: Run each script in a notebook cell. Start with visualization, then forecasting, and finally decision-making for a complete workflow.

Sample Insights:
Inventory: Prioritize stocking "Peanut Butter Cubes" in Australia.

Pricing: Test a price increase for "Mint Chip Choco" if unit price is low.

Marketing: Target India in July with promotions for "85% Dark Bars".

Notes:
Assumes data from 2022; multi-year data enhances trend accuracy.

Customizable: Adjust time granularity (e.g., weekly), filter by region/product, or add external factors (e.g., holidays).

