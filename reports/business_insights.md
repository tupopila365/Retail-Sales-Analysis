# Retail Sales Analysis — Business Insights

## 1. Purpose

Analyse sample retail sales data to identify patterns in revenue, profit, product performance, and regional performance. This report uses the completed Excel KPI summary and the current Power BI dashboard. Findings are descriptive and preliminary.

## 2. KPI overview

| KPI | Value | Interpretation |
| --- | ---: | --- |
| Total sales | 2,326,534.35 | Total recorded sales revenue |
| Total profit | 292,296.81 | Sum of recorded profit and losses |
| Total quantity | 38,654 | Product units sold |
| Profit margin | 12.56% | Total profit divided by total sales |
| Average sales per row | 228.23 | Average of the Sales column, **not** average order value |
| Unique orders | Approximately 5K | Rounded Power BI card; verify exact count |

**Validation check:** `292,296.8146 / 2,326,534.354 ≈ 12.56%`.

Currency is unspecified in the supplied screenshots. The dataset represents sample data, and the displayed monthly timeline extends through 2026; do not present the results as verified real-world financial performance.

## 3. Preliminary findings

### Regional performance

**Observation:** West has the highest total sales in the dashboard, followed by East. South shows the lowest total sales.

**Business implication:** Investigate what explains higher sales in West and East (e.g., order volume, product mix, average order value), rather than assuming demand alone causes the difference.



### Product-category profitability

**Observation:** Technology generates the highest total profit, followed by Office Supplies. Furniture generates much less total profit.

**Business implication:** Compare category profit margins and discounts before making pricing or stock recommendations. Low total profit does not necessarily mean every product in the category is unprofitable.

**Next check:** Identify profitable and loss-making products within Furniture.

### Top-selling products

**Observation:** Canon imageCLASS 2200 Advanced Copier appears to lead the Top 10 Products by Sales chart.

**Business implication:** Identify whether the ranking is driven by high unit prices or high quantities, and check the product's profit contribution.

**Next check:** Rank products by profit and compare with revenue ranking.

### Monthly sales trends

**Observation:** Monthly sales fluctuate, with a pronounced peak near the end of the 2023–2026 period shown in the dashboard.

**Business implication:** Seasonal effects are a hypothesis, not yet a proven finding. Test whether peaks repeat across years and whether order counts or average order values explain them.

**Next check:** Calculate month-over-month and year-over-year changes for comparable complete months.



## 4. Data limitations

- This is a **sample dataset**, not an audited report of an actual retailer.
- Source dataset URL and redistribution permissions still need to be recorded.
- Unique orders are only available as the rounded `5K` card in the screenshot; the exact total needs confirmation.
- The results shown here are from the unfiltered dashboard view supplied during the project.
- Some observations are visual estimates; exact group totals should be exported or queried before publication.
- Causation, seasonality, and pricing effects have not been established.


