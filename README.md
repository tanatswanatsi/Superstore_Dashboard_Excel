# Superstore_Dashboard_Excel
Interactive Excel sales dashboard with PivotTables, PivotCharts, and slicers — built on the Sample Superstore dataset to analyze profitability by category, region, and segment.

# Superstore Sales & Profitability Dashboard

## Overview
An interactive Excel dashboard analyzing the Sample Superstore dataset (9,994 orders, 
5,009 unique transactions), built with PivotTables, PivotCharts, and slicers to explore 
sales and profitability across category, region, segment, and top customers.

## Dataset
Sample Superstore dataset — order-level retail transaction data including Sales, Profit, 
Category, Region, Segment, Customer, and Order Date (2014–2017).

## Process
1. **Data Cleaning** — verified no duplicate rows, formatted dates and currency fields, 
   confirmed numeric columns were properly typed, and resolved a PivotTable source-range 
   issue that was pulling in phantom blank records
2. **PivotTables** — built 6 PivotTables covering Category/Sub-Category, Region, Segment, 
   Top 10 Customers, and a monthly Sales Trend
3. **Dashboard** — combined PivotCharts into a single dashboard with KPI cards (Total Sales, 
   Total Profit, Profit Margin, Total Orders) and 3 interactive slicers (Region, Category, 
   Segment) connected across all charts

## Key Insights

**Overall performance:** Total Sales of $2,297,200.86 generated $286,397.02 in profit — 
a 12.47% overall margin. Sales grew every year from 2014 ($484K) to 2017 ($733K), roughly 
a 51% increase over the period.

**Technology is the strongest category** — highest Sales ($836,154) and highest Profit 
($145,455), outperforming both Office Supplies and Furniture on both metrics.

**Furniture is a volume trap** — despite generating the second-highest Sales ($741,999, 
nearly matching Office Supplies), it produced by far the lowest Profit ($18,451) — a 
margin of just 2.5%, compared to 17% for Office Supplies and 17.4% for Technology.

**Tables and Bookcases are losing money outright** — within Furniture, the Tables 
sub-category lost -$17,725 and Bookcases lost -$3,473, despite both having substantial 
sales volume ($206,966 and $114,880 respectively). These two sub-categories alone explain 
most of Furniture's weak overall margin.

**The West region leads, the South lags** — West generated the highest Sales ($725,458) 
and Profit ($108,418). The South region had the lowest Sales ($391,722) and lowest Profit 
($46,749) of all four regions.

**Consumer segment dominates** — Consumer accounts for the largest share of both Sales 
($1,161,401) and Profit ($134,119), more than Corporate and Home Office combined on Sales.

**Customer concentration is high at the top** — the top 10 customers alone account for 
over $154,000 in sales, led by Sean Miller ($25,043) and Tamara Chand ($19,052) — more 
than double the 3rd-ranked customer.

## Recommendations

- **Investigate pricing/discounting on Tables and Bookcases.** These two sub-categories 
  are actively losing money despite healthy sales volume — likely candidates for 
  excessive discounting. Reviewing discount thresholds specifically for these items 
  could recover meaningful profit without needing to grow sales.
- **Reallocate marketing/inventory focus toward Technology.** It's the top performer on 
  both revenue and profit — worth understanding what's driving its success and whether 
  that can be replicated in other categories.
- **Review what's underperforming in the South region.** With both the lowest sales and 
  lowest profit of any region, it's worth investigating whether this reflects market size, 
  weaker local demand, or an execution gap (e.g., fewer sales reps, slower shipping) 
  that could be addressed directly.
- **Build a retention strategy around top customers.** With the top 10 customers 
  contributing over $154K in sales, a dedicated account-management or loyalty approach 
  for this group could protect a disproportionately valuable slice of revenue.
- **Capitalize on the consistent year-over-year growth trend.** Sales grew every single 
  year from 2014–2017 — worth identifying what's driving that trajectory (new customers, 
  repeat purchases, category expansion) to ensure it continues.

## Tools Used
Microsoft Excel — PivotTables, PivotCharts, Slicers, KPI formulas

## How to Use
Download the file and open in Excel. Click any slicer (Region, Category, Segment) to 
filter the entire dashboard interactively.
