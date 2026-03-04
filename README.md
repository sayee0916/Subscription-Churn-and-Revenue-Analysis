📊 Subscription Churn & Revenue Analysis – Power BI
📌 Project Overview

This project analyzes customer subscription behavior, churn patterns, and revenue performance using an interactive Power BI dashboard.

The goal of the analysis is to identify customer churn drivers, revenue impact, and high-risk customer segments to support data-driven decision making for customer retention strategies.

The dataset used in this project is synthetic and contains approximately 700,000 records, simulating a real-world subscription-based SaaS / telecom business environment.

📷 Dashboard Preview

🎯 Business Objectives

The main objectives of this analysis are:
Analyze customer churn trends
Identify high-risk customers
Measure revenue loss caused by churn
Understand customer behavior and satisfaction
Evaluate subscription plan performance
Analyze revenue distribution across regions and segments
Provide insights to support customer retention strategies

🗂 Dataset Information
Attribute	Description
Dataset Type	Synthetic Dataset
Total Records	~700,000+
Industry Simulation	Subscription-based digital service
Time Coverage	Multi-year customer lifecycle

Key Data Fields:

Customer ID
Subscription Plan (Basic / Premium)
Customer Segment
Region
Acquisition Channel
Churn Status
Churn Reason
Customer Satisfaction Score
Payment Transactions
Login Activity
Data Consumption
Competitor Switching Information

🧠 Data Model Architecture

The project uses a Hybrid Star Schema with multiple fact tables, optimized for large-scale analytics and efficient reporting in Power BI.

The model separates transactional data and analytical dimensions to enable scalable performance and faster queries.

Fact Tables
subscriptions:	Subscription lifecycle data including plan type and churn status
payments:	Revenue and payment transaction data
usages_metrics:	Customer activity data such as login count and data consumption
customers:	Customer attributes including region, segment, and acquisition channel

Dimension Table
churn_reasons:	Categorizes reasons for customer churn

Measures Table
_Measure:	Contains DAX measures used to calculate KPIs and analytical metrics

This model enables cross-table analytics such as:
Revenue vs churn analysis
Usage behavior vs churn correlation
Customer segmentation insights
Revenue risk estimation


📊 Dashboard Pages:
The Power BI report consists of four analytical dashboards.

1️⃣ Executive Overview:
Provides a high-level summary of customer and revenue performance.

Key KPIs: 
Total Customers
Active Customers
Churned Customers
Churn Rate
Total Revenue
Average Revenue per Customer

Visual Insights:
Revenue trends by year
Churn rate trends
Revenue by customer segment
Revenue by region

2️⃣ Churn Analysis & Risk Insights:
Focuses on understanding why customers churn and identifying potential risk groups.

Key KPIs: 
Churned Customers
Churn Rate
High Risk Customers
Average Satisfaction of Churned Customers

Visual Insights:
Churn reason distribution
Churn rate by subscription plan
Churn rate by region
Satisfaction score vs churn relationship

3️⃣ Revenue & Monetization Insights:
Analyzes revenue drivers and the financial impact of churn.

Key KPIs: 
Total Revenue
Revenue from Active Customers
Revenue Lost due to Churn
Revenue at Risk

Visual Insights:
Revenue by subscription plan
Revenue by acquisition channel
Revenue lost by churn reaso
Average revenue per customer

4️⃣ Risk-Based Predictive Indicators:
Identifies customers likely to churn based on behavioral indicators.

Key KPIs: 
High Risk Customers
Medium Risk Customers
Revenue at Risk
Risk percentage of customer base

Visual Insights:
Revenue distribution by churn severity
Customers grouped by churn severity score
Login activity vs data consumption
Competitor switching trends


⚙️ Tools & Technologies:
Tool	Purpose
Power BI Dashboard development
DAX	KPI calculations
Power Query	Data transformation
Data Modeling	Hybrid star schema architecture

📈 Key Metrics Created (DAX)
The following key performance indicators were created using DAX:

Churn Rate
Active Customers
Churned Customers
Revenue Lost due to Churn
Average Revenue per Customer
Revenue at Risk
High Risk Customer Count

These measures allow dynamic filtering and interactive analysis across the dashboards.


💡 Key Business Insights:

Overall churn rate remains around 35%, indicating retention challenges.
Basic plan customers exhibit higher churn rates compared to premium subscribers.
Customer satisfaction shows a strong correlation with churn probability.
Pricing and competitor switching are major churn drivers.
Certain customer segments and regions contribute significantly to revenue risk.

These insights can help businesses design targeted retention strategies and optimize pricing models.

Recommended Business Actions:

Introduce short-term plans like 7-day or 15-day options for users who don’t want long subscriptions, which can help reduce early drop-offs.
Provide special retention offers, discounts, or loyalty rewards to high-risk premium customers so they feel valued and stay longer.
Set up early warning alerts based on churn risk or severity scores, so the team can take action before the customer actually leaves.
Revisit pricing strategies and create attractive bundled offers, especially where churn is highest and competition is strong.
Run focused retention campaigns for SMB and Individual customers, as saving these segments will help protect a large portion of revenue.
