# 📊 IPL Cricket Data Analysis – Decoding Match-Winning Factors

---

## Student Information

**Student Name:** Akshith Reddy Yerva  
**WACP ID:** 1000194  
**CRS:** Artificial Intelligence  
**Unit:** Unit 4 – The Art of Storytelling (Summative Assessment)  
**School Name:** Birla Open Minds International School  

---

# 🏏 Project Overview

This project explores the IPL Complete Dataset (2008–2024) to decode match-winning factors in the Indian Premier League.

The objective is to build an interactive Tableau dashboard and storyboard that uncover:

- Top-performing batsmen and bowlers  
- Team rivalries and dominance patterns  
- Impact of toss decisions and venues  
- Evolution of scoring trends across seasons  

This analysis is designed to provide actionable insights for:

- IPL franchises  
- Coaches and analysts  
- Broadcasters  
- Cricket fans  

---

# 🎯 Purpose & Target Audience

## Purpose
To design an interactive Tableau dashboard that highlights player performance, team rivalries, and match-winning factors using storytelling principles.

## Target Audience
- IPL franchises (strategy & player selection)
- Coaches (match planning & tactics)
- Broadcasters (match narratives)
- Fans (performance insights & rivalries)

The dashboard is built to explain **why teams win**, not just show statistics.

---

# 📂 Data Summary

## Dataset Used
- `matches.csv`
- `deliveries.csv`

## Join Performed
Inner Join on:

```
matches.id = deliveries.match_id
```

This ensures ball-by-ball data aligns correctly with match-level details.

---

# 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Standardised team names (e.g., Delhi Daredevils → Delhi Capitals)
- Handled missing values in winner and result fields
- Removed unnecessary columns (umpire1, umpire2)
- Verified join integrity to prevent duplication
- Ensured season formatting consistency

---
# Tableu storyboard and dashboard link 
https://public.tableau.com/app/profile/akshith.reddy7261/viz/UNIT4SA/Storyboard?publish=yes

# 📊 Visualisations & Analysis (Graph-by-Graph Explanation)

---

## 1️⃣ Top 10 Batters – Total Runs

**Chart Type:** Horizontal Bar Chart  

### Description
Identifies the highest run scorers in IPL history.

### Key Insight
- Virat Kohli leads the all-time run charts.
- Consistency across seasons defines top performers.
- Strike rate combined with total runs indicates impact players.

### Strategic Value
Helps coaches identify dependable top-order anchors and match-defining batsmen.

---

## 2️⃣ Top 10 Bowlers – Wickets

**Chart Type:** Horizontal Bar Chart  

### Description
Highlights the most successful wicket-taking bowlers.

### Key Insight
- High wicket counts strongly influence match outcomes.
- Economy rate complements wicket-taking ability.

### Strategic Value
Identifies death-over specialists and powerplay bowlers.

---

## 3️⃣ Team Rivalry Heatmap

**Chart Type:** Heatmap  

### Description
Displays head-to-head win counts between teams.

### Key Insight
- Some rivalries are highly one-sided.
- Dominance patterns affect psychological edge and fan engagement.

### Strategic Value
Helps teams understand historical matchups and performance trends.

---

## 4️⃣ Toss Impact Analysis

**Chart Type:** Bar Chart  

### Description
Shows win percentage based on toss decision (bat vs field).

### Key Insight
- Toss decisions provide moderate advantage.
- Fielding first shows slightly higher success in recent seasons.

### Strategic Value
Supports tactical planning for toss decisions.

---

## 5️⃣ Venue Influence

**Chart Type:** Stacked Bar Chart  

### Description
Displays match distribution and team performance across venues.

### Key Insight
- Certain venues demonstrate measurable home advantage.
- Venue familiarity influences outcomes.

### Strategic Value
Supports venue-based strategic planning.

---

## 6️⃣ IPL Scoring Trends by Season

**Chart Type:** Line Chart  

### Description
Tracks average runs per match across seasons.

### Key Insight
- Steady increase in scoring rates over time.
- Post-2020 seasons show aggressive batting trends.
- Modern IPL is significantly higher scoring.

### Strategic Value
Reflects tactical evolution and changing gameplay dynamics.

---

# 🎬 Storyboard Flow

The Tableau Storyboard follows this structured narrative:

1. Introduction & Purpose  
2. Player Performance Analysis  
3. Team Rivalries  
4. Match-Winning Factors (Toss & Venue)  
5. League Evolution (Scoring Trends)  
6. Final Insights & Strategic Takeaways  

The storyboard connects individual performance to team success and tactical evolution.

---

# 🔍 Key Insights

- IPL scoring rates have increased significantly after 2020.
- Certain venues provide measurable home advantage.
- Toss decisions offer limited advantage compared to team strength.
- Rivalries remain a strong competitive factor.
- Consistent top-order batsmen significantly impact match outcomes.

---

# 🧪 Testing & Validation

- Verified strike rate and economy calculations manually.
- Cross-checked top run scorers with IPL statistics.
- Tested interactive filters for accuracy.
- Peer-tested usability.

---


# 🏁 Conclusion

The IPL has evolved into a high-scoring, analytics-driven league where:

- Player consistency drives team success.
- Venue dynamics create strategic advantages.
- Toss decisions provide marginal but not decisive impact.
- Rivalries add competitive depth.

This project demonstrates how data storytelling transforms raw statistics into actionable insights.

---

# 🚀 Future Improvements

- Advanced player impact metrics
- Over-by-over pressure analysis
- Predictive modelling for match outcomes
- Machine learning integration

---

# 📚 References

The following resources were consulted to support data validation, cricket statistics understanding, Tableau visualisation techniques, and storytelling structure:

1. ESPN Cricinfo – IPL Statistics Database  
   https://www.espncricinfo.com/

2. Tableau Official Documentation – Data Joins & Relationships  
   https://help.tableau.com/

3. Tableau Story Points Guide  
   https://help.tableau.com/current/pro/desktop/en-us/story_create.htm

4. Data-to-Viz – Choosing the Right Chart Type  
   https://www.data-to-viz.com/

5. Tableau Heatmap Tutorial  
   https://help.tableau.com/current/pro/desktop/en-us/buildexamples_heatmaps.htm

6. Cricket Analytics Concepts – Strike Rate & Economy Explained  
   https://www.cricbuzz.com/cricket-stats

7. IPL Official Website – Historical Records & Player Statistics  
   https://www.iplt20.com/

---

*All visualisations and analysis were independently created using Tableau based on the IPL Complete Dataset provided for academic purposes.*
