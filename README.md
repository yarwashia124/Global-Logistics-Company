# Global-Logistics-Company
> This Excel project cleans and analyzes shipping log data, using conditional formatting and slicers to track costs, priorities, and regional               

# Shipping Log Analysis (Excel)

## Overview
This project processes and analyzes shipping log data (date, priority, cost, state) using Excel. It includes data cleaning, sorting, conditional formatting, and interactive dashboards with slicers.

## Features
- *Data cleaning & validation* – removes duplicates, trims spaces.
- *Conditional formatting* – highlights high‑cost or high‑priority rows.
- *Dynamic tables* – easily sortable and filterable.
- *Slicers* – quick filters by region (East, West, North, South) and date.

## Requirements
- Microsoft Excel (Office 365 or 2019+)
- Basic knowledge of Excel formulas and PivotTables.

## Installation
1. Clone or download the repo.
2. Open the ShippingLog.xlsx file in Excel.
3. Enable macros if prompted (for any custom VBA scripts).

## Usage
1. *Load data*: Paste your raw shipping log into the RawData sheet.
2. *Run cleanup*: Use the “Data → Remove Duplicates” and TRIM functions.
3. *Apply formatting*: Conditional formatting rules are pre‑set for cost > ₹5000 and priority = “High”.
4. *Create PivotTable*: Drag fields to analyze by region, date, or state.
5. *Add slicers*: Insert slicers for Region and Date to enable quick filtering.

## Example
- *High‑cost filter*: Shows all shipments > ₹5000.
- *Region slicer*: Click “East” to view only Eastern region shipments.
