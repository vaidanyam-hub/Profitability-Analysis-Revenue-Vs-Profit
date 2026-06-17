# Profitability Analysis: Revenue vs Profit Diagnostic

## Why Is Revenue Growing but Profit Declining?

This project investigates the paradox of rising revenue alongside collapsing profit margins through end-to-end data analysis and visualization.

---

## Business Problem

The company experienced continuous month-over-month revenue growth, yet profit margins declined sharply—from **+5.8%** to **-29%**, including multiple loss-making months.

The business needed to understand:

* Why profits were declining despite growing sales
* Which factors were driving margin compression
* What actions could restore profitability

---

## Project Objectives

* Identify the root causes of profit erosion
* Quantify the impact of each contributing factor
* Deliver actionable, data-driven recommendations to improve profitability

---

## Dashboard Preview

![Executive Profitability Dashboard](dashboard.png)

### KPI Views Included

1. **Revenue vs Profit Trend**
   Month-over-month comparison of revenue growth and profit decline.

2. **Monthly Margin Trend**
   Tracks margin compression over time.

3. **Return Rate Analysis**
   Monitors the increase in return rates from approximately **3% to 18%**.

4. **Average Shipping Cost by Region**
   Identifies regions contributing to higher operational costs.

5. **Top 10 Revenue Products**
   Highlights products generating the highest revenue.

---

## Key Findings

After performing end-to-end exploratory data analysis, three major drivers of declining profitability were identified.

### 1. Return Rate Surge

* Return rates increased from **3% to 18%**
* High-return products continued to be promoted
* Revenue, shipping, and product costs were negatively impacted

### 2. Aggressive Discounting

* Discounts were applied without margin thresholds
* Revenue growth became volume-driven rather than profit-driven
* Contribution margins declined significantly

### 3. Rising Shipping Costs

* Shipping costs amplified losses in certain regions
* No effective cost-control strategy was in place
* Logistics expenses reduced overall profitability

---

## Recommendations

| Business Issue   | Recommendation                                                         |
| ---------------- | ---------------------------------------------------------------------- |
| High Return Rate | Implement return-rate threshold alerts for product categories          |
| Discount Erosion | Set minimum margin requirements before applying discounts              |
| Shipping Costs   | Introduce region-based shipping caps and renegotiate carrier contracts |

---

## Tools & Technologies

* **Programming Language:** Python
* **Data Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib
* **Development Environment:** Google Colab
* **Data Source:** Kaggle Dataset
* **Reporting & Analysis:** Exploratory Data Analysis (EDA)

---

## Project Structure

```text
Profitability-Analysis-Revenue-Vs-Profit/

├── dashboard.png
├── README.md
└── profitability_analysis.ipynb
```

---

## Business Impact

The analysis revealed that increasing revenue alone is not a reliable indicator of business health. Rising return rates, aggressive discounting, and increasing shipping costs collectively contributed to declining profitability.

This project demonstrates how data-driven analysis can uncover operational inefficiencies and support strategic business decisions.
3) Shipping costs - Introduce region-based shipping cost caps and renegotiate carrier contracts

**Tools & Technologies**
1) Language - Python
2) Data Analysis - Pandas, NumPy
3) Visualization - Matplotlib, Seaborn
4) Environment - Google Colab
5) Data Source - Kaggle Dataset
6) Reporting - Excel, EDA Dashboard

**Project Structure**

Profitability-Analysis-Revenue-Vs-Profit/

├── visuals/
│   ── dashboard.png            # Dashboard screenshot
│
├── README.md
│
└── notebooks/
    ── profitability_analysis.ipynb  
