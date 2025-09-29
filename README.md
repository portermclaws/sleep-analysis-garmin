# Sleep Analysis with Garmin Data

## Project Overview

This project analyzes 4 weeks of Garmin sleep data. The raw CSV export was cleaned and transformed using Python (pandas), then visualized in Tableau Public.

The analysis explores three core questions:

1. How long did I sleep each night (Garmin vs. bedtime–wake calculation)?
2. How efficiently did I sleep (% of time in bed actually asleep)?
3. Am I meeting the 8-hour goal (sleep debt)?

---

## Tools and Methods

* Python (pandas, matplotlib, seaborn) for data cleaning and analysis
* Jupyter Notebook for workflow and documentation
* Tableau Public for interactive dashboard visualization
* GitHub for version control and project sharing

---

## Project Structure

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

[View the live dashboard on Tableau Public](https://public.tableau.com/app/profile/porter.mclaws/viz/Book1_17591722694650/Dashboard1?publish=yes)

This dashboard includes:

* Sleep Duration Trend (Garmin vs. Bedtime–Wake calculation)
* Sleep Efficiency Over Time
* Sleep Debt compared to an 8-hour target

---

## Key Insights

* Garmin undercounts sleep by approximately 0.5–1.5 hours compared to raw bedtime–wake calculations.
* Average sleep efficiency is about 85%, meaning 15% of time in bed was spent awake.
* Sleep debt tends to build during weekdays, with recovery often occurring on weekends.
