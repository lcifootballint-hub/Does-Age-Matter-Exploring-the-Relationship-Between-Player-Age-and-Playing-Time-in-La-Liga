# Does-Age-Matter-Exploring-the-Relationship-Between-Player-Age-and-Playing-Time-in-La-Liga
This repository investigates the correlation between player age and total playing time across La Liga clubs. By combining sports data analytics and statistical modeling, this project examines whether elite Spanish football favors youth development, peak-age reliability, or veteran experience.

# Does Age Matter? Exploring the Relationship Between Player Age and Playing Time in La Liga

**Football Analytics | Sports Data Science | Player Scouting**

## 1. Project Overview

Does a footballer's age influence the opportunities they receive on the pitch?

This project investigates the relationship between player age and playing time in Spain's La Liga, using player-level league statistics from the 2024/25 season. The analysis examines whether younger, peak-age, and older players receive different amounts of playing time and whether these patterns vary across playing positions.

The project combines football statistics, data visualisation, and statistical analysis to understand how age relates to first-team opportunities. The ultimate goal is to translate data into meaningful insights that can support player evaluation, recruitment, and scouting decisions.

## 2. Research Objectives

The main objectives are to:

- Investigate the relationship between player age and total minutes played.
- Compare playing time across different age groups.
- Examine differences between goalkeepers, defenders, midfielders, and forwards.
- Explore the relationship between age, appearances, and starting opportunities.
- Evaluate whether age remains associated with playing time after accounting for position and club.
- Identify potential scouting insights from the observed patterns.

## 3. Research Questions

1. Is player age associated with total minutes played in La Liga?
2. Which age groups receive the most playing time?
3. Does the relationship between age and playing time differ by position?
4. Are younger players less likely to start matches than experienced players?
5. Does age remain associated with playing time when position and club are considered?

## 4. Dataset

The project uses player-level statistics from Spain's La Liga for the 2024/25 season.

**Data source:** [FBref — La Liga Player Statistics](https://fbref.com/en/comps/12/2024-2025/stats/Stats-2024-2025-La-Liga)

### Key variables

| Variable | Description |
|---|---|
| Player | Player name |
| Age | Player age during the season |
| Squad | Player's club |
| Position | Primary or listed playing position |
| MP | Matches played |
| Starts | Number of matches started |
| Min | Total minutes played |

Additional variables may be included depending on data availability.

## 5. Methodology

The analysis follows a structured data science workflow.

**Step 1 — Data Collection:** Obtain the player statistics and document the source.

**Step 2 — Data Cleaning:** Inspect missing values, correct data types, standardise positional categories, and check for duplicate records.

**Step 3 — Exploratory Data Analysis:** Examine player age distributions, playing-time distributions, appearances, and starting opportunities.

**Step 4 — Data Visualisation:** Create scatter plots, box plots, and comparative charts to investigate relationships between age and playing time.

**Step 5 — Statistical Analysis:** Use Pearson and Spearman correlation coefficients to examine associations. Where appropriate, fit regression models incorporating age, position, and club.

**Step 6 — Interpretation:** Evaluate the results and discuss their relevance to football analysis and scouting.

## 6. Tools and Technologies

- **Python** — Data analysis and statistical computing
- **pandas** — Data manipulation and cleaning
- **NumPy** — Numerical operations
- **Matplotlib and Seaborn** — Data visualisation
- **SciPy** — Statistical tests and correlation analysis
- **Statsmodels** — Statistical modelling
- **Jupyter Notebook** — Interactive analysis and documentation

## 7. Planned Visualisations

The project aims to include:

1. **Age vs. Minutes Played:** Investigating the relationship between player age and total playing time.
2. **Playing Time by Age Group:** Comparing distributions and median minutes across age categories.
3. **Age and Playing Time by Position:** Exploring differences between positional groups.
4. **Starts and Appearances by Age Group:** Examining differences in starting opportunities.

## 8. Repository Structure

```text
laliga-age-playing-time-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_collection.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_exploratory_data_analysis.ipynb
│   └── 04_statistical_analysis.ipynb
│
├── visualizations/
│
├── reports/
│   └── scouting_insights.md
│
├── requirements.txt
├── .gitignore
└── README.md
```

## 9. Key Findings

*This section will be updated after the analysis is completed.*

The final results will summarise the observed relationship between age and playing time, differences across positions, and the implications for player evaluation.

No conclusions are assumed before examining the data.

## 10. Relevance to Football Scouting

Playing time can provide useful context when evaluating a footballer's development and first-team involvement.

This analysis may help scouts and analysts:

- Identify younger players with limited senior-team exposure.
- Compare playing-time patterns across positions.
- Understand the age profile of players receiving regular minutes.
- Generate questions for further player evaluation and recruitment.

However, limited playing time does not automatically indicate low ability or high potential. Injuries, tactical suitability, squad depth, transfers, and competition for places must also be considered.

## 11. Limitations

This study focuses on a single La Liga season. The findings may not generalise to other seasons or leagues.

Age and playing time may be associated without age directly causing differences in playing opportunities. Other factors, including injuries, player quality, club strength, tactical roles, and match availability, may influence the results.

The analysis will acknowledge these limitations when interpreting statistical relationships.

## 12. Future Development

Potential extensions include:

- Comparing multiple La Liga seasons.
- Extending the analysis to Europe's top five leagues.
- Investigating age profiles within individual positions.
- Exploring relationships between playing time, goals, assists, and other performance indicators.
- Developing an interactive football scouting dashboard.

## 13. Author and Project

**LCI Football Intelligence**

Football Analytics | Data Science | Player Scouting

This project explores how statistical analysis can provide evidence-based insights into player development, first-team opportunities, and recruitment.


