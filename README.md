# Global-Inflation-Post-Covid
This project examines the macroeconomic landscape from 2020 to 2024, focusing on the surge and subsequent fluctuations in global inflation following the COVID-19 pandemic. The dashboard correlates inflation rates with key drivers such as Oil Prices, Food Price Indices, GDP Growth, and Money Supply across 20 major economies.
Tech Stack
Data Cleaning & Prep: Python (Pandas)

Data Visualization: Power BI

Analytical Logic: DAX (Data Analysis Expressions)

Data Source: Global Macroeconomic Indicators (2020–2024)

🐍 Python Implementation
Before importing data into Power BI, I used Python to ensure the dataset was robust and structurally sound. This was especially important for aligning disparate economic indicators (like Oil Prices vs. Country-specific Inflation).

Key Technical Tasks:
Standardization: Used Pandas to align data from different sources into a consistent time-series format (2020–2024).

Handling Missing Values: Applied interpolation methods for missing monthly economic data points to ensure smooth trend lines.

Data Reshaping: Transformed "Wide" format data from international databases into "Long" format for optimized Power BI performance.

Calculated Fields: Pre-calculated the Average Unemployment Rate and Food Price Index weights to verify data integrity before visualization.

📈 Dashboard Features & KPIs
The dashboard is designed for high-level executive summaries with the ability to drill down into specific country metrics.

Key Metrics (KPI Cards):
Average Inflation (4.18%): The global benchmark for the post-COVID period.

Average Interest Rate (2.56%): Visualizing the cost of borrowing during the recovery.

Average Oil Price ($75.03): Tracking the energy costs that heavily influence inflation.

Total Countries (20): Scope of the analysis including USA, IND, BRA, GBR, etc.

Core Visualizations:
Year-Wise GDP Growth: A funnel-style visualization showing the global recovery trajectory.

Inflation Over Time: A detailed area chart highlighting the 2022 inflation peak.

Oil vs. Food Price Index: A dual-line chart demonstrating the correlation between energy costs and food security.

Country-wise Money Supply: A donut chart breakdown showing the distribution of liquidity across major economies.

Dynamic Country Slicer: Allows for instant filtering to compare specific nations like India (IND), USA, or China (CHN).

🚀 How to Use
Filter by Country: Use the right-hand slicer to see how specific nations handled inflation vs. GDP growth.

Correlation Analysis: Compare the "Inflation Over Time" chart with the "Oil Price" chart to see the lag effect of energy prices on consumer goods.

**Portfolio Impact**
This project showcases a "Data-to-Insight" pipeline:

<img width="580" height="332" alt="image" src="https://github.com/user-attachments/assets/86ebab72-23c7-4cb4-9be3-1a6b517e9a2b" />
