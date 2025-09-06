# 🏏 IPL Analysis Dashboard – Power BI

## 📌 Project Overview  
This project is an **interactive Power BI dashboard** analyzing IPL tournament data across multiple seasons.  
It provides insights into **team performance, batting & bowling statistics, toss decisions, venue outcomes, and match results**.  

---

## 🎯 Key Features  
- **Tournament Summary** – Title winner, Orange Cap (most runs), Purple Cap (most wickets).  
- **Batting Analysis** – Runs, 4’s, 6’s, strike rate for selected players.  
- **Bowling Analysis** – Wickets, economy, average, strike rate for bowlers.  
- **Tournament Stats** – Total 4’s, 6’s, and key highlights.  
- **Venue Insights** – Matches won by runs, wickets, super over, or no result.  
- **Toss Decision Impact** – Fielding vs batting first win comparison.  
- **Team Performance** – Matches won by each franchise.  

---

## 🛠 Tools & Skills Used  
- **Power BI Desktop** – Dashboard, KPIs, Visuals  
- **Power Query** – Data Cleaning & Transformation  
- **DAX** – Measures and Calculations  
- **SQL (MS SQL Server)** – Data storage & queries  
- **Flat Files** – CSV/Excel for raw data  

---

## 📸 Dashboard Preview  
![Dashboard](https://github.com/LahariPonnaganti/IPL-Analysis-Dashboard/blob/main/ipl_dashboard.png)  

---

## 📂 Files in this Repository  
- `IPL_Analysis.pbix` → Power BI dashboard file (handled with Git LFS)  
- `dashboard.png` → Dashboard screenshot  
- `README.md` → Project documentation
-  [📊 IPL_ball_by_ball_dataset.xlsx](https://github.com/LahariPonnaganti/IPL-Analysis-Dashboard/blob/main/Data/ipl_ball_by_ball_2008_2022.csv) → **Download Excel file** (Dataset1).
-  
-  [📊 ipl_matches_2008_2022_dataset.xlsx](https://github.com/LahariPonnaganti/IPL-Analysis-Dashboard/blob/main/Data/ipl_matches_2008_2022.csv) → **Download Excel file** (Dataset1). 

---
## 📊 Dataset Description  

### 1. `ipl_ball_by_ball_2008_2022.csv'
Contains delivery-level data for every ball bowled in IPL matches.  
**Key Columns:**  
- `match_id` → Unique ID linking to the matches dataset  
- `over`, `ball` → Over and ball number  
- `batsman`, `bowler` → Players involved in the delivery  
- `batsman_runs`, `extra_runs`, `total_runs` → Scoring details  
- `dismissal_kind` → Type of wicket (bowled, caught, run out, etc.)  
- `fielder` → Player involved in dismissal  

🔹 **Use:** Enables detailed batting & bowling analysis (strike rates, economy, dismissals, boundary patterns).  

---

### 2. `ipl_matches_2008_2022.csv`
Contains match-level data across IPL seasons.  
**Key Columns:**  
- `id` → Match ID (links with ball-by-ball data)  
- `season` → Year of the match  
- `city`, `venue` → Location details  
- `team1`, `team2` → Competing teams  
- `toss_winner`, `toss_decision` → Toss details  
- `winner` → Match winner  
- `result` → Match result type (normal, super over, no result)  
- `player_of_match` → MVP for the match  

🔹 **Use:** Helps analyze overall tournament trends, team performance, and venue/toss impacts.  

---
## 📈 Key Insights (Across All Seasons)  
- **Most Successful Teams** → Mumbai Indians (5 titles), Chennai Super Kings (5 titles)  
- **Top Run Scorer** → Virat Kohli (6000+ career runs)  
- **Top Wicket Takers** → Dwayne Bravo & Lasith Malinga (highest career wickets)  
- **Most Sixes** → Chris Gayle (record holder for six-hitting)  
- **Venue Insights** → Eden Gardens & Wankhede Stadium host maximum matches/wins  
- **Toss Impact** → Fielding first leads to higher win probability in many matches  
- **Finals Trend** → Teams batting first in finals have higher success rate  
- **Scoring Pattern** → Increasing 4’s & 6’s trend shows more aggressive batting style  


---

## 🚀 How to Use  
1. Clone this repo or download it as a ZIP.  
2. Open `IPL_Analysis.pbix` in **Power BI Desktop**.  
3. Use filters (season, player, venue) to explore insights.  

---

## 👩‍💻 Author  
**Lahari Ponnaganti**  
- Aspiring Data Analyst | Power BI | SQL | Excel  
- [LinkedIn](https://www.linkedin.com/in/lahariponnaganti)  
- [GitHub](https://github.com/LahariPonnaganti)  

---

✨ *If you find this project useful, please ⭐ star the repository!*  
