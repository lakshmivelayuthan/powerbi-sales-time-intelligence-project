# Power BI Sales Time Intelligence Project
## Project Overview
This project demonstrates a real-world sales performance dashboard built using Power BI.
The objective was to analyze sales trends over time and provide meaningful insights using advanced time intelligence calculations.
The report is designed to support business decision-making by comparing current performance with previous periods and identifying growth patterns.
---
## Report Pages
- **Sales Overview**: High-level KPIs such as Total Sales, Sales YOY, and Growth %
- **Time Intelligence Analysis**: Year-over-Year (YoY), Previous Year (PY), and trend comparison
- **Monthly Performance**: Sales performance by month with dynamic visuals
- **Interactive Analysis**: Slicers for Year, Month, and other dimensions.
---
## Key Features & Techniques Used
- Star schema data modeling
- Proper Date table implementation
- DAX measures for:
  - Total Sales
  - Previous Year Sales
  - Year-over-Year Growth
  - Latest Year calculations
- Use of variables to control filter context
- Dynamic visuals and KPI cards
- Performance-optimized measures (measures instead of calculated columns)
---
## Real-World Challanges Addressed
- Comparing sales against the **latest completed year** regardless of slicer selection
- Handling filtr context issues in YoY calculations
- Ensuring accurate time intelligence using a dedicated Date table
- Designing reports that are both business-friendly and technically accurate
---
## Business Value
- Enables management to quickly assess sales performance
- Identifies growth and decline trends across time periods
- Supports data-driven decision-making
- Reduces manual reporting effort through automation
---
## Tools Used
- Power BI Desktop
- DAX (Data Analysis Expressions)
---
## Data Source
- SQL database (data populated using INSERT statement)
---
