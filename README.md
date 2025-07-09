# Bank of Canada Yield Curve Analysis

## 📘 Overview
This project leverages the Bank of Canada Valet Web Service to extract, clean, analyze, and visualize Canadian government bond and T-bill yield data. It focuses on the yield curve over the past 10 years, providing insights into spreads between tenors.

## 🎯 Objectives
Connect to an external API (Bank of Canada Valet API)

Import and clean financial time-series data

Analyze yield relationships and calculate spreads

Visualize yield curves and spread changes over time

## 🛠 Tools Used
You may use any of the following tools:

Python (Pandas, Requests, Matplotlib/Seaborn)

SQL

Power BI

Power Query

Excel
## Tasks
📥 1. Connect to External Data Source
Use the Bank of Canada Valet API to retrieve 10 years of historical yield data.

API Documentation:
https://www.bankofcanada.ca/valet/docs

🧹 2. Import and Clean Data
Data Series:

TB.CDN.1Y.MID → 1-Year Treasury Bill Yield

BD.CDN.2YR.DQ.YLD → 2-Year Benchmark Bond Yield

BD.CDN.5YR.DQ.YLD → 5-Year Benchmark Bond Yield

BD.CDN.10YR.DQ.YLD → 10-Year Benchmark Bond Yield

Cleaning Steps:

Handle missing or null values

Convert data types (e.g., dates and numeric values)

Rename columns for readability and consistency

📊 3. Analyze the Data
Examine yield trends across tenors

Calculate spreads between maturities:

2Y - 1Y

5Y - 2Y

10Y - 5Y

Document findings and observe patterns, such as yield curve inversion or steepening/flattening

📈 4. Visualizations
Create charts to visualize:

Individual yield time series

Yield curve spreads over time

Correlations or trend changes

Suggested Libraries/Tools:

Matplotlib / Seaborn (Python)

Power BI Dashboards

Excel Charts

## Descirption
For this assignment, I conducted a comprehensive analysis of bond yields from 2014 to 2024 consisting of descriptive statistical analysis, yield spread, scatter plots, moving averages, a correlation matrix, seasonal decomposition, rolling volatility, rolling correlation, and principal component analysis (PCA). With these in-depth analyses, a clearer understanding of bond yield dynamics was achieved, highlighting key trends, relationships, and volatility patterns that provide valuable insights into market behavior and potential economic conditions moving forward. In addition, I have also implemented all analyses from fundamental to advanced in a condensed Jupyter Notebook for a concise way to observe all visualizations.

Thank you!

Files Description:
1. A Comprehensive Report that documents my process, technical approach, findings, and insights regarding the data and visualizations.
2. An Excel file that performs data cleaning, data extraction through APIs, and fundamental analysis, along with basic visualizations.
3. A PowerBI file that contains both fundamental & advanced analysis along with advanced interactive visualizations and dashboards.
4. A PDF document that includes a detailed overview of the Power BI dashboard.  
5. An JupyterNotebook with additional advanced analysis and visualizations all fully implemented using only Python. This file also contains all previous analysis done in both Excel and PowerBI, please expand all fields to view these.

Technologies Utilized in The Assignment: Power Query, PivotTable, PivotChart, Formulas, DAX, Python, Numpy, scikit-learn, Matplotlib, Seaborn
## Technical Summary and Conclusion
This analysis involved a comprehensive examination of 10 years of Treasury bill (T-bill) and benchmark bond yield data from the Bank of Canada. The following technical steps were undertaken:
              1. Data Retrieval and Cleaning: The Bank of Canada Valet API was accessed to retrieve historical T-bill and bond yield data, followed by data cleaning to ensure accuracy and consistency.
              2. Statistical Analysis: Statistical analyses were performed to identify yield trends, volatility patterns, and yield spreads, providing insights into market sentiment.
              3. Yield Spread Calculation: Yield spreads between different tenors were calculated to evaluate economic signals and fluctuations in investor confidence.
              4. Correlation Analysis: The correlation between adjacent yield tenors was analyzed to understand their relationships and movement patterns over time.
              5. Advanced Analytical Techniques: Principal Component Analysis (PCA) was employed to uncover underlying factors influencing bond yields, and rolling volatility assessments were conducted to examine fluctuations across different maturities.
              6. Visualization: Visual representations, including yield curves and volatility heatmaps, were created to effectively communicate findings and facilitate the interpretation of data trends.

The analysis of the T-bill and benchmark bond yield data highlights key insights into the bond market's behavior. Longer-term bond yields, such as the 10-year bond, displayed greater stability, while shorter-term yields, like the 1-year T-bill, were more volatile and sensitive to economic changes. Yield spreads indicated economic sentiment, with a flattening curve signaling pessimism during uncertainties and wider spreads reflecting confidence in growth. Correlation analysis showed that yields tend to move in tandem, while advanced techniques, such as PCA, provided deeper insights into yield dynamics. Overall, this analysis emphasizes the importance of monitoring yield trends for informed investment decisions amid evolving economic conditions. This technical framework supports a robust understanding of bond yield dynamics and aids in navigating the complexities of the financial landscape.

