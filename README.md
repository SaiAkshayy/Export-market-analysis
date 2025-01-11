# Export-market-analysis

## Project Overview
This project analyzes Russia's export data to uncover key trends, highlight the impact of geopolitical and economic events, and forecast potential growth areas. By leveraging machine learning, dimensional modeling, and visualizations, we provide actionable insights into Russia's trade patterns and commodity distributions over 14 years.

**Key Objectives:**
1. Identify major commodities and their trade dynamics.
2. Explore the evolution of Russia's trading partnerships.
3. Analyze the impact of global and local economic events on export trends.
4. Develop scalable dimensional models for efficient analysis.


## Data & Methodology
**Dataset:**
- **Source:** [Kaggle Dataset: Russia-to-World Trade](https://www.kaggle.com/datasets/pranav941/russia-to-world-trade14m-data-points)
- **Scope:** Export data including trade value, commodities, and partner countries from 2007-2020.

**Data Processing:**
- **ETL:** Cleaned, standardized, and wrangled raw data using `csvkit` and Python.
- **Dimensional Modeling:** Created fact tables for trade metrics and dimension tables for countries, commodities, and quantities.

**Analysis Techniques:**
- SQL-based querying and dimensional modeling for structured analysis.
- Visualization tools (Matplotlib, Pyplot) to explore and present findings.
<img src="https://github.com/user-attachments/assets/3e73275e-32d1-44b6-866b-936e1835a736" width = 900 height = 500>

## Key Findings

### 1. Major Trading Partners
- **Top Partners (2007-2020):** Netherlands, China, Germany, Turkey, and Italy.
- **Trend Analysis:** 
  - China emerged as the dominant partner post-2014, surpassing the Netherlands.
  - Economic sanctions and geopolitical tensions significantly impacted exports to Western countries.

<img src ="https://github.com/user-attachments/assets/d90fa0cd-245e-40af-8369-10ad89b3796a" width = 600 height = 400>


### 2. Export Commodities
- **Key Exports:** Petroleum (60% of total revenue), followed by manufactured goods and precious metals.
- **Trends:** 
  - Petroleum peaked in 2012 with a decline post-2015 due to falling oil prices and geopolitical events.
  - Precious metals surged post-2016, becoming a growing revenue source.

**Visualization:**
![Pie Chart: Commodity Distribution](#)  
*A pie chart showing export shares by major commodity types.*


### 3. Economic Impact Analysis
- Global recessions (2009) and the 2014 Russian financial crisis led to sharp declines in export values.
- Economic recovery post-2016 was driven by diversified commodity trade and partnerships with China.

**Visualization:**
![Line Graph: Export Trends Over Time](#)  
*A line graph comparing annual export values across top trading partners.*


## Recommendations
1. **Diversify Export Portfolio:** Reduce dependency on petroleum by boosting manufacturing and technology exports.
2. **Strengthen Trade with Emerging Markets:** Expand partnerships with non-traditional allies to mitigate geopolitical risks.
3. **Invest in Data Infrastructure:** Utilize dynamic dashboards for real-time trade monitoring and forecasting.


## Future Work
- Incorporate additional features like transportation modes and import metrics for holistic trade analysis.
- Leverage predictive models for forecasting export values under varying geopolitical scenarios.
- Enhance data accessibility through interactive visualizations and dashboards.
