## Introduction

  In today's competitive business landscape, identifying high-performing markets, customers, and products is crucial for strategic decision-making. Equally important is understanding the impact of discounting practices on
  sales performance.
  This analysis focuses on validating and interpreting data across different dimensions — Markets, Customers, Products — using Power BI visualizations and Excel validations to ensure accuracy and business relevance.
  
  The raw data was ingested from source files into MySQL, visualized through Power BI dashboards, and finally validated and summarized in Microsoft Excel for reporting purposes. This systematic approach ensures that the
  insights derived are both reliable and actionable.

## Problem Statement

Our organization needs a clear understanding of:
  Which markets, customers, and products are driving the highest net sales.
  Which markets are showing the highest growth rates.
  How discounting (the reduction from Gross Price to Net Sales) affects customers and markets.

The objective of this analysis is to:
  Identify top contributors to revenue growth.
  Detect discount-heavy customers and markets that may require pricing strategy adjustments.
  Provide validated, insight-driven reports that can support management decisions on sales strategies, customer negotiations, and market prioritization.

## Methodology
  Data Flow (Raw ➔ MySQL ➔ Power BI ➔ Excel Validation)

## Analysis & Findings

### Top Performers
  Top 3 markets by Net Sales, Top 3 Customers that drive the most sales in those markets, Top 3 Products that are the top contributors
  
  ![image](https://github.com/user-attachments/assets/2efe79cc-9288-48d6-b29c-5b38a2899278)


  Top 5 Markets by Growth
  
  ![image](https://github.com/user-attachments/assets/c5586037-6c45-4aeb-ab28-303748b1c909)


  Top 10 Customers by Net Sales
  
  ![image](https://github.com/user-attachments/assets/cdb4daf3-7115-4fa5-92ac-500a1ef0d91a)


  Top 10 Products by Net Sales
  
  ![image](https://github.com/user-attachments/assets/f9fb90f8-ac5d-4e8f-a537-a198495c019d)

### Discount Analysis
  Discount Drilldown: Market ➔ Customers
  
  ![image](https://github.com/user-attachments/assets/5a358e33-3a46-422a-9533-03c3adbbc61b)


  Discount % Given to Customers
  
  ![image](https://github.com/user-attachments/assets/a557b283-a537-4654-9a48-c6451783fc64)


### Conclusion
The analysis of product performance, customer dynamics, and market trends over the past five years has surfaced several notable patterns and strategic insights:

- **AQ BZ Compact** is the only product to consistently appear in the **Top 10 Products by Net Sales** for five consecutive years, showcasing sustained customer demand and sales strength.
- **Amazon**, **AtliQ Exclusive**, and **AtliQ E-Store** have remained the **Top 3 Customers by Net Sales** throughout the five-year period, highlighting their pivotal role in driving revenue.
- **Amazon** leads in net sales but offers the **highest discount rate at 57%**, indicating a volume-driven pricing strategy. In contrast, **AtliQ Exclusive** achieves similar sales with a **lower discount rate of 41%**, suggesting stronger margins.
- **China, Canada, Poland, Italy, and the USA** recorded the **highest sales growth**, identifying them as high-potential markets.
- In the **most recent year**, **India, South Korea, and the USA** ranked as the **Top 3 Markets by Net Sales**.
- **South Korea** shows the **highest average discount rate at 55%**, signaling a potential profitability issue despite strong sales performance.

These insights provide a balanced view of revenue contribution vs. profitability, helping guide future strategies in pricing, product focus, and market prioritization.







