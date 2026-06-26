# Bellabeat Smart Device Usage Analysis

Analyzed FitBit fitness tracker data to identify behavioral trends and deliver marketing recommendations for Bellabeat, a wellness tech company. Completed as the capstone project for the Google Data Analytics Professional Certificate.

---

## Objective

Bellabeat wanted to understand how consumers use non-Bellabeat smart devices, and use those patterns to sharpen their marketing strategy for the **Bellabeat Leaf** — a wearable wellness tracker.

---

## Dataset

- **Source:** [FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit) (Kaggle / Möbius, CC0 Public Domain)
- **Size:** 1,388 records · 35 users · ~2 months (March–May 2016)
- **Files used:** `dailyActivity_merged` (two periods), `sleepDay_merged`
- **Limitation:** Small sample, 2016 data, no demographic info — findings are directional, not statistically conclusive

---

## Tools

| Tool | Use |
|------|-----|
| Google Sheets | Cleaning, merging, validation |
| Tableau | Dashboard and visualizations |
| Google Slides | Stakeholder presentation |

---

## What I Did

**Cleaning (Google Sheets)**
- Merged 3 CSV files into one unified dataset
- Removed 3 duplicate rows and 9 zero-calorie records (likely device non-use)
- Validated data types, value ranges, and cross-field consistency
- Exported clean `.xlsx` to Tableau

**Analysis**
- Calculated daily averages for steps, calories, active minutes, and sedentary time
- Segmented users by activity intensity (sedentary / lightly active / fairly active / very active)
- Examined sleep tracking coverage and sleep duration distribution
- Ran correlation analysis across key metrics

---

## Key Findings

- Average daily steps: **7,328** — below the 10,000-step benchmark
- Users are sedentary for ~**16.5 hours/day** on average
- Only **30.3%** of records had sleep data logged
- Of users who tracked sleep, ~**44% slept under 7 hours**
- **r = −0.54** between sedentary time and sleep quality — the strongest signal in the data

---

## Recommendations

1. **Step Challenge Campaigns** — Use the step gap (7,328 vs. 10,000) as a hook for in-app challenges and a "10K Challenge" social campaign
2. **Sleep Tracking Push** — Low sleep logging + poor sleep duration = opportunity to market the Leaf's sleep features through a "Better Sleep" campaign
3. **Sedentary Break Reminders** — The r = −0.54 finding supports a "Move more, sleep better" messaging angle with targeted push notifications

---

## Deliverables

- [`View Tableau Dashboard`](#) — replace with actual link
- [`View Presentation`](#) — replace with actual link

---

## Repository Structure

```
bellabeat-smart-device-analysis/
│
├── data/
│   └── (raw CSVs not included — available on Kaggle)
│
├── analysis/
│   └── bellabeat_cleaned.xlsx
│
└── README.md
```

---

*Google Data Analytics Capstone · 2025 · Iktedar Ahmed*
