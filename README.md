# NovaMed-Pharmaceutical-Sales-Analytics
## 💊Power BI dashboards analyzing pharmaceutical sales performance, profitability, and customer segments.
### View the Dashboard Interface below
<img width="1333" height="770" alt="Screenshot 2026-01-15 075556" src="https://github.com/user-attachments/assets/959bf3fd-d80c-48f9-88ab-dab355ce6e11" />
<img width="1327" height="761" alt="Screenshot 2026-01-15 075814" src="https://github.com/user-attachments/assets/1676ecb6-3a9c-4563-a6d0-6bae407e87ff" />

### 🗒️Table of Content

 - [Project Overview](#project-overview)
 - [Business Problem](#business-problem)
 - [Tools Used](#Tools-used)
 - [Data Description](#data-description)
 - [Dashboard Scope & Features](#Dashboard-scope-&-features)
 - [Key Insights](#key-insights)
 - [Conclusion](#Conclusion)
 - [Recommendations](#Recommendations)
   
### 📌 Project Overview
This project analyzes NovaMed Solutions’ 2023 pharmaceutical sales data to evaluate revenue performance, profitability, product demand, and customer behaviour. Using Power BI, interactive dashboards were developed to support data-driven decisions around sales optimization, inventory planning, and customer segmentation.
The analysis focuses on identifying top and underperforming drugs and customers, tracking month-over-month trends, and understanding how demographics and geography influence purchasing behaviour.

### 🎯 Business Problem
NovaMed Solutions faced challenges in:
- Optimizing sales performance across a diverse drug portfolio
- Identifying high and low-performing products and customers
- Improving demand forecasting and inventory efficiency
- Understanding customer demographics and regional revenue drivers
Without centralized reporting, stakeholders lacked visibility into profitability trends and customer behaviour needed for strategic planning.
### 🛠 Tools Used
- Power BI for data modelling, DAX calculations, and interactive dashboards
- Power Query for data cleaning and transformation
- DAX for KPIs such as revenue, profit, profit margin, and rankings
- Excel datasets as source files
### 📊 Data Description
The project integrates three core datasets:
Drug Information
- Drug ID
- Drug Name
- Unit Sales Price
- Cost of Production
- Medical Condition Treated
- Regulatory Compliance ID

Sales Information
- Sale ID
- Drug ID
- Customer ID
- Units Sold
- Sale Date
- Buyer Type (Individual, Pharmacy, Hospital)
Customer Information
- Customer ID
- Age
- Gender
- Country
- Buyer Details
These datasets were modelled using relational keys to enable cross-analysis between products, customers, and sales transactions.
### 📈 Dashboard Scope & Features
Dashboard 1. Top / Bottom Analysis
- Total Revenue, COGS, Profit, and Profit Margin KPIs
- Month-over-month revenue and profit comparison
- Dynamic Top 5 and Bottom 5 drugs by revenue, profit, and volume
- Top and underperforming customers with contribution percentages
- Interactive slicers for time, product, and customer exploration

Dashboard 2. Customer Analysis
- Customer distribution by age, gender, and buyer type
- Average revenue per customer segment
- Revenue breakdown by country and buyer category
- Revenue trends by age group and gender
- Geographic revenue insights highlighting top contributing countries
### 🔍 Key Insights
- A small group of drugs drives a disproportionate share of total revenue and profit
- Certain drugs generate high sales volume but low margins, indicating pricing or cost issues
- Hospitals and pharmacies contribute a higher average revenue than individual buyers
- Revenue concentration is strongest in the top two countries, signalling market dependency risk
- Specific age and gender segments show consistent purchasing patterns across drug categories

### ✅ Conclusion
The Power BI dashboards provide NovaMed Solutions with a consolidated view of sales performance and customer behaviour. By combining product profitability analysis with demographic insights, the company gains clarity on where revenue is generated, where margins are eroding, and which customer segments offer the highest long-term value.

### 🚀 Recommendations
- Prioritise inventory planning for high-margin, high-demand drugs
- Reassess pricing or production costs for low-margin, high-volume products
- Strengthen engagement with top-performing customer segments, especially hospitals and pharmacies
- Diversify market focus to reduce dependency on top revenue-generating countries
- Use month-over-month trend analysis to improve demand forecasting and sales planning
