# Basic Data Sorting & Filtering

Sort and filter a raw sales dataset to answer 5 business questions — practicing basic data exploration in Excel/Google Sheets without altering the source data.

## What's inside

| File | Description |
|---|---|
| `Data_Sorting_Filtering_Exercise.xlsx` | The workbook — see tab breakdown below. |


## Workbook tabs

- **Q&A Summary** — all 5 questions and their answers in one place.
- **Sales Data** — the raw dataset (3,000 order line items), completely unchanged.
- **Q1–Q5** — one tab per question. Each tab has Excel's native AutoFilter applied with the stated criteria, sorted on the relevant column, with non-matching rows hidden (not deleted).

## The 5 questions

1. Which single order had the highest profit in the West region?
2. Which Consumer-segment orders had a discount of 20% or more?
3. What are the 5 highest-revenue Technology orders shipped Same Day?
4. Which Furniture orders resulted in a loss (negative profit)?
5. What are the top 3 highest-quantity Office Supplies orders in the South region?

## Method

For each question: **Filter → Sort → Read.**

1. Apply Data ▸ Filter (Excel) or the filter icon (Sheets) on the relevant column(s).
2. Set the filter condition(s) — most questions combine two conditions (e.g. Region = West AND ...), per the "use multiple filters" guidance.
3. Sort the remaining visible rows on the target column (largest-to-smallest or smallest-to-largest).
4. Read the answer straight off the top row(s) — no formulas required.

No `SUM`/`SUMIFS` formulas were used anywhere in this exercise; that's a different skill (aggregation), not filtering/sorting.


## Data note

The dataset is synthetically generated (same one used in the earlier KPI Tracking Sheet project) — customers, products, and transactions were created programmatically for practice purposes and do not represent a real business.
