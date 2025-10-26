# 📱 Mobile Sales Performance Dashboard  
**Business Intelligence | Power BI | Data-Driven Sales Analytics**

## 1. Executive Summary  
This project presents a comprehensive **Mobile Sales Performance Dashboard** developed using Microsoft Power BI. The primary purpose of the report is to support senior management in analyzing product demand, brand profitability, and geographical performance. The solution delivers actionable business intelligence that strengthens decision-making and enhances operational efficiency in retail mobile sales environments.

## 2. Business Objectives  
- Monitor revenue, profit margin, and order volume in real time  
- Identify high-performing and underperforming mobile models and brands  
- Evaluate geographic market distribution to optimize regional strategy  
- Analyze seasonality, customer patterns, and growth opportunities  
- Improve executive reporting through interactive and self-service analytics  

## 3. Key Business Insights  
- **Premium Models Drive Profitability:** Apple and flagship Samsung devices maintain the highest profit margins, indicating strong returns in the premium smartphone segment.  
- **Regional Sales Imbalance:** Revenue concentration in Tier-1 cities reveals expansion opportunities in underserved regions.  
- **Seasonal Purchasing Behavior:** Sales demonstrate peak activity during product launch periods and festive seasons, enabling better sales and inventory planning.  
- **Customer Loyalty Impact:** Repeat customers contribute a major portion of total revenue, supporting initiatives that enhance customer retention.

> Note: Insights may be refined based on updated business rules or contextual scenarios in the dataset.

## 4. Dashboard Capabilities  
- Consolidated KPI monitoring for Revenue, Profit, Units Sold  
- Brand, category, and model-based comparative analysis  
- Geographic performance mapping at country-to-city granularity  
- Year-over-year trend evaluation for forecasting  
- Interactive slicers enabling segmentation by Brand, Region, Category, and Time  
- Clean, professional UX aligned with enterprise BI design standards  

## 5. Data Engineering & Modeling  
- **Schema Design:** Star Schema  
- **Data Preparation:** Power Query for transformation, standardization, and missing value resolution  
- **Analytical Logic:** DAX measures created for profitability, growth rate, and ranking analysis  

### Example DAX Measures  
```DAX
Total Sales = SUM(FactSales[SalesAmount])
Profit Margin % = DIVIDE(SUM(FactSales[Profit]), SUM(FactSales[SalesAmount]))
YoY Growth = DIVIDE([Total Sales] - [LY Total Sales], [LY Total Sales])
## 6. Technology Stack  
| Component | Functionality |
|----------|---------------|
| Power BI Desktop | Data modeling, dashboard development, publishing |
| Power Query | ETL operations and feature engineering |
| Data Analysis Expressions (DAX) | Business logic and KPI calculations |
| Excel / CSV | Source dataset ingestion |

## 7. Strategic Value Delivered  
- Improved visibility into product and category performance  
- Enhanced demand forecasting aligned with seasonal patterns  
- Data-backed decision support for business expansion strategies  
- Reduced report delivery time through interactive dashboard automation  

## 8. How to Access  
1. Download or clone this repository  
2. Open the `.pbix` file using **Microsoft Power BI Desktop**  
3. Use slicers and drill-down features to interact with insights  

## 9. Professional Outcome  
This project demonstrates proficiency in:  
- Applying advanced DAX for KPI and performance analytics  
- Implementing scalable data models using a star schema methodology  
- Designing polished business intelligence dashboards for executives  
- Transforming raw datasets into strategic, actionable insights  
