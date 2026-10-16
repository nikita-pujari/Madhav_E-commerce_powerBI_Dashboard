# Madhav_E-commerce_powerBI_Dashboard

A 2-page Power BI dashboard that analyses sales and profit for an e-commerce dataset of 1,500 records.

## Screenshots
![Executive Summary](Dashboard%201.png)
![product and profit Analysis](Dashboard%202.png)

## Business Problem

An e-commerce business has sales data spread across states, categories, sub-categories and payment modes, but no clear picture of what is really driving its results. The questions it needs answered:

- Which states and products bring in the most sales, and which bring in the most profit?
- Why is the profit margin only 8.4%?
- In which months does the business lose money?
- How does profit change from one month to the next?

 ## Data Source

The data comes from two Excel files:

- Orders.xlsx (500 orders): Order ID, Order Date, Customer Name, State, City
- Details.xlsx (1,500 order lines): Order ID, Amount (sales), Profit, Quantity, Category, Sub-Category, Payment Mode

The two tables are linked using Order ID, with one order having many order lines. The dataset was already cleaned (no missing values or duplicate rows) and is used for learning and portfolio purposes. 

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

  ## Recommendations

1. Investigate the loss months (May, July, September, December):  Check discounts, shipping costs and product mix to find what pushed profit below zero.
2. Review pricing and discounts on low-margin products:  Electronics has the lowest margin (7.9%).
3. Replicate what works in Madhya Pradesh: It earns the most profit (₹7.4K) even though Maharashtra has higher sales (₹102K).
4. Promote high-profit sub-categories: Printers (₹8.6K) and Bookcases (₹6.5K) lead on profit.
5. Learn from November: It was the best month (₹10.3K profit), so find out what drove it.


## Files
- Orders.xlsx and Details.xlsx: source data
- Madhav_E-commerce_sales_dashboard.pbix: open with Power BI Desktop
- Madhav_E-commerce_sales_dashboard.pdf: PDF of both pages
- Dashboard 1.png and Dashboard 2.png: dashboard screenshots
