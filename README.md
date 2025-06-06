# Supply Chain Data Analytics

## Overview
A comprehensive analysis of an e-commerce supply chain dataset. It explores various aspects of product performance, revenue generation, shipping logistics, and more through interactive visualizations and statistical summaries.

## Key Features

- **Data Exploration**: Loads and examines a supply chain dataset with 100 entries and 24 columns
- **Visual Analytics**: Creates interactive visualizations using Plotly Express and Plotly Graph Objects
- **Business Insights**: Analyzes relationships between product pricing, revenue, and sales volumes
- **Supply Chain Metrics**: Evaluates shipping carriers, transportation modes, and logistics costs

## Analysis Highlights

1. **Product Performance**:
   - Price vs. Revenue scatter plots with trendlines by product category
   - Sales distribution across product types (haircare, skincare, cosmetics)

2. **Revenue Analysis**:
   - Total revenue by shipping carrier
   - Revenue generation patterns by SKU

3. **Logistics Evaluation**:
   - Shipping costs across different carriers
   - Transportation mode efficiency

## How to Use

1. Ensure you have all required dependencies installed (`pandas`, `plotly`)
2. The notebook expects a `supply_chain_data.csv` file in the same directory
3. Run cells sequentially to reproduce the analysis
4. Interactive charts allow for hover tooltips and dynamic exploration

## Key Findings

- Relationship between product pricing and revenue generation varies significantly by product category
- Skincare products account for the majority of sales volume
- Shipping Carrier B handles the largest portion of shipments
- Revenue distribution across SKUs shows interesting patterns worth further investigation

## Scheduled Future Work

This analysis could be extended by:
- Adding predictive modeling for demand forecasting
- Incorporating time-series analysis of sales data
- Developing inventory optimization recommendations
- Creating a dashboard for ongoing supply chain monitoring

## Requirements

- Python 3.x
- Jupyter Notebook/Lab
- Pandas
- Plotly

To install dependencies:
```
pip install pandas plotly
```
