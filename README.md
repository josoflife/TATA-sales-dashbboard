# TATA-sales-dashbboard


Title: TATA  2011 Online Retail Performance Dashboard

Objective:
Provide executives with clear, interactive visuals of revenue, top countries, top customers, and product demand (excluding the United Kingdom where specified).
______________________________________________________
Data Source

Dataset: Online retail transactions for 2011

Key Fields Needed: Invoice Date, Country, Customer ID, Quantity, Unit Price, Revenue (calculated as Quantity * Unit Price).
_______________________________________________________
Visual 1 – Monthly Revenue (CEO)

Purpose: Show the 2011 revenue trend by month to reveal seasonality and help forecast next year.

Visualization Type: Line chart.

Details:X-Axis: Month (January–December 2011).
               Y-Axis: Total Revenue.
                Filter: Year = 2011 only.
______________________________________________________  Visual 2 – Top 10 Countries by Revenue (CMO)
Purpose: Identify countries (excluding the United Kingdom) with the highest revenue and quantity sold.

Visualization Type: Horizontal bar chart with dual-axis (Revenue & Quantity) or side-by-side bars.

Details: Sort by Revenue descending.
        Show the top 10 countries.
        Exclude Country = “United Kingdom”.
________________________________________________________

Visual 3 – Top 10 Customers by Revenue (CMO)

Purpose: Pinpoint the highest spending customers.

Visualization Type: Horizontal bar chart sorted descending by Revenue.

Details:Dimension: Customer ID (or Name if available).
        Measure: Total Revenue.
          Show top 10 only.
        Display customer ID and revenue values on bars.
______________________________________________________
Visual 4 – Global Demand Map (CEO)

Purpose: Identify high-demand regions to support expansion decisions.

Visualization Type: Filled world map (symbol or density map).

Details:Measure: Quantity Sold (or Revenue).
        Filter: Exclude “United Kingdom”.
        Color intensity: Higher demand = darker shade.
________________________________________________________
Dashboard Layout
Header KPIs (big numbers):
Total Revenue 2011
Total Customers
Total Products Sold
________________________________________________________
Interactivity
Year filter (default 2011).
Hover tooltips with extra info (but all essential numbers are visible without hover, per CEO request).
