---
title: "Project: Autolib Fleet Movement Analysis"
description: "Performing exploratory data analysis and rigorous hypothesis testing on 16,085 fleet records to optimize electric mobility operations."
date: 2026-02-20 11:15:00 +0300
categories: [Personal Projects, Data Analytics]
tags: [python, pandas, statistical-testing, eda, data-analytics]
---

## Project Overview
This project involved a comprehensive deep-dive exploratory data analysis (EDA) on electric vehicle operations using fleet utilization metrics. The core objective was to uncover spatial-temporal demand trends, perform mathematical hypothesis evaluations, and deliver data-driven operational strategies for car-sharing mobility platforms.

* **GitHub Repository:** [mburu-mwangi/Core-Wk-4-ip](https://github.com/mburu-mwangi/Core-Wk-4-ip)
* **Dataset Scale:** 16,085 operational logging data vectors

---

## Core Responsibilities & Technical Architecture

### Core Responsibilities
* **Mass Data Consolidation:** Cleaned and parsed over 16,000 temporal fleet movement sequences, isolating pick-up/drop-off intervals and resource allocations.
* **Statistical Hypothesis Testing:** Designed and executed mathematical hypothesis checks to evaluate operational differences across station parameters and weekend vs. weekday demand.
* **Trend Identification:** Built time-series visualization matrices tracking electric vehicle availability to locate bottleneck zones.
* **Operational Optimization:** Translated complex statistical outputs into actionable, data-driven insights for electric fleet distribution.

### Technical Architecture
{% raw %}
```text
[16K+ Fleet Log Records] ---> [Time-Series Parsing] ---> [Statistical Testing]
                                                                  |
                                                         (Z-Test / T-Test Verification)
                                                                  |
[Operational Strategy]  <--- [Trend Bottleneck Analysis] <--- [Matplotlib Framework]
```
{% endraw %}

---

## Key Solutions & Operational Outcomes

### 1. Rigorous Trend Identification
By combining statistical significance checks with exploratory charting workflows, the analysis successfully mapped high-occupancy usage windows, proving that weekend fleet demands diverged significantly from weekday baseline patterns.

### 2. Fleet Efficiency Solutions
The project delivered clear, actionable strategies to resolve vehicle location imbalances, showing exactly how sharing platforms can reallocate resources to maximize vehicle availability.

---

## Technical Stack Summary
* **Languages & Frameworks:** Python, Pandas Dataframes
* **Statistical Methods:** Hypothesis Testing, Parametric Verifications, Confidence Intervals
* **Visualization Layer:** Matplotlib, Seaborn Engine