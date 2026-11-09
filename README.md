# Sales Dashboard

## Problem Statement
Management needs one view of revenue, profit and growth to decide where to focus sales effort.

## Dataset
Any sales data with columns: order_id, order_date, region, category, product, units, revenue, cost (your own, a company export, or a Kaggle retail sales dataset).
Save it as `data/sales.csv`. If the file is missing, `analysis.py` generates **demo data** with the same columns so you can test the code. Demo data is only for testing. Do not publish its numbers as real findings.

## Business Questions
- What are total revenue, profit, margin, orders and AOV?
- How do revenue and profit trend month over month and year over year?
- Which regions and products drive the business?

## Tools
Python (pandas, matplotlib, seaborn), then Power BI / Tableau using `output/kpi_monthly.csv`

## How to Run
```bash
pip install -r ../requirements.txt
python analysis.py
```
Outputs: charts in `images/`, CSV summaries in `output/` (ready to import into Power BI / Tableau), key numbers printed in the terminal.

## Results
![overview](images/sales_dashboard.png)

## Key Findings
> Run the script on the **real dataset**, then replace these lines with your own numbers.
- Finding 1: ...
- Finding 2: ...
- Finding 3: ...

## Recommendations
1. ...
2. ...
3. ...

## Project Structure
```
generate_data.py   # demo data with the real schema (for testing)
analysis.py        # cleaning, analysis, charts, summaries
data/              # put the real CSV here
images/            # generated charts
output/            # generated summary CSVs
```
