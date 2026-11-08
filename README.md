## Project overview

## Power BI Dashboard

![Retail Sales Dashboard](images\dashretailpreview.png)

This portfolio project explores a sample retail sales dataset to understand sales performance, profitability, regional differences, product performance, and changes in revenue over time.

## Business questions
- How much revenue and profit did the store generate?
- Which regions and product categories perform best?
- Which products generate the most sales?
- How does sales performance change by month?

## Tools and skills
Python (Pandas)	Inspect and clean transaction data; export a cleaned CSV
Excel	KPI calculations, PivotTables, and sales exploration
Power BI	Data modeling, DAX measures, and dashboard visualizations
SQL Server	Planned: queries to validate and extend the analysis


## KPI summary
The table below reflects figures from the Excel workbook and Power BI dashboard. Values have been rounded for display.
Metric	Result
Total sales	2,326,534.35
Total profit	292,296.81
Total quantity sold	38,654
Profit margin	12.56%
Average sales per transaction row	228.23
Unique orders	Approximately 5,000 (Power BI card rounds to 5K; exact number to be verified)


Important: The reporting currency has not been verified. These figures are from a sample dataset, not confirmed financial results for a real business. The chart spans 2023–2026, including simulated dates.

## Dashboard insights (preliminary)
- Regional sales: West has the highest sales, followed by East; South is lowest in the dashboard view.
- Category profitability: Technology contributes the most total profit; Furniture contributes the least.
- Top products: The Canon imageCLASS 2200 Advanced Copier appears as the highest-sales product in the Top 10 Products chart.
- Monthly trends: Sales fluctuate substantially, with a prominent peak late in the displayed period.
These are observations from the visuals, not evidence of causation. See [`reports/business_insights.md`](reports/business_insights.md) for details, limitations, and follow-up analyses.
Repository structure
retail-sales-analysis/
├── data/
│   ├── superstore_raw.csv
│   └── superstore_clean.csv
├── python/
│   └── clean_data.ipynb
├── excel/
│   └── sales_exploration.xlsx
├── powerbi/
│   └── sales_dashboard.pbix     
├── images/
│   └── dashboard_overview.png
├── sql/
│   └── sales_analysis.sql      
├── reports/
│   └── business_insights.md
├── requirements.txt
├── .gitignore
└── README.md


## How to reproduce the Python cleaning
1. Install Python and open this repository in VS Code.
2. Create and activate a virtual environment (recommended).
3. Run pip install -r requirements.txt.
4. Open python/clean_data.ipynb and run the cells in order.


5. If the notebook uses a relative path such as data/superstore_raw.csv, make sure the notebook's working directory is the project root. Confirm with Path.cwd().
6. Check the row counts, date parsing, duplicate handling, and missing-value results before using data/superstore_clean.csv.
The Excel workbook can be opened in Microsoft Excel. 
Dataset and provenance
Dataset: Sample Superstore 


## Skills demonstrated
Data cleaning · CSV and Excel analysis · Power Query · DAX · KPI development · Power BI data visualization · Business reporting · Data quality checks

