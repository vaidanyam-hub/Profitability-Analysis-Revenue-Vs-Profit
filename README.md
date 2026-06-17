Profitability Analysis — Revenue vs Profit Diagnostic


Why is revenue growing but profit declining?

This project investigates the paradox of rising revenue alongside collapsing profit margins using end-to-end data analysis and visualization.

Problem Statement

A company experienced continuous month-over-month revenue growth, yet profit margins collapsed sharply — from +5.8% to -29%, including loss-making months. The business needed to understand why and what to do about it.

Objective


Identify the root causes of profit erosion
Quantify the impact of each contributing factor
Deliver actionable, data-driven recommendations to restore profitability

Dashboard Preview
Dashboard.png

<!-- ![Profitability Analysis Dashboard](dashboard.png) -->
5 KPI Views included:

KPI ViewDescriptionRevenue vs Profit TrendMoM comparison of revenue growth vs profit declineMonthly Margin %Tracks margin compression over timeReturn Rate AnalysisMonitors return rate surge from 3% → 18%Shipping Cost by RegionIdentifies regions with compounding cost issuesTop 10 Revenue ProductsHighlights which products drive vs drain profitability

Key Findings

After end-to-end exploratory data analysis, 3 root causes were identified:

1. Return Rate Surge
Return rate climbed from 3% → 18%
High-return products continued to be promoted, amplifying losses

2. Aggressive Discounting
Discounts were applied without margin thresholds
Contribution margin eroded even as top-line revenue grew


3. Regional Shipping Cost Explosion
Shipping costs compounded losses in specific regions
No cost-ceiling policy was in place for high-distance deliveries

Recommendations

IssueRecommendationHigh return rateImplement return rate threshold alerts per product categoryDiscount erosionSet minimum margin floor before applying discountsShipping costsIntroduce region-based shipping cost caps and renegotiate carrier contracts

Tools & Technologies

CategoryToolsLanguagePythonData AnalysisPandas, NumPyVisualizationMatplotlib, SeabornEnvironmentGoogle ColabData SourceKaggle DatasetReportingExcel, EDA Dashboard

Project Structure

Profitability-Analysis-Revenue-Vs-Profit/
│
├── data/
│   ── raw_dataset.csv          
│
├── notebooks/
│   ── profitability_analysis.ipynb  
│
├── visuals/
│   ── dashboard.png            # Dashboard screenshot
│
└── README.md

