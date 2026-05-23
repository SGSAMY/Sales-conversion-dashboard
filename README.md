# Sales Conversion Funnel Dashboard – Power BI

## Project Overview

This Power BI dashboard provides an executive-level overview of sales conversion performance for financial products including ISA, JISA, LISA, and Over 50 policies.

The dashboard focuses on quote-to-sale conversion, customer activity, policy maturity forecasting, year-over-year comparisons, and sales trends across multiple channels.

---

## Key Features

- KPI Reporting
- Quote-to-Sale Conversion Funnel
- Policy Maturity Forecasting
- YOY Sales Comparison
- Small Multiples Trend Analysis
- Conditional Formatting
- Dynamic Filtering
- Customer Segmentation

---

## Tools Used

- Power BI Desktop
- DAX
- Power Query
- Excel

---

## Sample DAX Measures

### Quote to Sale Conversion %

```DAX
Quote to Sale Conversion % = 
DIVIDE(
    [Total Policies Sold],
    [Total Quotes]
)
```

### YOY Growth %

```DAX
YOY Sales Growth % = 
DIVIDE(
    [Total Sales] - [Sales LY],
    [Sales LY]
)
```

### Previous Year Sales

```DAX
Previous Year Sales = 
CALCULATE(
    [Total Policies Sold],
    SAMEPERIODLASTYEAR(DateTable[Date])
)

```
## Dashboard Preview

!(Screenshots/dashboard-preview.png)

---

## Skills Demonstrated

- Data Visualization
- Business Intelligence
- Dashboard Design
- Financial Analytics
- Forecasting
- Time Intelligence
- KPI Reporting

## Author
Satheesh Gurusamy
