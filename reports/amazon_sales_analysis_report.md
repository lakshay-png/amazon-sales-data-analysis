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