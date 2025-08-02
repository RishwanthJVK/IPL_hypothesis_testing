# 🏏 IPL Data Analysis & Hypothesis Testing

This project presents a thorough data exploration and statistical analysis of IPL (Indian Premier League) match data. It focuses on uncovering insights, testing relevant hypotheses, and providing actionable interpretations through data visualization and statistical significance testing.

---

## 📁 Dataset Summary

- **Source**: [Kaggle IPL Dataset](https://www.kaggle.com/datasets)
- **Size**: ~636 matches (as of 2019)
- **Key Variables**: id, season, city, date, team1, team2, toss_winner,
       toss_decision, result, dl_applied, winner, win_by_runs,
       win_by_wickets, player_of_match, venue, umpire1, umpire2
- **Target Variables**:
  - `winner`: Used for outcome analysis
  - `win_by_runs` / `win_by_wickets`: For margin of victory

---

## 📌 Project Objectives

1. Perform **data cleaning** and **feature engineering**
2. Conduct **exploratory data analysis (EDA)** to identify patterns
3. Test **three hypotheses** using statistical significance tests
4. Summarize **key insights** and provide **visualizations**

---

## 🔎 Data Exploration Plan

- Understand match outcomes across years, teams, and venues
- Analyze toss impact and decision outcomes
- Visualize distributions and correlations 
- Study venue-wise win patterns

---

## 📊 Exploratory Data Analysis (EDA)

- Most successful teams and venues
- Influence of toss on match outcomes
- Preferred decisions after toss
- Home ground advantage patterns


## 🧹 Data Cleaning & Feature Engineering

- Handled **missing values** (e.g., nulls in `winner` during abandoned matches)
- Encoded categorical variables (Label Encoding, One-Hot Encoding)
- Standardized team names (e.g., `Rising Pune Supergiant` and `Rising Pune Supergiants`)
- Added derived features:
  - `is_home_team_win`
  - `toss_and_match_winner`

---

## ✅ Hypotheses Tested

1. **H1**: CSK's victory is independent of the venue  
2. **H2**: Winning the match is independent of winning the toss  
3. **H3**: Winning the match is independent of choosing to bat or field

---

## 📈 Hypothesis Testing Results

- Used **Chi-Square Test of Independence** for all hypotheses.
- **H1**: Rejected — CSK win rate **does** depend on the venue.
- **H2**: Not rejected — Toss winning does **not significantly** impact match outcome.
- **H3**: Not rejected — Batting/Fielding first does **not significantly** affect winning.

---

## 🔍 Key Insights

- Toss decisions don’t statistically impact match outcomes.
- CSK performs **significantly better** in certain venues (especially Chepauk).
- Teams prefer chasing in recent seasons.
- A small margin (less than 10 runs or 2 wickets) often decides many close matches.

---

## 🏁 Conclusion & Next Steps

### Key Takeaways:
- Venue has a **significant influence** on match outcomes for some teams.
- Toss decisions show **limited statistical importance**.
- Data-driven venue-based strategies can benefit franchises like CSK.

### Next Steps:
- Expand dataset with post-2019 matches
- Incorporate player-level data (e.g., top scorers, bowlers)
- Use machine learning models for match prediction

---

## 📎 Screenshots & Visualizations

![Win Distribution](images/win_distribution.png)  
![Toss vs Match Outcome](images/toss_vs_match.png)  
![Venue vs CSK Win](images/venue_csk_win.png)

> All visualizations are generated using **Matplotlib** and **Seaborn**.

---

## 📚 Tools & Libraries

- Python (Pandas, NumPy)
- Seaborn & Matplotlib
- SciPy (Chi-Square Test)
- Jupyter Notebook

---


