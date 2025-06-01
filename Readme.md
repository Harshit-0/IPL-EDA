# IPL Data Analysis

## Project Overview
This project analyzes various aspects of the Indian Premier League (IPL) cricket tournament using multiple datasets, including ball-by-ball deliveries, matches, players, and teams. The goal is to derive insights such as team performances, player contributions, and venue impacts.

---

## Dataset Note
The full IPL dataset is large and cannot be uploaded directly to this repository due to size restrictions.  
**You can download the complete dataset from:**  
[IPL Dataset on Kaggle](https://www.kaggle.com/datasets/himanshupoddar/ipl)

For convenience, a smaller sample subset is used in this project to ensure faster processing and easier handling.

---

## Project Highlights
- Analyzed overall match outcomes and team performances across IPL seasons.  
- Compared home vs away performance of IPL teams using win percentages and match data.  
- Investigated batting and bowling statistics including top run-scorers and wicket-takers.  
- Explored player contributions to teams based on runs and wickets to understand team reliance on key players.  
- Visualized data through insightful plots such as bar plots, line plots, and heatmaps for easy interpretation.

---

## Datasets Used
- `matches.csv` — Details of IPL matches including teams, venue, and results.  
- `deliveries.csv` — Ball-by-ball data for each match including batsman, bowler, runs, and wickets.  
- `players.csv` — Player information including batting and bowling styles.  
- `teams.csv` — List of IPL teams.  
- `teamwise_home_and_away.csv` — Team performances in home and away matches.  
- `most_runs_average_strikerrate.csv` — Batting statistics (used for some insights).

---

## How to Use This Repository
1. Download the full IPL dataset from the Kaggle link above and place the CSV files in the project directory.  
2. Run the provided Jupyter notebooks or Python scripts to perform data cleaning, analysis, and visualization.  
3. Adjust file paths in the code if needed to point to your local dataset location.

---

## Tech Stack
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook

---

## Exploratory Data Analysis (EDA) Summary

In this project, the EDA phase involved:

- **Understanding Dataset Structure:**  
  Loaded and inspected all IPL-related datasets (`matches.csv`, `deliveries.csv`, `players.csv`, etc.) to familiarize with available columns and data types.

- **Data Cleaning:**  
  Handled missing values, fixed inconsistent entries, and standardized column names to ensure smooth analysis.

- **Descriptive Statistics:**  
  Calculated summary statistics such as mean, median, and distribution counts for key features like runs, wickets, matches won, and player stats.

- **Visualizations:**  
  Created diverse plots to uncover patterns and insights, including:  
  - Bar plots for top teams by wins and player runs  
  - Line plots showing season-wise trends in match outcomes  
  - Heatmaps comparing team performances at different venues  
  - Violin plots illustrating the distribution of batting averages and strike rates

- **Key Insights Extracted:**  
  - Team home vs away win percentage differences  
  - Most successful teams per venue  
  - Leading batsmen and bowlers in IPL history  
  - Impact of player contributions on team results

The EDA helped shape further analysis and guided feature selection for deeper insights.
