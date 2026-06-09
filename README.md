## Live Dashboard
🔗 https://haodata.github.io/e-commerce_analytics_with_dashboard/

# E-Commerce_Analytics


A comprehensive data analysis of e-commerce order data spanning **October 2018 to October 2020**, covering 682,792 orders across 12+ European and international markets. 

---

## Dataset Overview

| Field | Detail |
|-------|--------|
| Source file | `orders.csv` |
| Total records | 682,792 orders |
| Time period | Oct 2018 – Oct 2020 |
| Key markets | DE, SE, GB, DK, NL, FR, PL, NO, US, and more |
| Key metrics | Revenue, profit margin, shipping fee, order weight, customer ID |

---

## Report Structure

The report is organized into 7 analytical dimensions plus a summary:

### 1 · Sales Overview
- **Total revenue**: 348.8M SEK (excl. VAT)
- **Total orders**: 682,792
- **Average order value**: 510.8 SEK
- Monthly revenue trend chart revealing strong year-over-year growth, with a notable 2× surge in April–May 2020 driven by COVID-19 pandemic effects on online shopping behavior.

### 2 · Profit Analysis
- **Total profit**: 218.4M SEK
- **Average profit margin**: 64.2% (range: 42%–83%)
- Country-level margin breakdown showing Germany (DE) leading at 70.9% and the UK (GB) trailing at 58.1%.
- Identifies 13,376 very high-margin orders (>80%) and 4,646 zero-profit orders for further investigation.

### 3 · Country Analysis
- Side-by-side comparison of orders and revenue across the top 8 markets.
- Summary table with orders, revenue, margin, and strategic insight per country.
- Key finding: DE is the strongest market by both volume and profitability; GB ranks 3rd in orders but has the lowest margin combined with the highest shipping costs.

### 4 · Customer Analysis
- **Total unique customers**: 577,950
- **Repeat buyer rate**: 14.2% (82,041 customers)
- Doughnut chart showing the 85.8% one-time buyer majority.
- Top 10 customers ranked by lifetime value (LTV), with the highest-value customer at 54,339 SEK across 16 orders.

### 5 · Time Analysis
- **Busiest months**: May and October
- **Busiest weekday**: Tuesday (120,495 orders)
- **Peak hour**: 21:00–22:00
- Three charts cover monthly, weekday, and hourly order distribution to support campaign scheduling decisions.

### 6 · Logistics & Shipping Analysis
- Average shipping fee by country, ranging from 8.2 SEK (SE) to 26.2 SEK (GB).
- Positive correlation between order weight and shipping cost, with notable outliers.
- 15% of orders (104K) are missing weight data, flagged as a data quality issue.

### 7 · Anomaly Analysis
- **13,376** orders with margin >80% — potential product/pricing patterns to replicate.
- **4,646** zero-profit orders — likely promotions or gift orders, require audit.
- **6,826** very high shipping fee orders — 72% concentrated in GB (4,892 orders).
- **16,876** orders with missing profit data — 2.5% data gap requiring investigation.

---

## Key Recommendations

| # | Action | Rationale |
|---|--------|-----------|
| 01 | **Scale Germany** | Best combination of volume (156K orders) and margin (70.9%) |
| 02 | **Fix UK profitability** | Low margin + highest shipping fees; renegotiate carrier contracts |
| 03 | **Boost repeat purchases** | Only 14.2% repeat rate; implement loyalty and retargeting programs |
| 04 | **Capitalize on seasonal peaks** | Pre-stage inventory and campaigns 4–6 weeks before May and October |
| 05 | **Investigate anomalies** | Audit zero-profit and missing-data orders to confirm intent and fix gaps |
| 06 | **Evening campaign focus** | Peak ordering at 21:00–22:00; schedule emails for 20:00–21:00 |

---



```

orders.csv                  # Source data (682,792 order records)
README.md                   # This file
```

---

