# Tableau build steps (quick version)

## 1. Open and connect
1. Open Tableau Public.
2. Open `EV_Market_Performance_Insights.twb`.
3. If Tableau asks to locate the data file, choose `Data/ev_market_sample.csv`.
4. For the real course project, use **Data → New Data Source → Text File** and select your course file `ev_market_test.csv`. Confirm the field names and data types.

## 2. Create the core worksheets
### Manufacturer Sales
- Drag `Manufacturer` to Rows.
- Drag `Annual Sales Units` to Columns.
- Sort descending.
- Marks: Bar. Turn on mark labels.

### Annual Sales Trend
- Drag `Year` to Columns.
- Drag `Annual Sales Units` to Rows.
- Change Marks to Line.

### Regional Comparison
- Drag `Region` to Rows.
- Drag `Annual Sales Units` to Columns.
- Marks: Bar; sort descending.

### Market Share
- Drag `Manufacturer` to Color.
- Drag `Market Share Pct` to Angle and Label.
- Marks: Pie.

### Range vs Price
- Drag `Average Range Km` to Columns.
- Drag `Average Price USD` to Rows.
- Drag `Manufacturer` to Color.
- Marks: Circle.

## 3. Assemble dashboard
1. Click **New Dashboard** at the bottom.
2. Set size to Automatic or Desktop Browser.
3. Add the worksheets above.
4. Add filters for `Year`, `Region`, and `Manufacturer` where useful.
5. Add a title: **EV Market Performance & Insights**.
6. Use a clean palette (dark navy, teal, white) and remove unnecessary gridlines.

## 4. Publish to Tableau Public
1. Save the workbook.
2. Choose **Server → Tableau Public → Save to Tableau Public**.
3. Sign in to your Tableau Public account.
4. Use the title `EV Market Performance & Insights`.
5. After publishing, copy the browser URL.

Note: a Tableau Public link is only created after the workbook is published from your signed-in Tableau account. This project file cannot publish itself automatically.
