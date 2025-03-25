# Chocolate Sales Analysis and Forecasting

## Overview
This project analyzes chocolate sales data from `Chocolate Sales.csv`, providing visualizations, trends, and a 6-month sales forecast using Prophet. It offers insights for inventory optimization, pricing strategies, and marketing campaigns, executed in a Kaggle environment.

## Functionality
1. **Preprocessing**:
   - Cleans `Amount` (removes '$', commas) and converts `Date` to datetime.
   - Adds `Unit Price` (Amount / Boxes Shipped).

2. **Exploratory Data Analysis**:
   - Visualizations: Sales by country, top products, monthly trends, sales vs. boxes shipped, sales by salesperson, purchase frequency, AOV, growth rates, seasonal patterns, market share.
   - Metrics: Correlation, top performers, averages.

3. **Forecasting**:
   - Uses Prophet to predict sales 6 months ahead.

4. **Business Insights**:
   - Inventory: Top products by sales and volume.
   - Pricing: Unit price distribution.
   - Marketing: Country sales and seasonal peaks.

## Frameworks and Libraries
- **Python**: Core language.
- **Pandas**: Data handling (`pd`).
- **NumPy**: Numerical ops (`np`).
- **Matplotlib**: Plots (`plt`).
- **Seaborn**: Visualization (`sns`).
- **Prophet**: Forecasting (`prophet`).

## Dataset
- Source: [Chocolate Sales](https://www.kaggle.com/datasets/<path-to-dataset>).
- Columns: `Date`, `Country`, `Product`, `Sales Person`, `Amount`, `Boxes Shipped`.
- Enhanced with `Unit Price` and `Month`.

## Key Features
- **Rich EDA**: Bar, line, scatter, heatmap, pie, and box plots.
- **Forecasting**: 6-month sales prediction with trend/seasonality breakdown.
- **Actionable Insights**: Supports inventory, pricing, and marketing decisions.
- **Visual Appeal**: Consistent, professional plotting style.

## Installation
```bash
pip install prophet matplotlib seaborn
