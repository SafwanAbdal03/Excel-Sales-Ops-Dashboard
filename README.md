# Excel Sales & Ops Dashboard

Interactive Excel dashboard for sales performance and shipping operations.

## What it shows
- **Yearly Sales trend**
- **Profit Margin over time** (Profit / Sales)
- **Profit by Region** (sorted bar)
- **Average Days to Ship by Ship Mode**
- Slicers: **Year, Month, Region, Segment, Category, Ship Mode**

## Files
- `Dashboard.xlsx` – source workbook (Dashboard sheet with PivotTables/Charts + slicers)
- `Dashboard.pdf` – export for quick viewing
- `images/` – screenshots (optional)

## How to use
1. Open `Dashboard.xlsx` → go to the **Dashboard** sheet.
2. Use slicers to filter by Year/Month/Region/etc.
3. To refresh with new data: replace data in the source sheet, then **Data → Refresh All**.

## Built with
Excel **PivotTables/Charts**, slicers, and two calculated fields:
- **Profit Margin** = `SUM(Profit) / SUM(Sales)`
- **Days to Ship** = `Ship Date – Order Date`
