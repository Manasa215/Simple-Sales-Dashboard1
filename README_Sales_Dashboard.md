# Simple Sales Dashboard Design

## Project overview
An Excel-based sales dashboard that summarizes sales performance by month, product category, region, state/city, customer segment, and payment method.

## Objective
Turn cleaned sales records into a concise dashboard that helps a stakeholder identify sales trends, revenue concentration, and profitability patterns.

## Files
- `Sales_Dashboard_Enhanced.xlsx` — enhanced workbook with the dashboard, source dataset, charts, calculated fields, and a Read Me worksheet.
- `How_to_Read_Sales_Dashboard.pdf` — one-page guide explaining the KPIs, charts, filters, and calculated fields.
- `deployment/README.md` — notes on publishing/sharing the workbook and rollback approach.
- `evidence/README.md` — checklist for screenshots and rollback evidence to add before submission.

## Dashboard contents
- KPI cards: Total Sales, Total Profit, Total Orders, Total Quantity, Average Discount, and Average Profit Margin.
- Seven charts covering monthly sales/profit, category, region, top states, top cities, customer segment, and payment method.
- Dataset table filters and calculated fields: `Order_Month`, `Profit_Margin`, and `Discount_Band`.

## Approach
1. Reviewed the sales data fields and existing dashboard charts.
2. Styled the dashboard title, KPI cards, chart section headings, and summary block for readability.
3. Added calculated fields to group dates by month, calculate profit margin, and classify discount levels.
4. Added table filters and conditional formatting to help inspect records and profit values.
5. Added an in-workbook guide and a separate one-page PDF explaining how to read the dashboard.

## How to use
1. Open `Sales_Dashboard_Enhanced.xlsx` in Microsoft Excel.
2. Start on the `Dashboard` sheet and read the KPI cards from left to right.
3. Review the monthly trend, then category/region and location charts, then customer/payment charts.
4. On `Dataset`, use the filter dropdowns to narrow records.
5. If PivotCharts do not reflect changed data, choose **Data → Refresh All**. For a fully slicer-driven dashboard, add Month and Region slicers to the relevant PivotTables and connect them through **Report Connections**.

## Validation and limitations
- The workbook is an Excel dashboard, not a hosted web application; no web deployment service is required.
- Table filters narrow source records, but may not automatically filter every existing PivotChart. Refresh PivotTables or add connected slicers in Excel for fully interactive chart filtering.
- Confirm the intended currency and validate the sample data before using results for business decisions.
- This repository should contain only non-sensitive sample data. Do not upload private customer information.

## Outcome
The workbook provides a compact view of sales and profit performance, plus clearer formatting, calculated fields, filtering guidance, and a one-page reader guide.
