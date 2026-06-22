# Part 3: Regression-Based Business Insights

## Business Problem Summary

The leadership team wants to understand which factors are associated with monthly sales performance across stores. The objective is to identify important drivers of sales and provide recommendations for improving business performance.

## Dataset Description

The dataset contains monthly performance information for retail stores.

### Dependent Variable

monthly_sales

### Potential Independent Variables

- marketing_spend
- footfall
- avg_discount_pct
- staff_count
- inventory_availability_pct
- competitor_distance_km
- holiday_flag
- customer_rating
- region
- store_type

### Numerical Variables

- marketing_spend
- footfall
- avg_discount_pct
- staff_count
- inventory_availability_pct
- competitor_distance_km
- customer_rating
- monthly_sales
- monthly_profit

### Categorical Variables

- region
- store_type
- month

### Variables That May Need Transformation

- region (dummy variables)
- store_type (dummy variables)

### Variables That May Not Be Useful For Regression

- store_id

Reason:

store_id is only an identifier and does not explain sales performance.
