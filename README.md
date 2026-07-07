Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and historical trading performance using real-world cryptocurrency trading data from the Hyperliquid exchange. The objective is to identify how different market sentiments influence trader behavior, profitability, trading volume, leverage usage, and overall trading performance.

The project combines two datasets: a Bitcoin Fear & Greed Index dataset containing daily market sentiment classifications and a Historical Trader Dataset containing trade execution details such as account information, trading symbol, execution price, position size, leverage, trade direction, and realized profit/loss (PnL). By merging these datasets on the trading date, the analysis uncovers hidden patterns and provides actionable insights that can support data-driven trading strategies.

Objectives
Analyze trader performance under different market sentiment conditions.
Compare profitability during Fear and Greed market phases.
Measure trader win rates and loss rates.
Identify high-performing traders and trading assets.
Study leverage usage across different market sentiments.
Discover relationships between market psychology and trading behavior.
Generate business insights for improving trading strategies.
Datasets Used
1. Bitcoin Fear & Greed Index

Contains daily Bitcoin market sentiment.

Features

Date
Fear & Greed Value
Classification (Extreme Fear, Fear, Neutral, Greed, Extreme Greed)
2. Historical Trader Dataset (Hyperliquid)

Contains real trading records.

Features

Account
Symbol
Execution Price
Trade Size
Side (Buy/Sell)
Timestamp
Closed Profit & Loss (PnL)
Leverage
Fees
Event Type
Position Details
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Plotly
SciPy
Scikit-learn
OpenPyXL
Jupyter Notebook
Methodology
Data Preprocessing
Imported CSV and Excel datasets.
Cleaned missing and duplicate records.
Converted timestamps into datetime format.
Standardized date formats.
Merged datasets using trading date.
Exploratory Data Analysis
Summary statistics
Missing value analysis
Distribution analysis
Outlier detection
Correlation analysis
Feature Engineering
Daily Profit
Win/Loss Indicator
Profit Percentage
Daily Trade Count
Average Leverage
Daily Trading Volume
Trader Ranking
Statistical Analysis
Pearson Correlation
ANOVA Test
Distribution Analysis
Group-wise Performance Comparison
Visualizations

The project includes multiple visualizations, including:

Profit & Loss Distribution
Market Sentiment Distribution
Daily Trading Volume
Win Rate by Sentiment
Average Profit by Sentiment
Leverage Analysis
Buy vs Sell Distribution
Top Performing Traders
Top Performing Coins
Correlation Heatmap
Daily Profit Trend
Boxplots
Histograms
Scatter Plots
Pie Charts
Violin Plots
Key Insights
Compared trader profitability across Fear, Neutral, and Greed market conditions.
Measured how market sentiment affects trading activity.
Identified which sentiment leads to higher average profits.
Evaluated leverage usage during volatile market periods.
Ranked traders based on cumulative realized profit.
Analyzed asset-wise trading performance.
Identified patterns in trading behavior under different market emotions.
Business Value

The analysis helps traders and financial analysts understand how market psychology impacts trading performance. The findings can support:

Better risk management
Improved position sizing
Smarter leverage decisions
Sentiment-based trading strategies
Portfolio optimization
Data-driven investment decisions
Project Deliverables
Cleaned and merged datasets
Exploratory Data Analysis (EDA)
Statistical analysis
Professional visualizations
Trader performance dashboard
Business insights and recommendations
Exported analysis reports
Fully documented Python code
Skills Demonstrated
Data Cleaning
Data Wrangling
Exploratory Data Analysis (EDA)
Feature Engineering
Statistical Analysis
Data Visualization
Business Intelligence
Financial Data Analysis
Python Programming
Analytical Thinking
Report Writing
Insight Generation
