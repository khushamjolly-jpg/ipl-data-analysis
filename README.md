# 🏏 IPL Data Analysis

Exploratory data analysis on IPL cricket data (2008–2017) using Python, Pandas, NumPy, Matplotlib and Seaborn.

## 📊 Analyses Performed

### Batting Analysis
- **Top Run Scorers** — All-time leading run scorers with batting first vs chasing split
- **Chasing vs Batting First** — Batsmen who perform better while chasing vs setting targets
- **Boundary Percentage** — Batsmen who score the highest % of runs in boundaries (4s and 6s)

### Bowling Analysis
- **Top Wicket Takers** — All-time leading wicket takers with bowling first vs defending split

### Team & Match Analysis
- **Team Win Percentage** — Win rates across all IPL franchises (with data cleaning)
- **Toss Impact Analysis** — Does winning the toss help? Batting vs fielding first breakdown
- **Powerplay Score vs Win Probability** — At what powerplay score does win probability exceed 50%?

### Trends
- **Runs Per Over** — How scoring patterns change across all 20 overs

## 🔍 Key Insights
- Virat Kohli is the all-time leading run scorer — equally dangerous batting first and chasing
- SL Malinga leads all bowlers in wicket count — almost perfectly balanced in both innings
- SP Narine scores 79.70% of his runs in boundaries — highest boundary % among qualified batsmen
- RV Uthappa is the best chaser — 800 more runs when chasing vs batting first
- AB de Villiers is the best batting first specialist — 817 more runs when batting first
- Toss winners only win 51.59% of matches — barely better than a coin flip
- Teams that field first win 55.79% of matches vs 45.73% when batting first
- Scoring 55+ in powerplay gives a 70% chance of winning batting first
- Scoring under 45 in powerplay means you're more likely to lose batting first

## 🛠️ Tools Used
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- JupyterLab

## 📁 Dataset
IPL dataset sourced from [Kaggle](https://www.kaggle.com/datasets/ramjidoolla/ipl-data-set)
- `matches.csv` — 756 matches with toss, venue, winner details
- `deliveries.csv` — 179,078 ball-by-ball records
- `deliveries.csv` — 179,078 ball-by-ball records

## 🔍 Key Insights
- Virat Kohli is the all-time leading run scorer in IPL history
- SL Malinga leads all bowlers in wicket count
- Teams that choose to field first win 55.79% of the time vs 45.73% when batting first
- Toss winners only win 51.59% of matches — barely better than a coin flip
