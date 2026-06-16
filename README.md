# E-Commerce Sales Data Cleaning & Transformation

## Project Overview
End-to-end data cleaning and transformation project using Microsoft Excel Power Query.
Cleaned 3 messy datasets totalling 2,058 raw rows into a professional, analysis-ready data model.

## Files
- `Excel_Study_Group_Project1.xlsx` — Full Power Query solution with all cleaned tables
- `Messy_List_of_Orders.csv` — Raw orders data (509 rows)
- `Messy_Order_Details.csv` — Raw line items data (1,507 rows)
- `Messy_Sales_Target.csv` — Raw sales targets (44 rows)

## What Was Cleaned
- Mixed date formats (DD-MM-YYYY, MM/DD/YYYY, YYYY-MM-DD, TBD)
- Currency symbols (₹, Rs., INR) in numeric columns
- Inconsistent state names (typos, abbreviations, mixed casing)
- Negative quantities, zero amounts, duplicate rows
- Category and Sub-Category typos and abbreviations

## Queries Built
| Query | Description | Rows |
|---|---|---|
| Messy_List_of_Orders | Cleaned orders header table | 434 |
| Messy_Order_Details | Cleaned line items table | 1,493 |
| Messy_Sales_Target | Cleaned monthly targets | 36 |
| Orders_Merged | Orders LEFT JOIN Details | 1,320 |
| Order_Summary | Aggregated by Order ID | 498 |
| Target_Vs_Actual | Actual Sales vs Target by Category | 3 |

## Tools Used
Microsoft Excel, Power Query, M Code

## Part of
Excel Study Group — SmartBizCrux Technologies
