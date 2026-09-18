# Social Media Impact on Students' Life — Data Analysis

**[Live Interactive Portfolio →](#)** *(update this link once GitHub Pages is live)*

A data analysis project exploring how social media usage patterns relate to sleep, stress, mental health, and academic performance among 4,500 students.

## Problem Statement
Social media is a constant part of student life, but its effect on wellbeing and academics is debated. This project uses a real-world-style dataset to answer:
- Does daily usage time correlate with mental health and academic performance?
- What role does sleep play as a mediating factor?
- Does social comparison behavior increase stress?
- Do usage patterns differ by platform?

## Dataset
- **Rows:** 4,500 students
- **Columns:** 16 (demographics, platform usage, sleep, stress, mental health, GPA, overall impact label)
- **Source:** User-provided CSV (`Social_media_impact_on_life.csv`)

## Tools Used
- Python (pandas, numpy)
- Matplotlib & Seaborn for visualization
- Jupyter Notebook

## Approach
1. **Data Cleaning** — handled missing values (median imputation), verified no duplicates, fixed data types.
2. **Exploratory Data Analysis** — summary statistics, distribution checks, correlation analysis.
3. **Visualization** — 7 charts covering distributions, correlations, and relationships between key variables.
4. **Insight Generation** — translated statistical patterns into plain-language findings.

## Key Findings
- Daily usage hours has a **strong negative correlation** with Mental Health Index (r ≈ -0.85) and GPA (r ≈ -0.71).
- Students in the "Negative impact" group average **~12.3 hrs/day** of usage vs **~4.4 hrs/day** for "Beneficial".
- **Sleep duration** correlates strongly with mental health (r ≈ 0.77), suggesting it's a key mediator.
- Frequent **social comparison** is linked to higher perceived stress.
- **Snapchat and TikTok** users report the highest average daily usage; LinkedIn and X (Twitter) the lowest.
- **Late-night users** report lower sleep quality scores than non-late-night users.

## Files
```
├── index.html                           # Live interactive portfolio (open this)
├── Social_Media_Impact_Analysis.ipynb   # Main analysis notebook (with outputs)
├── Social_media_impact_on_life.csv      # Dataset
├── analysis.py                          # Standalone script version
├── insights_summary.txt                 # Plain-text summary of findings
└── site_assets/                         # Chart images used by index.html
```

## How to Run
```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook Social_Media_Impact_Analysis.ipynb
```

## Limitations
This is a **correlational** analysis, not causal. Confounding factors (personality, environment, academic workload) aren't controlled for. Findings should be interpreted as patterns worth further investigation, not proof of cause-and-effect.

---
*Portfolio project — built to demonstrate data cleaning, EDA, visualization, and insight communication skills.*
