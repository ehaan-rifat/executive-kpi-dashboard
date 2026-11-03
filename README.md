# Executive KPI Dashboard | Excel Business Analysis Project

An Excel-based executive dashboard for a fictional e-commerce business, built with synthetic FY2025 order data. The project demonstrates KPI reporting, sales and profitability analysis, target tracking, and evidence-based management recommendations.

> **Data integrity note:** All 300 order records and monthly targets are synthetic training data. This is a self-initiated portfolio project, not a report of a real company's performance.

## Executive snapshot

| KPI | Result |
|---|---:|
| Total revenue | $37,262.31 |
| Total profit | $13,900.54 |
| Profit margin | 37.3% |
| Orders analyzed | 300 |
| Annual revenue target | $41,000 |
| Annual target attainment | 90.9% |

## Workbook contents

| Worksheet | Purpose |
|---|---|
| Executive Dashboard | Executive KPIs, monthly performance, regional revenue, charts, and management findings |
| Product Analysis | Revenue and profit by product category |
| Orders Data | 300 order-level records and calculated revenue, cost, and profit |
| Monthly Targets | Monthly revenue targets for FY2025 |
| Read Me | Workbook purpose, metric definitions, and usage guidance |
| Regional Analysis | Revenue and profit comparison across four regions |

## Key findings

- All 12 months finished below their monthly revenue targets.
- November was the strongest month for both revenue and profit, reaching 91.1% of its target.
- Electronics generated the highest revenue ($18,280.30).
- Personal Care recorded the highest profit margin (50.6%).
- Rajshahi led regional revenue ($11,884.73); Dhaka recorded the lowest ($8,405.87).

These observations describe the synthetic dataset only. They do not establish real-world causes or guarantee that the same patterns would hold in an actual business.

## Validation and testing

- Recalculated revenue, profit, and margin from the 300 order records and reconciled them with the dashboard KPIs.
- Reconciled monthly, product-category, and regional revenue and profit summaries.
- Inspected workbook formulas for visible spreadsheet error values.
- Tested a source-data change on order `ORD-0001`: changing unit price from $44.25 to $50.00 increased revenue and profit by $5.75 each; restoring the original price returned the dashboard to its original totals.

## Tools and techniques

- Microsoft Excel
- PivotTables and summary analysis
- Spreadsheet formulas and KPI calculations
- Charts and executive dashboard layout
- Revenue target-attainment analysis
- Data reconciliation and scenario testing

## How to use

1. Open `Executive_KPI_Dashboard_Project2_Starter(1).xlsx`.
2. Start with the **Read Me** worksheet.
3. Review the **Orders Data** and **Monthly Targets** worksheets.
4. Explore the executive dashboard and the product and regional analysis sheets.
5. If editing source records, verify that the summary calculations and charts update as expected.

## Limitations

- The dataset is synthetic and limited to 300 orders across FY2025.
- Findings are descriptive; no causal analysis is claimed.
- The workbook is an Excel analysis artifact. Automated external data connections or live business-system integration are not claimed.

## Portfolio status

The workbook has been inspected and its reported headline metrics independently recalculated. Add final screenshots and publish the workbook before marking the project as publicly published.
