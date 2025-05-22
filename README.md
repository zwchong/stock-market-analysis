# Stock Market Analysis Project

## Project Overview
This project analyzes a comprehensive stock market dataset to extract meaningful business insights using Microsoft Excel. The goal is to demonstrate foundational to intermediate data analysis skills essential for a junior data analyst role. This includes data cleaning, visualization, and dashboard creation — .

---

## Dataset Description
The dataset contains financial and geographic information for publicly traded companies, including:
- Exchange
- Symbol
- Shortname and Longname
- Sector and Industry
- Current Price
- Market Capitalization (Market Cap)
- Market Cap Rating
- EBITDA
- Revenue Growth (%)
- Headquarters Location (City, State, Country)
- Performance Tier

*Source: Kaggle (https://www.kaggle.com/datasets/andrewmvd/sp-500-stocks/data?select=sp500_companies.csv)*

---

## Tools Used
- Microsoft Excel (Tables, PivotTables, Charts, Slicers, Conditional Formatting)
- Excel Functions: VLOOKUP, IF

---

## Workflow & Key Steps

### 1. Data Cleaning & Preparation
- Converted Market Cap from scientific notation to readable numeric format
- Handled blank and missing cells, removing `(blank)` entries in PivotTables
- Created helper columns for performance tiers and classifications

### 2. Exploratory Data Analysis (EDA)
- Summarized data by sector, country, and industry using PivotTables
- Calculated averages and totals for key financial metrics
- Identified top-performing companies by revenue growth and market cap

### 3. Data Enrichment with VLOOKUP
- Created reference tables to categorize companies by:
  - Performance tiers based on Revenue Growth
  - Market Cap size ratings (Micro, Small, Mid, Large, Mega Cap)
- Used `VLOOKUP` with approximate matching to apply these categories dynamically

### 4. Visualization & Dashboarding
- Built interactive dashboards with slicers filtering by Sector, Country, and Performance Tier
- Created charts including bar, pie, and combo charts to visualize distributions and trends

---

## Key Insights
- Distribution of companies across market cap tiers and sectors
- Identification of sectors with highest revenue growth
- Geographic breakdown of market capitalization
- Clear visualization of company size and performance categories

---

## Skills Demonstrated
- Data cleaning and transformation in Excel
- Advanced use of PivotTables and calculated fields
- Dynamic data enrichment using `VLOOKUP` with approximate and exact matching
- Interactive dashboard creation with slicers and charts
- Business understanding of financial metrics and classifications

---

## Files Included
- `StockMarketDashboard.xlsx` — Final Excel workbook with cleaned dataset, PivotTables and charts
- `README.md` — Project documentation (this file)

---

## Next Steps
- Apply conditional formatting to further highlight insights
- Incorporate time-series data for trend analysis
- Convert analysis into SQL queries for database integration
- Build interactive dashboards using Power BI or Tableau
- Automate data updates with Excel Power Query
