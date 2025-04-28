# Business Insights 360 End-to-End
AtliQ Inc., a growing electronics OEM, was buried under static sheets. I transformed their data journey—building a robust SQL infrastructure and a dynamic Power BI dashboard—connecting Sales, Finance, Marketing, Supply Chain, and Executive teams with real-time, actionable insights.

## Project Overview
This project demonstrates a full analytics workflow from raw data cleaning to advanced business intelligence reporting across multiple domains: Finance, Sales, Marketing, Supply Chain, and Executive Metrics.

## Tools Used
- **MySQL**: Data cleaning, transformations, procedures for dynamic reports
- **Excel**: Intermediate data analysis and validation
- **Power BI**: Interactive dashboards across business domains

## Project Workflow
1. **Data Cleaning in MySQL**:
   - Trimmed unnecessary spaces and corrected misspellings.
   - Standardized data types for consistency.
   - Created dynamic views with custom columns, calculated fields, multiple joins to prepare the dataset for Power BI.
   - Developed stored procedures to automate reports:
     - Customer-wise report
     - Top N Markets
     - Top N Customers
     - Top N Products Year-wise

2. **Data Analysis in Excel**:
   - Analyzed and validated MySQL report outputs.
   - Performed pivot table analyses to explore patterns.

3. **Data Modeling & Visualization in Power BI**:
   - Built domain-specific dashboards:
     - **Finance**: P&L statement, KPIs-Net Sales, Gross Margin, Net Margin
     - **Sales**: Gross Revenue, Conversion Rates, Volume Target Analysis
     - **Marketing**: Marketing Efficiency, Market Share, Reach by Zone
     - **Supply Chain**: sMAPE, APE, Net Error analysis
     - **Executive Metrics**: CAGR for Net Sales, Gross Profit, Marketing Expenses, COGS, Operating Expenses, and Net Profit

## 📸 Dashboards Preview
![image](https://github.com/user-attachments/assets/4f0d408d-d76b-4b88-ac99-74a0b83d518a)
![image](https://github.com/user-attachments/assets/74f7aa28-7c8c-402b-ac08-a6e28d662896)
![image](https://github.com/user-attachments/assets/3ef33794-4a19-4d69-bfee-3f9c7287f325)

## How to Run This Project
1. Use SQL scripts to clean and prepare the data.
2. Analyze intermediate outputs in Excel if needed.
3. Open the Power BI `.pbix` file to explore final dashboards.

## Key Insights
- Dynamic reporting using SQL procedures saved >40% reporting time.
- Cross-domain dashboarding provided a full business overview in one platform.
- Advanced KPIs like CAGR, Net Margin, sMAPE gave executives deeper insights.

