# Sales Data Dashboard — SoftGrowTech Internship (Task 1, Project 1)

## Overview
Analyzes sales data and generates a 4-panel dashboard: monthly revenue trend,
revenue by product, revenue share by region, and top 5 sales days. Also
prints key business insights to the console.

## Tools Used
- Python
- pandas
- matplotlib

## How to Run
```bash
pip install pandas matplotlib
python sales_dashboard.py
```
If `sales_data.csv` isn't present, the script auto-generates a sample dataset.

## Dataset Columns
| Column   | Description                  |
|----------|-------------------------------|
| Date     | Order date                    |
| Region   | North / South / East / West   |
| Product  | Widget A–E                    |
| Quantity | Units sold                    |
| Revenue  | Total revenue for the order   |

## Output
- `sales_dashboard.png` — the 4-panel dashboard image
- Console output — key insights (total revenue, best month, top product, top region)

## Benefits
Builds business analysis skills: interpreting sales trends, identifying
top performers, and translating data into decisions.

