# 📊 Marketing Funnel & Conversion Performance Analysis

**Task 3 – Data Science & Analytics Internship**

---
## Project Overview

This project analyzes a bank’s direct marketing campaign data to evaluate **marketing funnel performance**, identify **conversion drop-offs**, and understand **what drives customer subscriptions** to term deposits.

The analysis combines:

* **Python** for data understanding, cleaning, and metric validation
* **Power BI** for interactive dashboards and business storytelling

The goal is to demonstrate how data can support **more efficient, targeted marketing decisions**.

---
## Business Objective

Outbound marketing campaigns typically contact many customers but convert only a small percentage.
This project aims to help answer:

* How effective is the current marketing funnel?
* Where do customers drop off?
* Which customer segments and campaign factors lead to higher conversions?
* How can marketing efforts be optimized without increasing cost?

---
## Dataset

* **Source:** UCI Bank Marketing Dataset
* **Granularity:** One row per contacted customer
* **Target Variable:**

  * `yes` → customer subscribed (conversion)
  * `no` → customer did not subscribe (drop-off)

The dataset represents a simplified funnel:

```
Contacted Customer → Converted Customer
```

---
## Methodology

1. **Data Preparation & Validation (Python)**

   * Initial exploration and cleaning performed in Jupyter notebooks
   * Missing values handled to reflect real-world absence of information
   * Key conversion metrics validated programmatically

2. **Funnel & Driver Analysis**

   * Overall conversion performance assessed
   * Campaign fatigue and contact frequency analyzed
   * Customer segmentation explored (job, age group, contact type, prior outcome)

3. **Dashboarding (Power BI)**

   * Cleaned dataset used as the single source of truth
   * KPIs and funnel logic implemented using DAX
   * Interactive visuals designed for both executive and analyst use

---
## Key Insights

* Overall conversion rates are low, which is typical for outbound campaigns
* Conversion likelihood decreases as contact attempts increase, indicating diminishing returns
* Conversion performance varies significantly by customer segment and contact method
* Previous successful campaign outcomes strongly increase future conversion probability

---
## Business Recommendations

* Limit repeated contact attempts to reduce customer fatigue
* Prioritize high-performing customer segments
* Leverage historical campaign outcomes in targeting strategies
* Focus resources on more effective contact channels

---
## Repository Structure

```
FUTURE_DS_03/
│
├── data/          # Raw and cleaned datasets
├── notebooks/     # Python analysis and validation
├── dashboard/     # Power BI dashboard and screenshots
├── reports/       # Summary report and insights
├── assets/        # Supporting images (if used)
│
├── requirements.txt
└── README.md
```
### Folder Guide

* **`data/`** – Original and cleaned datasets
* **`notebooks/`** – Data understanding, cleaning, funnel analysis, validation
* **`dashboard/`** – Power BI `.pbix` file and dashboard screenshots
* **`reports/`** – Written summary of findings and recommendations

---
## Tools Used

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Power BI (DAX, interactive dashboards)

---
## Final Note

This project demonstrates a complete analytical workflow — from raw data to validated insights and business-ready dashboards — with an emphasis on clarity, correctness, and decision support rather than complexity.

---
