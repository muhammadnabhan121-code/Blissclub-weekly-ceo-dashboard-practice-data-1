# Blissclub-weekly-ceo-dashboard-practice-data-1
# Weekly CEO Business Review Dashboard (Looker Studio)

A practice dashboard for a D2C apparel brand, built in Looker Studio on simulated data.

**Live dashboard:** [ https://datastudio.google.com/reporting/4c00898f-e1b5-4061-881e-fb5bcb08cd3c ]

## What it shows
- 6 KPIs: orders, net revenue, AOV, return rate, repeat %, menswear share
- Last 4 weeks vs previous 4 weeks
- Weekly revenue by category, revenue and ad spend by channel
- City performance (all 12 weeks)

## Key insights
- Net revenue up 28.1%, return rate down 5.4%
- Week 7 dip after website ad spend was cut about 60%
- Menswear share up to about 26%

## Data quality issues found and fixed
1. Duplicate Order_ID (ORD-100283): removed the extra row
2. Negative sales (ORD-100895): corrected the sign, flagged for confirmation
3. Missing city (1 order): labelled Unknown to keep totals correct
4. Inconsistent category label ("men" vs "Men"): standardised

## Tools
Looker Studio, Google Sheets

Data is simulated for practice.

![Page 1](page1.png)
![Page 2](page2.png)
