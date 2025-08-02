# 🏏 IPL Data Analysis & Hypothesis Testing

This project presents a thorough data exploration and statistical analysis of IPL (Indian Premier League) match data. It focuses on uncovering insights, testing relevant hypotheses, and providing actionable interpretations through data visualization and statistical significance testing.

---

## 📁 Dataset Summary

- **Source**: Kaggle
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
- Analysed Duplicates
- Handled Outliers
- Handled Mistyped data
- Encoded categorical variables (Label Encoding, One-Hot Encoding)

---

## ✅ Hypotheses Tested

1. **H1**: CSK's victory is independent of the venue  
2. **H2**: Winning the match is independent of winning the toss  
3. **H3**: Winning the match is independent of choosing to bat or field

---

## 📈 Hypothesis Testing Results

- Used **T-Test** for all hypotheses.
- **H1**: Not Rejected — CSK win rate **does not** depend on the venue.
- **H2**: Not rejected — Toss winning does **not significantly** impact match outcome.
- **H3**: Not rejected — Batting/Fielding first does **not significantly** affect winning.

---


## Conclusion & Next Steps

### Key Takeaways:
- Venue doesn not have a **significant influence** on match outcomes.
- Toss decisions show **limited statistical importance**.


## Tools & Libraries

- Python (Pandas, NumPy)
- Seaborn & Matplotlib
- SciPy (T-Test)
- Jupyter Notebook

---


