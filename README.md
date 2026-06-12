# E-Commerce Data Visualization

Power BI dashboard project for analyzing e-commerce sales data, customer activity, product performance, and country-wise revenue patterns.

Made by **Arshpreet Singh**.

## Project Overview

This project converts raw e-commerce transaction data into an interactive Power BI dashboard. The dashboard helps users understand sales performance, revenue trends, top products, customer behavior, and market contribution by country.

## Folder Contents

- `e-commerce data.csv` - Source dataset containing transaction-level e-commerce records.
- `E-Commerce Sales Dashboard.pbix` - Power BI dashboard file.
- `SCREENSHOTS/` - Dashboard preview images.
- `E-Commerce Data Visualization Report With Described Figures.docx` - Detailed project report.
- `README.md` - Project summary and usage guide.

## Dataset Columns

The dataset includes the following fields:

- `InvoiceNo` - Invoice or order number.
- `StockCode` - Product stock code.
- `Description` - Product description.
- `Quantity` - Number of units purchased.
- `InvoiceDate` - Date and time of invoice.
- `UnitPrice` - Price per unit.
- `CustomerID` - Unique customer identifier.
- `Country` - Customer country.

## Dashboard Features

- Sales and revenue KPIs.
- Revenue trend analysis over time.
- Country-wise sales comparison.
- Product performance analysis.
- Customer and order-based insights.
- Visual summary pages for quick decision-making.

## Data Preparation

The dashboard is based on a cleaned sales view:

- Removed or filtered invalid sales records where required.
- Checked quantity and price fields for meaningful sales values.
- Used invoice dates for time-based trend analysis.
- Created revenue logic using:

```text
Revenue = Quantity * UnitPrice
```

## How To Use

1. Open `E-Commerce Sales Dashboard.pbix` in Microsoft Power BI Desktop.
2. Review the dashboard pages and visuals.
3. Use slicers, filters, and chart interactions to explore the data.
4. Refer to `REPORT.md` for the full project explanation.

## Tools Used

- Microsoft Power BI
- CSV dataset
- Data cleaning and visualization techniques

## Author

**Arshpreet Singh**
