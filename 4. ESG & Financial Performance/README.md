# Financial and ESG Performance Dataset Analysis Portfolio

## Overview
This repository contains a Power BI-based portfolio project analyzing a synthetic dataset of financial and ESG (Environmental, Social, and Governance) performance for 1,000 global companies across 9 industries and 7 regions, spanning 2015 to 2025. The dataset includes financial metrics (e.g., revenue, profit margins, market capitalization) and ESG indicators (e.g., carbon emissions, water usage, ESG scores), enabling comprehensive analyses of corporate performance and sustainability trends.

The goal of this portfolio is to showcase data analysis and visualization skills using Power BI, focusing on financial forecasting, ESG-financial relationships, and industry-specific insights.

## Dataset Description
The dataset simulates realistic financial and ESG performance for 1,000 synthetic companies over 11 years (2015–2025). It consists of **11,000 rows** and **16 columns**, covering:

- **Financial Metrics**: Revenue, Profit Margin, Market Capitalization, Growth Rate
- **ESG Metrics**: Overall ESG Score, Environmental, Social, and Governance Scores, Carbon Emissions, Water Usage, Energy Consumption
- **Metadata**: Company ID, Company Name, Industry, Region, Year

### Key Features
- **Size**: 11,000 rows × 16 columns
- **Companies**: 1,000 unique entities
- **Period**: Annual data from 2015 to 2025
- **Industries**: 9 sectors (e.g., Technology, Finance, Energy)
- **Regions**: 7 geographic regions (e.g., North America, Europe)
- **Use Cases**:
  - Regression/classification (e.g., predicting market cap, ESG scores)
  - Clustering/segmentation (e.g., by industry or ESG performance)
  - Time-series forecasting (e.g., financial growth, ESG trends)
  - Exploring ESG-financial relationships for sustainable investing

For a detailed breakdown of columns, refer to the [dataset description](#dataset-description).

## Project Objectives
This portfolio leverages Power BI to:
1. Visualize financial and ESG trends over time across industries and regions.
2. Analyze the relationship between ESG performance and financial outcomes (e.g., revenue, market cap).
3. Forecast future financial and ESG metrics using time-series analysis.
4. Segment companies based on ESG and financial performance for investment strategy insights.
5. Identify high-performing industries and regions in terms of sustainability and profitability.

## Tools and Technologies
- **Power BI**: For data visualization, dashboard creation, and interactive reporting.
- **Dataset**: Synthetic Financial and ESG Performance Dataset (11,000 rows × 16 columns).
- **Additional Tools** (if applicable): Excel for preliminary data cleaning, Python for advanced preprocessing (optional).

## Analysis Plan
The portfolio will include the following analyses in Power BI:
1. **Descriptive Analytics**:
   - Summary statistics for financial (revenue, market cap) and ESG metrics (overall ESG score, carbon emissions).
   - Distribution of companies by industry and region.
2. **Time-Series Analysis**:
   - Trends in revenue, market cap, and ESG scores from 2015 to 2025.
   - Year-over-year growth rate analysis by industry.
3. **Correlation Analysis**:
   - Relationships between ESG scores and financial metrics (e.g., profit margin vs. ESG_Environmental).
   - Impact of sustainability on market capitalization.
4. **Segmentation**:
   - Clustering companies by ESG performance and financial health.
   - Industry and region-based segmentation for investment insights.
5. **Forecasting**:
   - Predict future revenue and ESG scores using Power BI's forecasting tools.
   - Identify potential high-growth companies based on historical trends.

## Power BI Dashboards
The portfolio will feature interactive Power BI dashboards, including:
- **Financial Performance Dashboard**: Visualizations of revenue, market cap, and growth rate by industry/region.
- **ESG Performance Dashboard**: Trends in ESG scores, carbon emissions, water usage, and energy consumption.
- **ESG-Finance Correlation Dashboard**: Scatter plots and heatmaps showing relationships between ESG and financial metrics.
- **Forecasting Dashboard**: Predicted financial and ESG metrics for 2025 and beyond.

## Repository Structure
```
├── data/
│   └── financial_esg_dataset.csv  # Synthetic dataset
├── power_bi/
│   └── portfolio_dashboard.pbix   # Power BI file with dashboards
├── docs/
│   └── README.md                 # This file
└── images/
    └── dashboard_screenshots/     # Screenshots of Power BI dashboards
```

## Getting Started
1. **Download the Dataset**: Obtain the synthetic dataset (`financial_esg_dataset.csv`) from the source or repository.
2. **Set Up Power BI**:
   - Install Power BI Desktop (free) from the [official website](https://powerbi.microsoft.com/).
   - Import the dataset into Power BI for analysis.
3. **Explore Dashboards**:
   - Open the `portfolio_dashboard.pbix` file in Power BI Desktop.
   - Interact with the dashboards to explore financial and ESG insights.
4. **Reproduce Analysis**:
   - Follow the steps in the Power BI file to recreate visualizations and forecasts.
   - Modify queries or visuals to explore additional insights.

## Potential Insights
- Which industries have the highest ESG scores, and how do they correlate with financial performance?
- Are companies in certain regions (e.g., Europe) more sustainable than others?
- Can high ESG scores predict stronger revenue growth or market cap?
- Which companies are poised for growth based on historical financial and ESG trends?

## Future Improvements
- Integrate external datasets (e.g., real-world ESG benchmarks) for comparison.
- Incorporate machine learning models (e.g., via Power BI's Python/R integration) for advanced predictions.
- Expand dashboards to include real-time data feeds (if applicable).

## Acknowledgments
- Dataset Source: Synthetic Financial and ESG Performance Dataset
- Tools: Microsoft Power BI for visualization and analysis

## Contact
For questions or feedback, please reach out via [your contact information or portfolio website].

---

*This portfolio is a work in progress and will be updated as new analyses and dashboards are developed.*