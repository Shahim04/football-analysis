# 📊 Advanced Scouting & Analysis for Mousa Al-Tamari

## 📌 Project Summary
# This is a data analysis project that i have worked on it to get a clear insihgts and tactical audit of the Stade Rennais winger Mousa Al-Tamari during the 2025/26 season in Ligue 1 only, using data extracted from 'https://understat.com/' and from 'https://fbref.com/en/', the analysis foucses on the position shiftng and game state contexts.
----
## 🛠️ Data Science & Analysis Workflow
to explore the true tactical profile and to get a clear insights, i executed the following steps in Python:
1. Filtered the dataset to isolate observations from the 2025/26 Ligue 1 season using pandas, ensuring the analysis focuses exclusively on the relevant time frame.
2. Grouped and analyzed match metrics across 7 distinct operational roles (AMR, DML, FW, FWR, ML, MR, Sub) to evaluate structural flexibility.
3. Isolated cumulative real outputs (Goals/Assists) against advanced probability models (xG/xA) to evaluate final-third composure and clinical execution.
4. Eliminated substitute-related outliers by excluding player performances with fewer than 20 minutes played, ensuring more reliable and representative analysis.
5. Conducted a comparative variance analysis to handle unequal sample sizes. By executing median scripts, I successfully muted single-game outlier distortions to reveal his true match-to-match performance floor.
----
## 📁 Repository Structure
- `data/` : structured match-logs xlsx datasets extracted from 'https://understat.com/' and added more data from Fbref.
- `notebooks_or_scripts/` : Cleaned Python production scripts handling data parsing, filtering, and metric aggregations.
- `visualizations/` : Exported performance profiles, trendlines, and distribution charts.
----
## 🚀 How to Run
1. Clone the repository: `git clone https://github.com/Shahim04/repo.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Execute the pipeline: `python notebooks_or_scripts/python.sr.py`
