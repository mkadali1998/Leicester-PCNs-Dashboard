# Leicester-PCNs-Dashboard
A dashboard to analyze Leicester City PCNs and income data
This project presents four key visualizations that showcase monthly and year-wise trends in Penalty Charge Notices (PCNs) issued by Leicester City Council. These charts provide insights into enforcement volume and revenue patterns.

Dataset Summary:
This dashboard is built on simulated open data containing:
Month (12 months of 2023)
PCNs issued
Income (£) generated
Street Name (randomly assigned)
Year

Visualizations Included -
1. Monthly PCNs – Line Chart

Displays how PCNs issued fluctuate across the months, highlighting trends or seasonal drops/spikes in enforcement.

2. Income vs PCNs – Dual Axis (Bar + Line Combo)

A powerful comparison of revenue and enforcement activity.

Bar → Income
Line → PCNs issued
3. PCNs vs Income – Scatter Plot

Analyzes the correlation between the number of PCNs and revenue for each month. Each dot is a month labeled on the chart.

4. Grouped Bar Chart – Year-wise Monthly PCNs

Shows monthly PCNs comparison between two years (2022 and 2023) to understand growth or enforcement shifts. Each month has two bars grouped by year.

Built With -
Python 3.9+
Pandas for data handling
Matplotlib & Seaborn for dual-axis charts
Plotly Express for interactivity
Jupyter Notebook or Streamlit for dashboard rendering
