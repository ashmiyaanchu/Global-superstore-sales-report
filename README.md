
# Global Superstore Sales Analysis

An interactive Power BI report for exploring Global Superstore orders and sales across shipping methods and geographic markets. The report combines an overview page with a country drill-through page for more detailed location-based analysis.

## Project files

- `Global superstore sales dashboard.pbix` — Power BI report containing the interactive dashboard.
- `Global Superstore.ashmiya.xlsx` — Excel workbook used as the report’s data source.

## Report overview

### Sales Analysis

The main page presents sales and order information through visual summaries, including:

- Order count by ship mode
- Sales by market
- Sales by state
- Sales by city
- Sales by region

Use the visuals to explore how sales are distributed across the locations shown in the report.

### Country details

The report includes a drill-through page for country-level exploration. It provides tables showing sales by region, state, and city, as well as order counts by ship mode for the selected country.

To open the country details, right-click a country in a relevant visual and select the drill-through option. Use the **Back** button on the details page to return to the overview.

## Open the report

1. Download both the `.pbix` report and the Excel workbook.
2. Open `Global superstore sales dashboard.pbix` in Microsoft Power BI Desktop.
3. If Power BI asks you to locate the source data, select `Global Superstore.ashmiya.xlsx`.
4. Refresh the report if prompted.

Keep the workbook available at the path configured in the report. If you move or rename it, update the data source path in Power BI Desktop before refreshing.

## Interacting with the dashboard

- Select a data point in a chart to filter or highlight related visuals.
- Use the report’s country drill-through interaction to view the corresponding details page.
- Use the **Back** button to return from the details page to the sales overview.
- Clear selections in the visuals to restore the broader view.

## Data and interpretation

The report displays sales and order counts from the included workbook. Values shown in the visuals depend on the selected locations and any active filters. The report focuses on sales and order distribution; it should not be used to infer profit or other measures unless those are added to the report.

## Requirements

- Microsoft Power BI Desktop
- Microsoft Excel, if you want to inspect or edit the source workbook

## Notes

This repository contains the report file and its Excel data source. The `.pbix` file is required for the interactive Power BI experience.
