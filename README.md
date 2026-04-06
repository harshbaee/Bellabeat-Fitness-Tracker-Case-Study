# 🌿 Bellabeat Case Study — Can a Wellness Tech Company Play It Smart?
 
> Exploratory data analysis and interactive Tableau dashboard built on Fitbit fitness tracker data to uncover actionable insights for Bellabeat's product strategy.
 
---
 
## 📊 Project Overview
 
This case study investigates how real-world usage patterns from 35 Fitbit users can inform smarter features for **Bellabeat** — a wellness technology company focused on women's health.
 
The analysis covers activity levels, sleep behaviour, calorie burn, and weekly trends, culminating in three concrete product recommendations backed by the data.
 
| Metric | Value |
|---|---|
| 👥 Users Tracked | 35 |
| 📅 Days of Data | 62 |
| 🏃 Activity Records | 1,373 |
| 😴 Sleep Records | 901 |
| 🗓️ Period | March – May 2016 |
| 📦 Data Source | Fitbit Fitness Tracker Data (Kaggle · Möbius) |
 
---
 
## 🔍 Key Findings
 
### Act 01 — Activity & Steps
- Average daily steps: **7,377** — 26% below the CDC's 10,000-step target
- Only **21% of users** consistently hit 10K steps
- Users are **sedentary 81% of the time**; very active time is just 1.6%
- **Tuesday** is the most active day; Sunday shows the biggest drop-off
 
### Act 02 — Sleep & Calories
- Average sleep per night: **6.6 hours** (below the recommended 7–9 hrs)
- Most restful night: **Sunday**
- Average calories burned: ~**2,295/day** — consistent across the dataset
- Strong positive correlation between **active minutes → calories burned**
 
### Act 03 — Trends Over Time
- Steps peaked in **Week 17** at **1.78 million total steps**
- A sharp drop-off occurred in **Week 19**
- Heatmap analysis revealed **huge variance between individual users** — underlining the need for personalisation
 
---
 
## 💡 Recommendations
 
| # | Feature | Rationale |
|---|---|---|
| 01 | **Step Challenge Nudges** | Push notifications on low-activity days (Sun/Thu) with personalised goals — 81% sedentary time + user variance = huge room for small wins |
| 02 | **Sleep Improvement Programme** | In-app bedtime reminders targeting Sunday nights, where restless minutes peak — avg 6.6h sleep is consistently below recommendation |
| 03 | **Calorie & Activity Dashboard** | Show a live correlation score between active minutes and calories burned — making the payoff visible creates a retention-driving feedback loop |
 
---
 
## 🛠️ Tools Used
 
- **Tableau** — interactive dashboard and all visualisations (`.twbx`)
- **Excel / CSV** — raw Fitbit data preparation
- **Presentation** — findings communicated via a structured slide deck (`.pptx`)
 
---
 
## 📁 Repository Structure
 
```
bellabeat-case-study/
│
├── Bellabeat_Presentation.pptx   # Slide deck — full story in 3 acts
├── Project2.twbx                 # Tableau packaged workbook (dashboard)
└── README.md
```
 
---
 
## 🚀 How to Explore
 
1. **Tableau Dashboard** — Open `Project2.twbx` in [Tableau Public](https://public.tableau.com) or Tableau Desktop to interact with all visualisations.
2. **Slide Deck** — Open `Bellabeat_Presentation.pptx` for the full narrative walkthrough of findings and recommendations.
 
---
 
## 👤 Author
 
**Harsh Prajapati**
