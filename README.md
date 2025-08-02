# 🏏 IPL Data Analysis & Hypothesis Testing

This project presents a thorough data exploration and statistical analysis of IPL (Indian Premier League) match data. It focuses on uncovering insights, testing relevant hypotheses, and providing actionable interpretations through data visualization and statistical significance testing.

---

## 📁 Dataset Summary

- **Source**: [Kaggle IPL Dataset](https://www.kaggle.com/datasets)
- **Size**: 635 matches
- **Key Variables**: id, season, city, date, team1, team2, toss_winner,
       toss_decision, result, dl_applied, winner, win_by_runs,
       win_by_wickets, player_of_match, venue, umpire1, umpire2
- **Target Variable**:
  - `winner`: can be used for outcome analysis

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

- Handled **missing values** 
- Encoded categorical variables (Label Encoding, One-Hot Encoding)
- Standardized team names 

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


## Conclusion & Next Steps

### Key Takeaways:
- Venue has a **significant influence** on match outcomes for some teams.
- Toss decisions show **limited statistical importance**.
- Data-driven venue-based strategies can benefit franchises like CSK.



## Tools & Libraries

- Python (Pandas, NumPy)
- Seaborn & Matplotlib
- SciPy (T-Test)
- Jupyter Notebook

---


