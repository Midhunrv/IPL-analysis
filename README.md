# 🏏 IPL Analytics Dashboard (2007–2021)

> **Live Report**: [View Power BI Report](https://app.fabric.microsoft.com/reportEmbed?reportId=0272506c-1eba-4408-b4ae-d767224d5ff4&autoAuth=true&ctid=bdd02b43-f9cd-40c0-9e34-c9d0314b687f)

## 📊 Overview

This Power BI report provides an in-depth and interactive analysis of Indian Premier League (IPL) cricket data from 2007 to 2021. It allows users to explore team and player performances, historical records, and season-level statistics using visual storytelling and advanced filters.

---

## 🧩 Key Features

- ✅ **14 Seasons Covered** (2008–2021)
- 🏟️ **875 Matches Analyzed**
- 🎯 **9587 Sixes**, **9281 Wickets**
- 🏆 **Title Winner Insights** per Season
- 📈 **Team Performance Summary** with Win Percentages
- 🧠 **Player Performance Dashboard** with batting, bowling, and fielding stats
- 🎛️ Interactive filters: Player, Team, Venue, Season

---

## 🔍 Report Pages & Insights

### 1. **IPL Overview**
- **KPI Cards**: Matches Played, Sixes, Wickets, Seasons
- **Team Performance Table**: Matches, Wins, Win %, Titles
- **Season Winners Table**
- **Color-coded Season Heatmap**
- **Slicers**: Filter by Team, Player, Venue, Season

### 2. **Player Stats Dashboard**
- **Batting Metrics**: Runs, Strike Rate, 100s, 50s, Average, Balls Faced
- **Bowling Metrics**: Wickets, Economy, Bowling Avg, 5W Hauls
- **Fielding**: Catches, Player of the Match

---

## 📁 Data Sources
Cricsheet Ball by ball data can be found here: https://cricsheet.org/matches/

Data from the website has been consumed and made into the following tables in a star Schema:
-Ball by Ball data (fact)
-Match (dim)
-Player (dim)
-Team (dim)
-Team Player (dim)
These datasets are modeled using Power BI’s data transformation tools and loaded into interactive visuals.

---

## 📈 Visualizations Used

- Clustered Bar/Column Charts  
- Card Visuals for KPIs  
- Heatmaps  
- Tables and Matrix Views  
- Slicers for Filtering  
- Drill-through Support for Detailed View


---
