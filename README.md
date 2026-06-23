# nuteshsairam_bitsom_ba_2511693_part1_data_cleaning

# Data Cleaning and Quality Assessment Project

## Problem Summary
This project focuses on cleaning, validating, and analyzing an e-commerce orders dataset. The objective is to improve data quality and generate business-ready summary reports.

## Dataset Description
The dataset contains order, customer, product, sales, discount, shipping, and profit-related information.

## Tools Used
- Microsoft Excel
- Pivot Tables
- Data Validation
- Formula-Based Calculations

## Cleaning Steps Performed
- Removed duplicate records
- Replaced missing region values with "Unknown"
- Replaced missing discount values with 0
- Standardized date formats
- Created calculated columns
- Generated data quality reports

## Business Rules Applied
- Missing region values replaced with "Unknown"
- Missing discounts replaced with 0
- Date issues flagged for review
- Shipping delay calculated using order and ship dates

## Summary of Data Quality Issues Found
- 25 missing region values
- 18 missing discount values
- 20 duplicate records
- 129 date parsing issues
- 15 negative discount records

## Summary of Final Pivot Reports
- Sales and profit by region
- Sales and profit by category and sub-category
- Order count by ship mode
- Profit margin by segment
- Failed orders by region
- Monthly sales trend

## Key Business Insights
- Completed orders dominate overall transactions
- Some regions contribute significantly more sales and profit
- Date quality issues require monitoring
- Discount inconsistencies were identified and corrected

## Assumptions and Limitations
- Missing discounts assumed as zero
- Unknown used for missing regions
- Some date records remain flagged for manual review

## Screenshots Included
- Raw dataset preview
- Cleaned dataset preview
- Pivot summary 1
- Pivot summary 2
