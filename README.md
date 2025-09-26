# Amazon Sales Analysis

## Table of Contents
- [Overview](#overview)
- [Dataset Information](#dataset-information)
- [Key Findings](#key-findings)
- [Technical Implementation](#technical-implementation)
- [Analysis Results](#analysis-results)
- [Business Recommendations](#business-recommendations)
- [File Structure](#file-structure)
- [Requirements](#requirements)
- [Author](#author)

## Overview

A comprehensive analysis of Amazon sales data to uncover actionable business insights. This project examines sales trends, product performance, geographic distribution, and operational metrics to provide data-driven recommendations for strategic business decisions.

## Dataset Information

- **Total Records**: 128,976 transactions
- **Time Period**: 2022 sales data
- **Geographic Coverage**: Multi-state sales across India
- **Product Categories**: Apparel and clothing items
- **Data Points**: 21 attributes including order details, fulfillment status, amounts, and shipping information

## Key Findings

### Sales Performance
- Massive sales peak in April reaching over 2.0 Crores
- Clear seasonal patterns indicating strategic marketing opportunities

### Geographic Distribution
- Maharashtra leads with over 1.20 Crores in sales
- Karnataka and Uttar Pradesh form secondary markets
- Highly concentrated market with top 3 states driving majority revenue

### Product Analysis
- T-shirts dominate as top revenue generator
- Apparel categories (Shirts, Blouses) form core business
- Clear product hierarchy for inventory prioritization

### Operations
- 69% orders fulfilled through Amazon FBA
- High order completion rate with minimal cancellations
- Streamlined but Amazon-dependent logistics model

## Technical Implementation

### Data Processing
- Robust date parsing with automatic format inference
- Comprehensive data cleaning and standardization
- Duplicate removal and missing value handling
- State name standardization

### Visualization
- Custom currency formatter for Indian Crores display
- Time series analysis for seasonal trends
- Geographic sales distribution mapping
- Product category performance charts
- Operational metrics visualization

### Analysis Framework
- Monthly sales trend analysis
- Top 10 state performance ranking
- Product category revenue analysis
- Fulfillment and order status distribution

## Analysis Results

### Monthly Sales Trend
Reveals critical seasonal patterns with April showing exceptional performance, indicating optimal timing for marketing campaigns and inventory planning.

### State-wise Performance
Demonstrates market concentration with Maharashtra as the dominant market, followed by Karnataka and Uttar Pradesh as key secondary markets.

### Category Performance
Identifies T-shirts as the primary revenue driver, with complementary apparel categories supporting overall business performance.

### Operational Efficiency
Shows strong reliance on Amazon FBA with high order fulfillment rates and minimal cancellation issues.

## Business Recommendations

### Strategic Marketing
- Launch major promotional campaigns in late March and throughout April
- Allocate larger marketing budgets to Maharashtra, Karnataka, and Uttar Pradesh
- Feature T-shirts, Shirts, and Blouses as headline products

### Inventory Management
- Significantly increase stock levels for best-selling items by mid-March
- Focus inventory planning on top-performing product categories
- Implement seasonal inventory strategies based on April peak

### Geographic Expansion
- Implement targeted digital advertising in high-performing states
- Optimize logistics for faster delivery in key markets
- Consider market expansion strategies for underperforming regions

### Product Development
- Explore new variations of top-performing categories
- Consider product bundling strategies for core items
- Investigate seasonal product introductions aligned with sales peaks

## File Structure

```
Amazon_sales_Analysis/
├── Amazon Sale Report.csv
├── amazon_sales_analysis.py
├── README.md
```

## Requirements

- Python
- pandas
- numpy
- matplotlib
- seaborn

## Author

**Jay Mevada**  
Date: September 15, 2025

---

This analysis provides comprehensive insights into Amazon sales performance, enabling data-driven decision making for business growth and optimization.
