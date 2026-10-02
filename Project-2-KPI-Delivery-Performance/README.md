# KPI & Delivery Performance

## Project Overview

This project analyzes delivery performance in the Olist Brazilian E-Commerce dataset to identify delivery-related business problems and understand their impact on customers.

The analysis focuses on order fulfillment status, delivery performance, delivery trends over time, geographic differences, product characteristics, seller performance, and customer review scores.

The objective is to transform operational order data into actionable business insights that can help identify where delivery performance problems occur and which areas require further attention.

## Business Questions

- How many orders were successfully delivered, still in progress, or unsuccessful?
- What proportion of delivered orders were early, on time, or late?
- How significant is the late delivery problem?
- When did late deliveries increase?
- Which states have higher late delivery rates?
- Which product categories have higher late delivery rates?
- Is product weight associated with late deliveries?
- Are late deliveries concentrated among specific sellers?
- How does delivery performance relate to customer review scores?
- What business areas should be prioritized based on the analysis?

## Tools

- Excel
- Power Query
- Looker Studio

## Data Preparation

Excel and Power Query were used for data cleaning, transformation, merging, filtering, and preparation of the analytical dataset.

The analysis includes the creation of calculated fields and categories for:

- Order Fulfillment Status
- Delivery Performance
- Delivery Delay Flag
- Delivery Month
- Delivery Year
- Late Delivery Rate
- Product Weight
- Review Category

The prepared data was then used for analysis and dashboard development in Looker Studio.

## Analysis Framework

### 1. Order Fulfillment Status

Orders were classified into three operational categories:

- Delivered
- In Progress
- Unsuccessful

Orders with statuses such as shipped, invoiced, processing, approved, and created were treated as orders that were still in progress.

### 2. Delivery Performance

Delivered orders were analyzed based on the difference between the actual delivery date and the estimated delivery date.

Orders were classified as:

- Early
- On Time
- Late

Late delivery analysis was performed using delivered orders.

### 3. KPI Problem Analysis

The main KPIs used to evaluate the delivery problem include:

- Total Orders
- Delivered Orders
- Late Orders
- Late Delivery Rate
- Unsuccessful Orders

These KPIs provide an overview of the scale and severity of delivery performance issues.

### 4. Time Analysis

Monthly delivery data was analyzed to identify periods in which late deliveries increased.

This analysis helps identify changes in delivery performance over time.

### 5. Geographic Analysis

Delivery performance was analyzed across Brazilian states to identify geographic areas with higher late delivery rates.

The analysis compares delivered orders, late orders, and late delivery rates by state.

### 6. Product Analysis

Product categories were analyzed to identify categories with higher late delivery rates.

Product weight was also incorporated into the analysis to examine whether heavier products are associated with higher late delivery rates.

### 7. Seller Analysis

Seller-level delivery performance was analyzed to determine whether late deliveries were concentrated among particular sellers.

### 8. Customer Impact

Delivery performance was compared with customer review scores to examine the relationship between delivery outcomes and customer satisfaction.

## Project Workflow

1. Data Collection
2. Data Cleaning & Transformation using Excel and Power Query
3. Order Fulfillment Classification
4. Delivery Performance Analysis
5. Time & Geographic Analysis
6. Product & Seller Analysis
7. Customer Impact Analysis
8. Dashboard Development using Looker Studio
9. Business Insights

## Dashboard

The interactive dashboard was developed using Looker Studio.

[View Interactive Dashboard](https://datastudio.google.com/reporting/9524c0e5-1720-4b13-be91-d36c1936554b)

The dashboard presents key delivery KPIs and visual analyses covering:

- Order Fulfillment Status
- Delivery Performance
- Late Delivery Trend
- Late Delivery by State
- Product Category Performance
- Product Weight
- Seller Performance
- Customer Review Performance

## Key Insights

The analysis is designed to identify the main areas contributing to delivery performance problems and translate the findings into business-oriented insights.

The detailed findings and recommendations are presented through the dashboard and final analysis.
