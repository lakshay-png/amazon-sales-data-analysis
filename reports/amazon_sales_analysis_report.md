# Amazon Sales Data Analysis

## Comprehensive Business Performance Analysis

### Prepared By
Lakshay Karwa

### Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Git & GitHub

### Project Duration
25-Day Data Analytics Project

# Executive Summary

This project analyzes Amazon sales data to identify trends, customer behavior, fulfillment performance, product performance, and geographical sales patterns.

The analysis was conducted using Python-based data analytics tools including Pandas, NumPy, Matplotlib, and Seaborn.

The project identified key revenue drivers, customer purchasing patterns, operational challenges, and strategic opportunities that can support business decision-making.

Major findings include:

- Strong revenue contribution from a limited number of product categories.
- Significant concentration of sales within specific geographical regions.
- A customer base primarily composed of B2C buyers.
- A cancellation rate of approximately 14%, representing an opportunity for operational improvement.
- Clear sales trends and demand patterns across the analysis period.

# Business Problem

Amazon processes thousands of orders across multiple product categories, customer segments, and geographical regions.

Without proper analysis, it is difficult to understand:

- Which products drive revenue?
- Which regions contribute most sales?
- How customers behave?
- How efficiently orders are fulfilled?
- What operational improvements can increase profitability?

The objective of this project is to analyze Amazon sales data and generate actionable business insights.

# Project Objectives

The project focuses on the following business objectives:

1. Sales Overview Analysis
2. Product Performance Analysis
3. Fulfillment Analysis
4. Customer Segmentation
5. Geographical Analysis
6. Time Series Analysis
7. KPI Development
8. Business Insight Generation
9. Strategic Recommendations

# Dataset Description

The dataset contains Amazon sales transactions and order-level information.

## Dataset Characteristics

- Total Records: 128,976
- Total Columns: 21 (before cleaning)
- Cleaned Columns: 19
- Order Information
- Product Categories
- Fulfillment Details
- Customer Segment Information
- Geographical Data
- Revenue Information

## Key Variables

- Order ID
- Date
- Category
- Amount
- Quantity
- Fulfilment
- Status
- B2B
- State
- City

# Data Cleaning Process

Several preprocessing steps were performed before analysis.

## Missing Value Treatment

- Investigated missing values in Amount and Currency columns.
- Retained cancelled orders due to their business significance.
- Removed records with missing geographical information where appropriate.

## Column Removal

The following columns were removed:

- New
- PendingS

These columns contained 100% missing values.

## Duplicate Removal

- Identified duplicate records.
- Removed duplicates to ensure data quality.

## Data Type Conversion

- Converted Date column into datetime format for time series analysis.

# Sales Performance Analysis

## Overview

The sales analysis focused on understanding overall business performance through revenue trends, order volume, and order status distribution.

## Key Findings

- The dataset contained over 128,000 orders.
- Total revenue exceeded ₹70 million.
- Revenue peaked during April 2022.
- The majority of orders were successfully fulfilled.
- Approximately 14.2% of orders were cancelled.

## Business Interpretation

The business demonstrated strong sales performance with a large transaction volume and healthy revenue generation. However, the cancellation rate indicates an opportunity to improve operational efficiency and recover lost revenue.

# Product Performance Analysis

## Overview

Product analysis was conducted to identify categories contributing the most revenue and customer demand.

## Key Findings

- The T-shirt category generated the highest revenue.
- Apparel products dominated overall sales performance.
- Customer demand was concentrated within a few categories.
- Certain categories generated significantly higher revenue per unit sold.

## Business Interpretation

The results suggest that inventory planning and marketing efforts should prioritize high-performing apparel categories to maximize revenue generation.

# Fulfillment Analysis

## Overview

Fulfillment analysis evaluated shipping performance and order processing efficiency.

## Key Findings

- Amazon fulfilled the majority of orders.
- Standard shipping was the most commonly selected service.
- Most orders were successfully shipped.
- Approximately 14.2% of orders were cancelled.

## Business Interpretation

The fulfillment process performs effectively overall; however, reducing cancellations could improve customer satisfaction and increase realized revenue.

# Customer Segmentation Analysis

## Overview

Customer segmentation focused on comparing B2B and B2C purchasing behavior.

## Key Findings

- The customer base was primarily composed of B2C customers.
- B2C customers generated the majority of revenue.
- B2B customers represented a smaller but strategically important segment.
- Customer purchasing behavior varied across categories.

## Business Interpretation

Targeted marketing strategies can be developed for different customer segments to improve retention and increase customer lifetime value.

# Geographical Analysis

## Overview

Geographical analysis identified regions contributing the highest order volume and revenue.

## Key Findings

- Maharashtra generated the highest revenue.
- Major metropolitan cities contributed a significant share of total sales.
- Revenue was concentrated in a limited number of states.

## Business Interpretation

The company should prioritize logistics optimization and marketing investments in high-performing regions while exploring expansion opportunities in underpenetrated markets.

# Time Series Analysis

## Overview

Time series analysis examined revenue and order trends over time.

## Key Findings

- Revenue peaked during April 2022.
- Sales performance fluctuated across the analysis period.
- Certain weekdays generated higher revenue than others.
- The moving average revealed underlying sales trends.

## Business Interpretation

Understanding seasonal demand patterns can support forecasting, inventory planning, and promotional scheduling.

# Strategic Recommendations

Based on the analysis, the following recommendations are proposed:

## 1. Prioritize High-Revenue Categories

The highest revenue-generating product categories should receive priority in inventory management, promotional campaigns, and supply chain planning.

**Expected Benefit:**
- Increased revenue
- Improved product availability
- Higher customer satisfaction

---

## 2. Reduce Order Cancellations

The cancellation rate of approximately 14% indicates opportunities for operational improvement.

Recommended actions include:
- Better inventory forecasting
- Improved order validation
- Faster order confirmation
- Enhanced customer communication

**Expected Benefit:**
- Higher realized revenue
- Better customer retention

---

## 3. Expand High-Performing Regions

States contributing the highest revenue should receive increased marketing investment and logistics support.

**Expected Benefit:**
- Increased regional sales
- Improved delivery performance

---

## 4. Optimize Fulfillment Operations

Monitor merchant fulfillment performance and identify operational bottlenecks.

**Expected Benefit:**
- Lower cancellation rates
- Faster deliveries
- Better customer experience

---

## 5. Segment Marketing Campaigns

Develop different marketing strategies for B2B and B2C customers.

Examples:

- Personalized offers for B2C customers
- Bulk purchase incentives for B2B customers

**Expected Benefit:**
- Higher conversion rates
- Increased customer loyalty

# Business Impact Analysis

Implementing the recommendations from this analysis can create measurable business value.

## Revenue Growth

Focusing on top-performing products and regions can increase sales through better inventory planning and targeted promotions.

## Cost Reduction

Reducing cancellations and improving fulfillment efficiency can lower operational costs.

## Customer Satisfaction

Improved delivery performance and better product availability can enhance customer experience.

## Decision Support

The KPI dashboard developed in this project enables management to monitor business performance and make data-driven decisions.

# Project Limitations

Although the analysis provides valuable insights, several limitations should be considered.

- The dataset covers a limited time period.
- Customer demographic information was unavailable.
- Product ratings and reviews were not included.
- Marketing campaign data was unavailable.
- External factors such as holidays and promotions were not considered.

# Future Scope

The project can be extended in several ways:

- Develop a Power BI dashboard.
- Build sales forecasting models using Machine Learning.
- Predict order cancellations using classification algorithms.
- Perform customer lifetime value analysis.
- Conduct market basket analysis for product recommendations.