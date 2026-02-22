# al-rajhi-financial-analysis-dashboard
##Project Overview

This project analyzes the long-term stock performance of Al Rajhi Bank (RJHI) from 2010 to 2025. The topic was chosen to reflect a strong understanding of the Saudi financial market and to evaluate a leading banking asset within the Tadawul ecosystem.
The central question addressed by this dashboard is:
How has Al Rajhi Bank performed as a long-term wealth-generating asset, and what does its historical behavior reveal about growth sustainability, volatility structure, and seasonal performance patterns?
Rather than focusing on short-term price movement, the analysis evaluates structural capital appreciation, annualized compounding strength, liquidity behavior, and recurring return distribution patterns.

##Data Source

The data was sourced from Kaggle's public datasets. It contains historical (Open, High, Low, Close, Volume) data from 2010 to 2025.
The data was obtained from publicly available historical financial market records. The 15-year time frame captures multiple economic phases including post-crisis recovery, oil market volatility, COVID-19 disruption, and structural economic reforms under Vision 2030.
This broad time horizon allows for evaluation of resilience across macroeconomic cycles rather than isolated market events.

##Steps & Methodology

The project followed a structured analytical process:
First, the data was reviewed and validated to ensure chronological consistency and completeness. Derived metrics were calculated to transform raw prices into meaningful financial indicators.
Total Return was calculated to measure cumulative capital appreciation over 15 years, resulting in 722.96% growth. To normalize performance across time and assess sustainability, the Compound Annual Growth Rate (CAGR) was calculated at 15.09%.
A 15-year High and Low were extracted to define historical price boundaries and contextualize current positioning within long-term ranges.
A Monthly Performance metric was derived to construct a heatmap showing return distribution across calendar months and years, enabling detection of seasonality patterns.
Trading Volume was aggregated and analyzed alongside price movement to evaluate conviction strength and liquidity depth.

Tool Selection:
Google Looker Studio was used to build the live interactive dashboard due to its filtering capabilities and executive-friendly interface. Figma was used to design a structured UI layout before implementation, focusing on visual hierarchy and institutional aesthetics.

Design Decisions:
The dashboard follows a layered analytical hierarchy:

KPI Scorecards → Executive summary metrics

Time Series (Close Price) → Long-term structural trend

Combined Chart (Volume bars + Close line) → Conviction validation

Monthly Heatmap → Tactical and seasonal insight

The dark executive theme and structured layout were intentionally selected to enhance readability and storytelling clarity.

##Dashboard Screenshots



<img width="780" height="596" alt="Screenshot (76)" src="https://github.com/user-attachments/assets/6f1f077e-04b3-417b-933c-b8446132f82f" />
 




##Design Screenshots




<img width="680" height="487" alt="Screenshot (78)" src="https://github.com/user-attachments/assets/2ae6c06c-fa72-48b8-8d44-b4420eda1949" />



High-fidelity wireframes were created in Figma prior to implementation to define layout structure, spacing, and component hierarchy.

##Key Insights

The analysis reveals several important findings:

First, the stock generated 722.96% cumulative growth over 15 years, confirming significant long-term capital appreciation.

Second, the 15.09% CAGR indicates that growth was sustained rather than episodic. This level of compounding over an extended period reflects structural strength.

Third, time-series analysis shows cyclical volatility rather than structural breakdowns. Corrections appear macro-driven and temporary.

Fourth, price movements during major upward phases were supported by elevated trading volume, indicating institutional participation rather than speculative spikes.

Finally, the monthly heatmap suggests non-uniform return distribution, indicating potential seasonal strength patterns that may support tactical capital allocation.

##Live Dashboard Link


https://lookerstudio.google.com/reporting/6e5c7b12-5071-466b-a063-ace1417dfac9

##Assumptions & Limitations

This analysis assumes historical prices reflect corporate adjustments and does not incorporate dividend reinvestment.

The study is technical in nature and does not integrate fundamental banking indicators such as profitability ratios, interest rate sensitivity, or macroeconomic variables.

Future iterations could incorporate risk-adjusted metrics and fundamental overlays to enhance analytical depth.
