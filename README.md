# Chai Cafe Orders Analysis

Cleaning and analysis of one month of cafe orders (September 2026) using Python, pandas and matplotlib.

> **Note:** this is a practice dataset created for learning, not real business data.

## What I did
- Cleaned the data: converted dates, removed 4 duplicates, standardized branch names, and handled missing and impossible values
- Analysed revenue by branch, item, category and payment mode
- Checked age, ratings and daily trends
- Made bar and line charts

## Key findings
- **Total revenue: 37,215.** Bandra earns the most (16,400, about 44%).
- **A higher price can beat a higher quantity.** Cold Coffee earns the most (8,520) from only 71 units, while Cutting Chai sold 97 units but earns the least (1,455).
- **UPI is the most popular payment mode:** 54% of orders and 52% of revenue.
- **No clear pattern** by age, rating or weekday.

## Data cleaning notes
4 duplicate rows removed (304 to 300). Two impossible quantities and one impossible age set to blank. One price of 3000 corrected to 30. Six blank payment modes labelled "Unknown". 18 blank ratings left as they are, so the average rating uses 282 ratings.

## Files
- `Chai_Cafe_Analysis.ipynb`: the full notebook
- `chai_cafe_orders.csv`: the data

## How to run
Open the notebook in Google Colab, upload `chai_cafe_orders.csv`, and click Runtime, then Run all.
