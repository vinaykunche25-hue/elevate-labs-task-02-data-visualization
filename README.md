# Task 2: Data Visualization and Storytelling

## Objective
Create visualizations that communicate a clear business story from the Superstore dataset.

## Tool
Power BI / Tableau (recommended for the internship task).

## Dataset
Superstore Sales dataset, using the `Orders` sheet as the primary analysis table.

## Dataset overview
- Rows: 10,194
- Columns: 21
- Unique Orders: 5,111
- Unique Customers: 804
- Quantity: 38,654

## Dashboard KPIs
- Total Sales: $2,326,534.35
- Total Profit: $292,296.81
- Total Orders: 5,111
- Profit Margin: 12.56%

## Required/Recommended Visual Story
1. KPI cards — Total Sales, Total Profit, Total Orders
2. Sales by Category — clustered column/bar chart
3. Profit by Category — clustered column/bar chart
4. Sales by Region — bar chart
5. Monthly Sales Trend — line chart
6. Profit by Sub-Category — bar chart, highlighting negative-profit categories
7. Top 10 Products by Sales — horizontal bar chart
8. A short business-insights/story section

## Key observations from this dataset
- Technology has the highest category sales.
- Technology also has the highest category profit.
- West has the highest regional sales.
- Tables have negative total profit, followed by Bookcases and Supplies.
- Sales increase across the dataset's years, with 2026 having the highest annual sales in this file.

## Files
- `visual_report.pdf` — visual report/storyboard
- `visuals/` — chart images and dashboard preview
- `category_summary.csv`
- `region_summary.csv`
- `subcategory_summary.csv`
- `monthly_summary.csv`
- `top_10_products.csv`

## Power BI build
Import the Superstore Excel file, select the `Orders` table, and create the visuals listed above. Add slicers for:
- Order Date
- Region
- Category
- Segment

Keep the dashboard uncluttered and use clear titles and labels.

## GitHub submission
Create a new repository for Task 2 and upload the report, visuals, dataset used, and this README. Then submit the repository link through the internship submission form.
