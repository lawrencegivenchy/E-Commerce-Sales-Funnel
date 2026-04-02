# E-Commerce Sales Funnel Analysis

## Project Overview
End-to-end sales funnel analysis for an e-commerce platform using SQL on Databricks and Power BI. 
The goal was to identify drop-off points across the customer journey and understand revenue performance by traffic source.

## Tools Used
- **SQL** (Databricks) — data extraction and analysis
- **Power BI** — interactive dashboard and visualizations

## Dataset
- 9,381 events across 5,000 unique users
- 5 event types: page_view, add_to_cart, checkout_start, payment_info, purchase
- Source: FBref-style synthetic e-commerce event data

## Analysis Breakdown

### 1. Sales Funnel Stages
Tracked unique users through each stage of the funnel from page view to purchase, including drop-off rates at every step.

### 2. Conversion Rates
Calculated step-by-step conversion rates across the funnel to identify the biggest drop-off points.

### 3. Funnel by Traffic Source
Compared views, carts and purchases across organic, social, paid ads and email traffic sources.

### 4. Time to Conversion
Measured average time in minutes for users to move from page view to cart and cart to purchase.

### 5. Revenue Analysis
Calculated total revenue, average order value, revenue per buyer and revenue per visitor.

## Dashboard
![Dashboard](Sales_Funnel_Analysis.pdf)

## Key Findings
- Overall funnel conversion rate from page view to purchase was 18.5%
- Organic traffic drove the highest volume of purchases
- Average total journey from first view to purchase was 24.63 minutes
- Total revenue across the period was R87.98K

## SQL Queries
Full analysis available in [`Funnel_Analysis.sql`](Funnel_Analysis.sql)
