# EV Market Performance & Insights — Tableau Project

## Project overview
This project explores electric-vehicle market performance using Tableau. It is designed around manufacturer sales, annual trends, regional comparisons, market share, vehicle range, and average price.

## Important data note
`Data/ev_market_sample.csv` is **illustrative synthetic data created for the project template**. It is not official or verified EV market data. Replace it with the course-provided `ev_market_test.csv` before reporting real-world findings.

## Files
- `EV_Market_Performance_Insights.twb` — Tableau workbook scaffold to open in Tableau Desktop/Public.
- `Data/ev_market_sample.csv` — illustrative data for the workbook.
- `PROJECT_REPORT.md` — project report.
- `TABLEAU_BUILD_STEPS.md` — fast instructions for completing charts/dashboard and publishing.
- `INSIGHTS_TEMPLATE.md` — prompts to fill after checking actual charts.

## Recommended Tableau sheets
1. Manufacturer Sales: Manufacturer → Rows; SUM(Annual Sales Units) → Columns; sort descending.
2. Annual Sales Trend: Year → Columns; SUM(Annual Sales Units) → Rows; line chart.
3. Regional Comparison: Region → Rows; SUM(Annual Sales Units) → Columns; bar chart.
4. Market Share: Manufacturer → Color; SUM(Market Share Pct) → Angle; pie chart (optional).
5. Range vs Price: Average Range Km → Columns; Average Price USD → Rows; scatter plot, Manufacturer → Color.

## Publish
Open the workbook in Tableau Public. Verify/replace the data source, create the recommended sheets and dashboard if needed, then use **Server → Tableau Public → Save to Tableau Public**. Copy the public workbook URL for submission.
