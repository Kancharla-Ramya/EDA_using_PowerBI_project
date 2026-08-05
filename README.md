Title:
Exploratory Data Analysis of the ShopTrail E-Commerce App Using Power BI

Project Overview
This project analyzes ShopTrail, a fictional mobile-first e-commerce app selling products across Electronics, Fashion, Home, Beauty, Sports, and Books. The dataset captures the app's user base, in-app behavior, purchase transactions, product catalog, and marketing campaign performance. The aim is to build a governed Power BI data model and uncover how users engage with the app, what drives revenue and profitability, and how effective marketing campaigns are at acquiring and converting users.

Dataset Description
The dataset consists of 11 interconnected tables (7 dimension and 4 fact) totaling approximately 630,000 records, structured as a star schema. It includes qualitative variables (gender, device type, subscription plan, payment method) and quantitative variables (session duration, order value, profit, campaign spend, conversions). Core tables include Users, Products, Sessions, AppEvents, Purchases, and Campaigns, supporting engagement, revenue, and marketing analysis.

Project Objectives
1.	To analyze how users engage with the ShopTrail app across sessions, screens, and devices.
2.	To identify the most profitable product categories and top-selling items.
3.	To determine which countries, channels, and campaigns drive the highest revenue.
4.	To study the relationship between discounting, order value, and profit margin.
5.	To examine marketing ROI and conversion effectiveness across acquisition channels.

Methodology
The analysis follows a structured Power BI workflow. First, the eleven tables are imported and cleaned in Power Query — correcting data types, removing duplicates, handling missing values, and standardizing inconsistent text. Tables are then related in a star schema with dimension tables filtering fact tables, and role-playing date tables are built for time intelligence. Calculated columns and DAX measures are created to summarize revenue, engagement, and marketing performance, and the results are visualized through an interactive, multi-page dashboard.
Key Performance Indicators (KPIs)
●	Total Revenue and Profit Margin %
●	Average Order Value
●	Sessions per User and Average Session Duration
●	Conversion Rate (session-to-purchase)
●	Marketing ROI and Cost per Acquisition

Data Visualization Approach
●	Bar and column charts to compare revenue across categories, countries, and platforms.
●	Line charts to trend revenue, sessions, and conversions over time.
●	Map visuals to show user and revenue distribution by country.
●	Funnel and scatter charts to analyze screen-to-screen drop-off and scroll depth vs. conversion.
●	Decomposition Tree and Key Influencers visuals to surface AI-driven insights.

Key Insights:
The analysis is expected to show that a small set of product categories and countries drive the majority of revenue, while discounting beyond a certain threshold erodes profit margin. Paid acquisition channels are expected to show a wide spread in ROI, with organic and referral users showing stronger retention despite lower initial spend. Engagement metrics such as scroll depth and session duration are expected to correlate with a higher likelihood of purchase.
Conclusion:
This study highlights how a well-modeled Power BI dashboard can turn raw app, transaction, and campaign data into decision-ready insight for an e-commerce business. By combining clean data modeling, DAX-driven KPIs, and interactive, AI-assisted visualizations, ShopTrail's stakeholders can identify what drives revenue and engagement, and where to focus marketing and product investment going forward.




## Power BI (.pbix) File
The Power BI file is larger than GitHub's file size limit.

Download it here:
[https://drive.google.com/your-link](https://drive.google.com/file/d/1pQmJn0SkTGlTl6qXCP5ZFD_aphMpNRMY/view?usp=sharing)
