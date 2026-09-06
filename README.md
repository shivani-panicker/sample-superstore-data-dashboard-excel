# Superstore Performance Dashboard - Excel

An interactive, multi-tab Excel dashboard built on the Sample Superstore dataset (2014-2017). Covers data cleaning, KPI design, native Excel charts, and click-driven navigation, all without add-ins.

## Dataset

Sample Superstore (`Orders`, `Returns`, `People` sheets)

- 9,994 order line items, 5,009 unique orders, Jan 2014 to Dec 2017
- 4 regions, 3 segments, 3 categories / 17 sub-categories, 49 states
- Clean source data, but about 19% of line items post a negative profit
- `Returns` sheet only flags about 8% of orders, so return-related figures are directional, not exact

## Why two dashboards

Excel and Tableau are used for what each does best on the same data, not the same dashboard rebuilt twice.

- Excel: PivotTable-driven exploration, formula-based KPIs, native charts, click-based navigation
- Tableau: LOD expressions, parameter-driven Top-N views, geographic mapping, cross-dashboard actions

## Structure

4 dashboard tabs, each sharing the same navigation rail.

| Tab | Focus | Key visuals |
|---|---|---|
| Overview | Company-wide health | 5 KPI cards, yearly Sales vs Profit trend, Profit by Sub-Category waterfall, Profit by Discount Band |
| Regional | Performance by geography | Sales by Region x Category, Order Count by Sub-Category, Profit Margin % by State (map) |
| Customer | Who drives revenue | Top Customers, Sales/Profit/Discount by Segment, Order Frequency Distribution, Sales Concentration (Pareto) |
| Operations | Fulfillment and shipping | Avg Fulfillment Days by Ship Mode, Avg Shipping Duration by Region, Ship Mode Mix by Year, Ship Mode Preference by Segment |

Every tab has the same rail: a Navigation panel to jump between tabs, a Filters panel (Category, Region, Segment), and a collapsible Year timeline toggled with a button. Operations also has its own local Ship Mode filter.


