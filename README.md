Credit Card Financial Dashboard

Author: Anmol Sharma | Date: Nov 2026
Tech Stack: Power BI | PostgreSQL | DAX | Power Query

📌 About the Project

This project is an end-to-end data analytics solution designed to transform disconnected credit card transaction and customer data into a real-time, interactive Power BI dashboard. By leveraging PostgreSQL for robust data management and Power BI for visualization, this dashboard enables stakeholders to monitor financial health, track week-over-week trends, and identify the most profitable customer segments.

⚠️ Business Problem

Stakeholders previously struggled with fragmented CSV data, time-consuming manual reporting, and a lack of real-time visibility into key performance metrics like revenue fluctuations, customer acquisition costs, and portfolio risk (delinquency and activation rates).

💡 Key Findings

Strong Financials: Generated 57M USD in YTD revenue, with a significant Week-over-Week (WoW) revenue increase of 28.8% in Week 53.

Top Demographics: The 40-50 age bracket, specifically self-employed professionals and businessmen, are the primary revenue drivers.

Product Concentration: The 'Blue' and 'Silver' entry-level card tiers account for an overwhelming 93% of all transactions.

Geographic Leaders: Texas, New York, and California dominate the market, driving 68% of the total portfolio revenue.

Expenditure Trends: "Bills" (14M USD) and "Entertainment" (10M USD) are the dominant customer spending categories.

🛠️ Data Pipeline & Workflow

Database Setup (PostgreSQL): Designed relational schemas (cred_detail and customers_detail) and executed high-speed bulk data ingestion of over 10,000 records using SQL COPY commands.

Data Transformation (Power Query & DAX): Engineered custom features like demographic brackets (AgeGroup, IncomeGroup) and dynamic Week-over-Week revenue tracking using advanced DAX measures (SWITCH, CALCULATE, FILTER).

Data Visualization (Power BI): Developed two primary dashboards—Transaction Report and Customer Report—featuring interactive slicers for real-time temporal and demographic filtering.

🚀 Business Recommendations

Targeted Marketing: Focus digital acquisition spend on the highly profitable 40-50 age demographic and self-employed professionals.

Incentivize Upgrades: Launch targeted loyalty promotions or waive first-year fees to convert high-spending Blue/Silver cardholders into premium Gold/Platinum tiers.

Geographic Focus: Double down on retention campaigns in TX, NY, and CA, while investigating ways to boost penetration in underperforming states like FL and NJ.

📊 Dashboards

(Insert screenshots of your Power BI Dashboards here)

Credit Card Transaction Report: Focuses on operational performance, revenue by expenditure type, and card category metrics.

Credit Card Customer Report: Focuses on demographic analysis, revenue by age/income, and customer satisfaction scores.
