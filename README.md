# E-commerce Sales Analysis

## Objective
Analyze sales data to find which categories and regions drive profit, how sales trend over time, and how discounts affect profitability.

## Tools Used
Python, Pandas, NumPy, Matplotlib, Google Colab

## Steps
1. Data cleaning (removed duplicates, handled missing values)
2. Feature creation (month from order date)
3. Analysis using groupby (category, region, discount)
4. Visualization (bar and line charts)

## Key Findings & Insights

- Cleaned the dataset from 1,010 to 1,000 records by removing 10 duplicate rows.
- Handled 16 missing region values by replacing them with "Unknown".
- Grocery generated the highest total profit (179,561.61), followed closely by Furniture (178,618.05).
- Clothing recorded the lowest total profit (130,834.60).
- East was the most profitable region (195,773.57), while West recorded the lowest profit (113,887.38).
- Orders without discounts had the highest average profit (836.63).
- The 30% discount group recorded the lowest average profit (513.62).
- Monthly analysis showed fluctuations in sales and profit, with August recording the highest monthly sales (659,789.00).

## Recommendations

- Investigate opportunities to improve profitability in the West region.
- Review pricing and cost strategies for Clothing and Electronics.
- Evaluate discount policies to understand their impact on average profit.
- Monitor monthly sales and profit trends to support business decisions.

## Limitations

- The dataset is synthetically generated using NumPy and does not represent real business transactions.
- Findings are intended for learning and demonstration purposes.

