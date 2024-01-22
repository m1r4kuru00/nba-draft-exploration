# NBA Draft Exploration

## Project Overview

This data analysis project aims to explore whether there is a significant difference between players drafted in higher rounds compared to those drafted in lower rounds or left undrafted.

## Data Source

 [**all_seasons.csv:**](https://www.kaggle.com/datasets/justinas/nba-players-data) This dataset from Kaggle, compiled by Justinas Cirtautas, contains the following information:

- `player_name`: Name of the player
- `team_abbreviation`: Abbreviated name of the team the player played for (at the end of the season)
- `age`: Age of the player
- `player_height`: Height of the player (in centimeters)
- `player_weight`: Weight of the player (in kilograms)
- `college`: Name of the college the player attended
- `country`: Name of the country where the player was born (not necessarily the nationality)
- `draft_year`: The year the player was drafted
- `draft_round`: The draft round in which the player was picked
- `draft_number`: The number at which the player was picked in his draft round
- `gp`: Games played throughout the season
- `pts`: Average number of points scored
- `reb`: Average number of rebounds grabbed
- `ast`: Average number of assists distributed
- `net_rating`: Team's point differential per 100 possessions while the player is on the court
- `oreb_pct`: Percentage of available offensive rebounds the player grabbed while on the floor
- `dreb_pct`: Percentage of available defensive rebounds the player grabbed while on the floor
- `usg_pct`: Percentage of team plays used by the player while on the floor ((FGA + Possession Ending FTA + TO) / POSS)
- `ts_pct`: Measure of the player's shooting efficiency that takes into account free throws, 2 and 3 point shots (PTS / (2*(FGA + 0.44 * FTA)))
- `ast_pct`: Percentage of teammate field goals the player assisted while on the floor
- `season`: NBA season

## Tools

- Pandas: Data Cleaning - Exploratory Data Analysis
- Matplotlib: Data Visualization
- Seaborn: Data Visualization
- scipy.stats: Hypothesis Testing

## Data Cleaning / Preparation

In the initial data preparation phase, we performed the following tasks:
- Data loading and inspection
- Handling missing values
- Data cleaning and formatting

## Exploratory Data Analysis (EDA)

EDA involved exploring the NBA All Seasons data to answer the following questions:

1. What is the distribution of drafted and undrafted players in the dataset?
2. Do players who were drafted in earlier rounds tend to have higher average points or better performance?

## Key Findings and Insights:

- Players drafted in the **first round** consistently outperform others across various performance metrics.
- **Second-round** draftees also demonstrate strong performance, although generally not reaching the levels of **first-round** picks.
- **Undrafted players**, on average, lag behind drafted players in points, rebounds, and assists.
- The analysis provides valuable insights for assessing and comparing player performance based on their draft round.

Additionally, it's worth noting that while the visualization suggests a potential higher average performance for players drafted in the later rounds (3rd - 8th) compared to those drafted in the first and second rounds, caution should be exercised in interpreting these findings. The smaller number of observations for players drafted in the latter rounds may impact the robustness of the analysis.

