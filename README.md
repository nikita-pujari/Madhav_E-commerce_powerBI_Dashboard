# Madhav_E-commerce_powerBI_Dashboard

A 2-page Power BI dashboard that analyses sales and profit for an e-commerce dataset of 1,500 records.

## Screenshots

![Executive Summary](screenshots/page1.png)
![Product and Profit Analysis](screenshots/page2.png)

## Business Problem

An e-commerce business has sales data spread across states, categories, sub-categories and payment modes, but no clear picture of what is really driving its results. The questions it needs answered:

- Which states and products bring in the most sales, and which bring in the most profit?
- Why is the profit margin only 8.4%?
- In which months does the business lose money?
- How does profit change from one month to the next?

## Tools Used

- Power BI Desktop: data model, visuals and dashboard layout
- DAX: measures for Total Profit, Profit Margin %, AOV and Profit MoM %
- Excel: source data

## How I Solved It

1. Built a data model: I added a Calendar table linked to the order date, so month and quarter calculations work correctly.
2. Created KPI measures: Total Sales, Total Quantity, Total Profit, AOV, Profit Margin % and Profit MoM % give a quick health check of the business.
3. Page 1, Executive Summary: It shows top states, customers, category and payment mode split, monthly profit and top sub-categories by sales.
4. Page 2, Product & Profit Analysis: It compares sales with profit by sub-category, shows profit by category and state, and tracks the monthly trend with a zero line to spot loss months.
5. Added Quarter and State slicers, synced across both pages, so anyone can filter the whole report in one click.

## Key Findings

- Total sales ₹438K, total profit ₹37K, profit margin 8.4%
- Maharashtra leads in sales, but Madhya Pradesh earns the most profit
- Clothing has the best margin (9.2%) and Electronics the lowest (7.9%)
- Printers are the top profit sub-category (₹8.6K)
- Profit is uneven, with losses in May, July, September and December

## Files

- Madhav Ecommerce sales dashboard.pbix: open with Power BI Desktop
- Madhav Ecommerce sales dashboard.pdf: PDF of both pages
- screenshots/: dashboard images

## Author

[Your Name] | [LinkedIn link]
