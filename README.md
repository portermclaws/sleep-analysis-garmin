# sleep-analysis-garmin
Analyzing 4 weeks of Garmin sleep data using Python (pandas) and Tableau.

# Sleep Analysis with Garmin Data

## Overview

Analyzed 4 weeks of Garmin sleep data. Raw CSV was cleaned with **Python (pandas)** and visualized with **Tableau Public**.

Key questions:

* How long did I sleep (Garmin vs. Bedtime–Wake calculation)?
* How efficiently did I sleep (% of time in bed actually asleep)?
* Am I meeting the 8-hour goal (sleep debt)?

---

## Tools

* Python (pandas, matplotlib, seaborn)
* Jupyter Notebook
* Tableau Public
* GitHub for versioning + documentation

---

## Files

```
sleep-analysis-garmin/
│
├── data/
│   └── processed/
│       └── sleep_clean.csv   # Clean dataset
│
├── notebooks/
│   └── sleep_analysis.ipynb  # Jupyter workflow
│
└── README.md
```

---

## Tableau Dashboard

👉 [View the live dashboard on Tableau Public](https://public.tableau.com/app/profile/porter.mclaws/viz/Book1_17591722694650/Dashboard1?publish=yes)

This dashboard includes:
- Sleep Duration Trend (Garmin vs. Bedtime–Wake)
- Sleep Efficiency Over Time
- Sleep Debt vs. 8-Hour Goal

---

## Insights

* Garmin undercounts sleep by ~0.5–1.5 hrs vs. raw bed-to-wake.
* Avg sleep efficiency ≈ 85%.
* Sleep debt builds on weekdays, weekends show catch-up.

---
