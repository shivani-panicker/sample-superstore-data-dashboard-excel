# Superstore Performance Dashboard - Excel

## Project Overview

An interactive, multi-tab Excel dashboard built on the Sample Superstore dataset from 2014 to 2017. The project covers data cleaning, KPI design, PivotTable-driven analysis, native Excel charts, and click-driven dashboard navigation without add-ins.

## Objectives

- Analyze overall sales and profitability performance.
- Compare performance across regions and states.
- Understand customer segment contribution.
- Evaluate shipping and fulfillment performance.
- Identify the impact of discounting on profitability.
- Analyze category and sub-category level performance.

## Dataset

Sample Superstore dataset containing the `Orders`, `Returns`, and `People` sheets.

- 9,994 order line items and 5,009 unique orders.
- Data covers January 2014 to December 2017.
- 4 regions, 3 segments, 3 categories, 17 sub-categories, and 49 states.
- Approximately 19% of line items generate negative profit.
- The `Returns` sheet flags approximately 8% of orders, so return-related figures are directional rather than exact.

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Dashboard development and analysis |
| PivotTables | Data summarization and exploration |
| Excel Formulas | KPI calculations |
| Native Excel Charts | Data visualization |
| Excel Navigation | Click-driven dashboard navigation |

## Data Cleaning & Transformation

- Reviewed and structured the Orders, Returns, and People datasets.
- Validated fields required for sales, profit, discount, customer, regional, and shipping analysis.
- Created calculated metrics and KPIs for dashboard reporting.
- Prepared the data for PivotTable-based analysis.
- Integrated relevant return information into the analysis.

## Data Analysis

The analysis covers five key areas:

### Overview Analysis

- Overall sales and profit performance.
- Year-over-year sales and profit growth.
- Profitability trends across the business.

### Regional Analysis

- Sales and profit by region.
- Performance by state.
- Regional performance across product categories.
- Identification of states with strong sales but weak profitability.

### Customer Analysis

- Sales and profit by customer segment.
- Top customer contribution.
- Order frequency distribution.
- Sales concentration using Pareto analysis.

### Operations Analysis

- Shipping mode performance.
- Average fulfillment time.
- Average shipping duration by region.
- Shipping mode mix across years and customer segments.

### Product & Profit Analysis

- Category-level sales and profitability.
- Sub-category profit contribution.
- Profitability across discount bands.
- Identification of high-performing and loss-making sub-categories.

## Dashboard

The workbook contains four dashboard tabs with a shared navigation rail.

| Tab | Focus | Key Visuals |
|-----|-------|-------------|
| Overview | Company-wide health | KPI cards, yearly Sales vs Profit trend, Profit by Sub-Category waterfall, Profit by Discount Band |
| Regional | Performance by geography | Sales by Region × Category, Order Count by Sub-Category, Profit Margin % by State |
| Customer | Customer contribution | Top Customers, Sales/Profit/Discount by Segment, Order Frequency Distribution, Sales Concentration Pareto |
| Operations | Fulfillment and shipping | Avg Fulfillment Days by Ship Mode, Avg Shipping Duration by Region, Ship Mode Mix by Year, Ship Mode Preference by Segment |

Each dashboard includes:

- Navigation panel for switching between tabs.
- Filters for Category, Region, and Segment.
- Collapsible Year timeline.
- Dedicated Ship Mode filter on the Operations dashboard.

## Key Insights

### 1. Overall Performance

- Sales reached **$2.29M**, with overall profit of **$286.4K**.
- Sales increased by **20.4%**, while profit increased by **14.2%**, indicating strong growth with comparatively slower profit growth.

### 2. Regional Performance

- The **West region** is the strongest performer, generating approximately **$725.5K in sales and $108.4K profit**.
- The **South region** has the lowest sales at approximately **$391.7K**.
- **Texas** is a major profitability concern, generating approximately **$170.2K in sales but a $25.7K loss**.

### 3. Customer Performance

- The **Consumer segment** is the largest contributor, generating approximately **$1.16M in sales and $134.1K profit**.
- The **Corporate segment** contributes approximately **$706K in sales and $92K profit**.
- **Home Office** contributes the least sales at approximately **$430K**, while generating around **$60.3K profit**.

### 4. Operations Performance

- **Standard Class** is the dominant shipping mode, accounting for approximately **$1.36M in sales and $164.1K profit**.
- **Same Day shipping** generates the lowest sales among the major shipping modes at approximately **$128.4K**.
- Higher discount bands negatively affect profitability, with the **41-60% discount band generating approximately $70.6K in losses**.

### 5. Product & Profitability

- **Technology** is the most profitable category, generating approximately **$145.5K profit**.
- **Office Supplies** generates approximately **$122.5K profit**.
- **Furniture** is a profitability concern, generating approximately **$742K in sales but only $18.5K profit**.
- At the sub-category level, **Copiers, Phones, and Accessories** are major profit contributors.
- **Tables** generate the largest sub-category loss at approximately **$17.7K**.

## Dashboard Screenshots
PAGE 1 
<img width="1598" height="588" alt="image" src="https://github.com/user-attachments/assets/5e0b1edf-75b8-48c3-bcb6-4789fdb26467" />

PAGE 2
<img width="1596" height="592" alt="image" src="https://github.com/user-attachments/assets/b6c8c661-331f-4809-b0d5-2a0ad099479b" />

PAGE 3 
<img width="1497" height="537" alt="image" src="https://github.com/user-attachments/assets/dd2ad402-fc51-4f46-820a-a92ef92b1762" />

PAGE 4
<img width="1398" height="511" alt="image" src="https://github.com/user-attachments/assets/bf2e3caf-ba59-435d-9fbb-7ec2e6c3c213" />

## Conclusion

The dashboard provides a consolidated view of Superstore's sales, profitability, customer, regional, product, and operational performance. The analysis shows that while the business remains profitable and continues to grow, profitability varies significantly across regions, products, and discount levels. The interactive Excel dashboard enables users to identify these performance differences, evaluate key business metrics, and gain actionable insights into overall business performance.


