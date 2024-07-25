# Cricket Data Analysis

### Project Architecture

![ipl art](https://github.com/user-attachments/assets/3bc429b8-226f-4fb4-a578-80fe7ec7a6eb)

### Project Overview

This project utilizes PySpark to conduct a comprehensive analysis of Indian Premier League (IPL) data. Key tasks include data ingestion, cleaning, transformation, and enrichment. It calculates metrics like total and average runs, identifies high-impact deliveries, and explores player performance, team dynamics, and match outcomes. The analysis leverages visualizations to uncover trends and patterns in player statistics, team performance, and match factors.

### Data Source

This project utilizes data publicly available on the data.world platform, specifically the "IPL Data Till 2017" dataset by user raghu543 (https://data.world/raghu543/ipl-data-till-2017).

### Exploratory Data Analysis

- Analyzed the distribution of high-impact deliveries to understand their frequency and impact on match outcomes.
- Investigated the relationship between win margin and match outcome categories.
- Explored the distribution of player roles (captain, keeper, etc.) across different teams.
- Explored relationships between different entities (players, teams, matches) using techniques like count plots or cross-tabulations.

### Results

- High-impact deliveries: A significant portion of runs are scored through high-impact deliveries (boundaries and wickets), indicating their crucial role in match outcomes.
- Win margins: High win margins are relatively infrequent, suggesting most matches are closely contested.
- Data quality: The dataset appears to be relatively clean, with no immediate issues identified in terms of missing values or inconsistencies.
- Data structure: The creation of temporary views facilitates efficient query execution and analysis.

