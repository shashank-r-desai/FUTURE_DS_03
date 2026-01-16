# 📄 Marketing Funnel & Conversion Performance Analysis

## Executive Summary

This project analyzes a bank’s direct marketing campaign data to evaluate funnel performance and identify key drivers of customer conversion. Using Python for validation and Power BI for visualization, the analysis highlights where customers drop off and which segments contribute most to successful term deposit subscriptions.

The complete analysis, dashboard, and supporting files are available in this GitHub repository.

---
## Business Objective

Banks contact a large number of customers, but only a small percentage convert.
The objective of this analysis is to:

* measure conversion performance across the marketing funnel
* identify customer and campaign attributes that influence conversions
* support more efficient, data-driven marketing strategies

---
## Dataset Overview

* **Source:** UCI Bank Marketing Dataset
* **Unit of analysis:** One contacted customer
* **Target variable:**

  * `yes` → subscription (conversion)
  * `no` → no subscription (drop-off)

The dataset represents a simplified funnel:

```
Contacted → Converted
```

---
## Methodology

* Raw data was cleaned and validated using Python notebooks (`/notebooks`)
* Key metrics and segment-level insights were recreated in Power BI using DAX (`/dashboard`)
* Python-based validation was used to cross-check core KPIs before final visualization

The cleaned dataset serves as the single source of truth (`/data/processed`).

---
## Key Insights

* Overall conversion rates are low, which is typical for outbound campaigns
* Conversion likelihood decreases as the number of contact attempts increases, indicating campaign fatigue
* Conversion rates vary significantly by job category, age group, contact method, and previous campaign outcome
* Previous successful engagements strongly increase the probability of future conversion

---
## Dashboard Summary

The Power BI dashboard presents:

* High-level KPIs for overall performance
* A funnel view showing conversion drop-offs
* Segment-level charts explaining conversion drivers
* Interactive slicers to explore subsets without altering global KPIs

Dashboard files and screenshots are available in the `/dashboard` folder.

---
## Business Recommendations

* Reduce excessive contact attempts to avoid diminishing returns
* Focus marketing efforts on high-performing customer segments
* Prioritize customers with successful prior campaign outcomes
* Allocate resources toward more effective contact channels

---
## Conclusion

This analysis shows that improving marketing effectiveness depends more on **targeting and strategy** than on increasing outreach volume. By focusing on high-intent segments and limiting unnecessary contact, organizations can improve conversion rates while reducing campaign costs.

---
### Project Reference

* **Data:** `/data`
* **Analysis & validation:** `/notebooks`
* **Dashboard:** `/dashboard`
* **Full repository:** GitHub – `FUTURE_DS_03`
