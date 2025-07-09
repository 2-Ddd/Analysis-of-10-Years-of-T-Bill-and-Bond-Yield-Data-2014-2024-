Bank of Canada Yield Curve Analysis

📘 Overview
This project leverages the Bank of Canada Valet Web Service to extract, clean, analyze, and visualize Canadian government bond and T-bill yield data. It focuses on the yield curve over the past 10 years, providing insights into spreads between tenors.

🎯 Objectives
Connect to an external API (Bank of Canada Valet API)

Import and clean financial time-series data

Analyze yield relationships and calculate spreads

Visualize yield curves and spread changes over time

🛠 Tools Used
You may use any of the following tools:

Python (Pandas, Requests, Matplotlib/Seaborn)

SQL

Power BI

Power Query

Excel

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


###########################
For this assignment, I conducted a comprehensive analysis of bond yields from 2014 to 2024 consisting of descriptive statistical analysis, yield spread, scatter plots, moving averages, a correlation matrix, seasonal decomposition, rolling volatility, rolling correlation, and principal component analysis (PCA). With these in-depth analyses, a clearer understanding of bond yield dynamics was achieved, highlighting key trends, relationships, and volatility patterns that provide valuable insights into market behavior and potential economic conditions moving forward. In addition, I have also implemented all analyses from fundamental to advanced in a condensed Jupyter Notebook for a concise way to observe all visualizations.

Thank you!

Files Description:
1. A Comprehensive Report that documents my process, technical approach, findings, and insights regarding the data and visualizations.
2. An Excel file that performs data cleaning, data extraction through APIs, and fundamental analysis, along with basic visualizations.
3. A PowerBI file that contains both fundamental & advanced analysis along with advanced interactive visualizations and dashboards.
4. A PDF document that includes a detailed overview of the Power BI dashboard.  
5. An JupyterNotebook with additional advanced analysis and visualizations all fully implemented using only Python. This file also contains all previous analysis done in both Excel and PowerBI, please expand all fields to view these.

Technologies Utilized in The Assignment: Power Query, PivotTable, PivotChart, Formulas, DAX, Python, Numpy, scikit-learn, Matplotlib, Seaborn
