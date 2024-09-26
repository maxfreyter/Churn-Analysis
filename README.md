![Screenshot_26-9-2024_171451_](https://github.com/user-attachments/assets/d02c25e6-76d5-4e79-9c9f-d33215136528)

# Customer Churn Overview Dashboard

## Overview
This project was part of a guided case study on DataCamp for a fictional telecom company called **Databel**. The goal of the analysis was to understand the factors contributing to customer churn and provide actionable insights for reducing it. The dashboard was built using **Power BI**.

### Key Metrics
- **Total Churned Customers**: 1,796
- **Total Number of Customers**: 6,687
- **Churn Rate**: 26.86%

## Business Problem
Databel, a telecom company, faces high customer churn, which affects its revenue and growth. The purpose of this dashboard is to:
- Identify the key factors driving customer churn.
- Understand the distribution of churn across customer segments (e.g., contract type, demographics).
- Provide recommendations to improve customer retention.

## Features
1. **Churn Rate by State**:
   - A geographic visualization showing where churn is highest across different states.
2. **Churn by Contract Type**:
   - Breakdown of churn by contract type (month-to-month, one-year, two-year).
3. **Churn by Age**:
   - Visualizes churn rates across different age groups.
4. **Churn Reasons**:
   - A chart listing reasons for churn, including competition, price dissatisfaction, and network reliability.
5. **Grouped Data Consumption**:
   - Analysis of churn rate based on data consumption levels and whether the customer has an unlimited data plan.
6. **Churn by Category**:
   - A donut chart showing the distribution of churn causes, such as competitor offers and product dissatisfaction.

## Insights
- 1. **Contract Type**: Customers on month-to-month contracts have the highest churn rate, suggesting that long-term contracts may reduce churn.
- 2. **Churn by Age**: Customers who are 70 or over on average show a much higher churn rate compared customers under 70.
- 3. **Churn Reasons**: The most common reason for churn is competitors offering better deals and products.
- 4. **Geographic Distribution**: California had the highest churn rate of any state by far at 63.24%!
- 5. **Data Plan and Grouped Consumption**: Among customers who used under 5 GB of data, the churn rate of those who have an unlimited data plan was 34.71%, whereas those without an unlimited plan were much lower at 12.31%. In contrast, customers who used more than 5 GB, regardless of whether they had an unlimited plan or not, averaged higher than the total average churn rate.


## Recommendations
### 1. **Introduce Loyalty Programs for Month-to-Month Customers**
   -  Customers with month-to-month contracts have the highest churn rate. This is especially troublesome as they make up more than half of Databel's customers.
   - **Recommendation**: Offer loyalty programs or discounts for long-term contract upgrades. Provide incentives for these customers to switch to yearly plans, such as discounted rates or free add-ons for early commitments.

### 2. **Target Older Customers with Custom Packages**
   - Older customers (ages 70+) show higher churn rates. 
   - **Recommendation**: Create more flexible, personalized service packages tailored to older demographics. Perhaps bundled phone and internet services with senior discounts or tailored packages that offer help with technical issues will help increase retention. 
     
### 3. **Competitor Analysis & Competitive Pricing**
   - A significant percentage of churn is due to competitors offering better deals or pricing.
   - **Recommendation**: Regularly review competitors' offers to remain competitive. Offer a price-match guarantee or exclusive promotions for customers who are considering leaving.

### 4. **Target At-Risk Regions with Personalized Campaigns**
   - The churn rate varies significantly by state, with some regions experiencing higher churn.
   - **Recommendation**: Launch targeted retention campaigns in high-churn regions, offering special discounts or regional promotions to customers in those areas.
     
### 5. **Offer Custom Data Plans**
   -The dashboard shows a correlation between data consumption and churn, with those using between 5–10 GB having higher churn.
   - **Recommendation**: Provide more flexible or customized data plans that cater to medium users. 




## Technologies Used
- **Power BI**: For interactive data visualization and dashboard creation.

## How to View the Dashboard
1. Download the `.pbix` file from this repository.
2. Open the file using **Power BI Desktop** to interactively explore the dashboard.

