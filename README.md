Background:
As the nation’s central bank, the Bank of Canada’s main role is to promote the economic and
financial welfare of Canada. Additionally, the Bank is a source of exchange rates, interest rates, price
indexes, economic indicators, and other statistical data. The Bank of Canada Valet Web Service
offers programmatic access to global financial data. More information can be found here:
https://www.bankofcanada.ca/valet/docs

Objective:
The goal of this exercise is to evaluate a candidate’s ability to:
• Connect to external data sources
• Import and clean data
• Analyze data from sources
• Create a report or visualization
Tools:
You may use any of the following tools:
• SQL
• Python
• Power Query
• Power BI
• Excel
Ensure your code is clearly documented.
Tasks:
1. Connect to an External Data Source:
o Use the Bank of Canada Valet API to retrieve data.
2. Import and Clean Data:
o Import 10 years’ worth of T-bill and benchmark bond yield data for the following
tenors:
 1 year (TB.CDN.1Y.MID)
 2 years (BD.CDN.2YR.DQ.YLD)
 5 years (BD.CDN.5YR.DQ.YLD)
 10 years (BD.CDN.10YR.DQ.YLD)
o Clean the data by handling missing values, converting data types, and renaming
columns for clarity.
3. Analyze Data:
o Analyze the T-bill and bond yields.
o Calculate the spreads between different tenors (e.g., 2Y-1Y, 5Y-2Y, 10Y-5Y).
o Document your approach and findings.
4. Build Visualizations:
o Create visualizations that highlight your analysis of yields and their relationships.
o Use any tool of your choice (e.g., Excel, Power BI, Python’s Matplotlib/Seaborn)


For this assignment, I conducted a comprehensive analysis of bond yields from 2014 to 2024 consisting of descriptive statistical analysis, yield spread, scatter plots, moving averages, a correlation matrix, seasonal decomposition, rolling volatility, rolling correlation, and principal component analysis (PCA). With these in-depth analyses, a clearer understanding of bond yield dynamics was achieved, highlighting key trends, relationships, and volatility patterns that provide valuable insights into market behavior and potential economic conditions moving forward. In addition, I have also implemented all analyses from fundamental to advanced in a condensed Jupyter Notebook for a concise way to observe all visualizations.

Thank you!

Files Description:
1. A Comprehensive Report that documents my process, technical approach, findings, and insights regarding the data and visualizations.
2. An Excel file that performs data cleaning, data extraction through APIs, and fundamental analysis, along with basic visualizations.
3. A PowerBI file that contains both fundamental & advanced analysis along with advanced interactive visualizations and dashboards.
4. A PDF document that includes a detailed overview of the Power BI dashboard.  
5. An JupyterNotebook with additional advanced analysis and visualizations all fully implemented using only Python. This file also contains all previous analysis done in both Excel and PowerBI, please expand all fields to view these.

Technologies Utilized in The Assignment: Power Query, PivotTable, PivotChart, Formulas, DAX, Python, Numpy, scikit-learn, Matplotlib, Seaborn
