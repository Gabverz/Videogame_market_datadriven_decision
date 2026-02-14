# Video Game Industry Analysis Project - Market Trends and Sales Prediction

### Problem Context:
Development of a comprehensive data analysis to understand video game industry trends and identify the most promising platforms, genres, and regions for game development and marketing strategies, using historical sales data from 1980-2016 to make predictions for 2017.

### Objective:
Analyze gaming market patterns across different platforms, genres, regions, and time periods to provide strategic insights for game publishers and developers, focusing on identifying the most profitable segments and emerging trends.

Technical Competencies Used:
Exploratory Data Analysis (EDA):
- Investigation of gaming dataset with 16,444 records across multiple dimensions (platforms, genres, regions, ratings)
- Analysis of temporal trends showing platform lifecycles and market evolution
- Identification of market leaders and emerging platforms over nearly 40 years

Data Preprocessing:
- Handling missing values in critical columns (name, year_of_release)
- Data type conversions and standardization (critic_score normalization)
- Feature engineering (total_sales calculation)
- Data filtering and scope definition (2014-2016 focus period)

Advanced Analytics:
- Platform lifecycle analysis showing ~5-year dominance patterns
- Regional market analysis (North America, Europe, Japan)
- Genre performance analysis across different markets
- Correlation analysis between critic/user scores and sales performance
- Market share calculations and competitive analysis

Statistical Hypothesis Testing:
- T-tests comparing user ratings between platforms (Xbox One vs PC)
- Statistical comparison of genre preferences (Action vs Sports)
- Significance testing with proper variance analysis
- Statistical validation of market insights

Data Visualization:
- Time series analysis showing platform evolution
- Bar charts for market share analysis
- Scatter plots for correlation analysis
- Box plots for distribution analysis across platforms

### Main Libraries:
- pandas: Data manipulation, grouping, and pivot operations
- numpy: Mathematical operations and data handling
- matplotlib: Comprehensive data visualization
- scipy.stats: Statistical hypothesis testing (t-tests)

### Final Results:
Comprehensive market analysis revealing key strategic insights:

Platform Insights:
- PS4 identified as the dominant platform for 2017 predictions
- Platform lifecycle patterns showing ~5-year dominance cycles
- Xbox One and PS4 as the primary growth platforms (2014-2016)

Regional Analysis:
- North America: 43.85% market share, Xbox preference
- Europe: 41.78% market share, similar to NA patterns
- Japan: 14.37% market share, strong preference for 3DS platform

Genre and Rating Insights:
- Action and Shooter genres dominate across all regions
- Mature-rated games (17+) generate highest sales globally
- Strong correlation between critic scores and sales performance

Statistical Validation:
- No significant difference in user ratings between Xbox One and PC platforms
- Significant difference confirmed between Action and Sports genre ratings
- Statistical significance established at 95% confidence level

The project demonstrates proficiency in end-to-end business analytics, from data preprocessing through statistical validation to strategic business recommendations for the gaming industry.
