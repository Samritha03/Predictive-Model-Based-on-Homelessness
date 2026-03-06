## Predictive Model Based on Homelessness
A sophisticated data science framework designed to identify and forecast structural, community-level drivers of homelessness across the United States. By integrating **16+ years of multi-source longitudinal data**, this project utilizes advanced ensemble learning models to provide actionable insights for resource optimization and policy intervention.

### Overview
Traditional homelessness research often focuses on individual-level predictors; however, this project shifts the lens to **structural community-level factors**. By analyzing approximately **400 Continuums of Care (CoC)** funded by HUD, the framework identifies how variables like rent levels, economic conditions, and housing inventory influence homelessness trends.

### Key Objectives
- Forecast regional homelessness trends using historical data from 2007–2023.
- Identify key community predictors—such as renter household rates and housing cost burdens—that drive homelessness.
- Optimize resource distribution by enabling early identification of high-risk communities for policymakers.

### Technical Stack
- **Language:** Python, R.
- **Data Processing:** Pandas, NumPy (for complex multi-source ETL).
- **Machine Learning:** Histogram-Based Gradient Boosting, Random Forest, XGBoost, Linear Regression.
- **Visualization:** Matplotlib, Seaborn (for trend analysis and feature importance).
- **Data Sources:** HUD (HIC/PIT counts), U.S. Census Bureau (ACS), and NOAA (Weather data).

### Key Findings & Impact
- **High-Precision Results:** Achieved an RMSE as low as 0.31 for predicting family-specific homelessness rates.
- **Primary Drivers:** Identified Renter Household Rates and Total Year-Round Beds as the most impactful structural features.
- **Policy Insight:** Findings suggest that interventions focusing on rent stabilization and high-risk community targeting are critical for long-term reduction.

