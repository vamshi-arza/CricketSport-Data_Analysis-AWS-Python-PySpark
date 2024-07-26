# Cricket Data Analysis

### Project Architecture

![ipl art](https://github.com/user-attachments/assets/3bc429b8-226f-4fb4-a578-80fe7ec7a6eb)

### Project Overview

This project utilizes PySpark to analyze IPL cricket data from CSV files stored in an S3 bucket. It aims to calculate runs, identify impactful balls, and examine toss and win margins. Data cleaning involves filtering invalid entries and normalizing player names. Key insights include running total runs per over, win margin categorization, and toss-match winner correlations. Technologies used include Apache Spark, PySpark, AWS S3, and databricks, delivering strategic analytics on match performance, player statistics, and team dynamics.

### Data Source

This project utilizes data publicly available on the data.world platform, specifically the "IPL Data Till 2017" dataset by user raghu543 (https://data.world/raghu543/ipl-data-till-2017).

### Tools Used

- Amazon S3 - For storing and accessing CSV files.
- Databricks - For creating and managing the Spark session and data processing.
- Python - For scripting and data manipulation.
- SQL - For querying and manipulating data within Spark.
- PySpark - For data processing and analysis using Apache Spark.

### Data Cleaning

- Filtered out invalid and missing entries.
- Ensured consistent data formats.
- Normalized player names for accuracy.
- Examined columns with null values and removed rows with significant missing information.
- Standardized player names to handle variations and typos.
- Ensured dataset accuracy and consistency for reliable analysis.

### Exploratory Data Analysis

- Data Overview - Examined dataset structure, types, and missing values.
- Descriptive Statistics - Calculated means, medians, and standard deviations for numerical features.
- Distribution Analysis - Analyzed distributions of key variables (e.g., runs, wickets) using histograms and density plots.
- Correlation Analysis - Investigated relationships between variables using correlation matrices and scatter plots.
- Categorical Data - Explored categorical variables like team names and match venues through bar plots and frequency counts.
- Patterns and Trends - Identified patterns in match outcomes, scoring trends, and player performances.

### Results

- Feature Importance: Identified key features influencing match results, such as team strength, venue, and weather conditions.
- Winning Patterns: Analyzed trends in winning teams and match conditions, highlighting significant factors that contribute to victory.
- Player Impact: Evaluated individual player performances and their impact on match outcomes.
- Venue Effects: Observed the influence of different venues on team performance and match results.
- Comparative Analysis: Compared model predictions with actual outcomes, revealing insights into prediction accuracy and areas for improvement.

### Conclusion

This project showcases an efficient PySpark approach for IPL cricket data analysis. It involves defining schemas, filtering data, calculating runs, and enhancing match DataFrames with additional metrics. By normalizing player names and integrating career statistics, it provides valuable insights into match dynamics and player performance. The repository offers a scalable framework for further analysis and machine learning applications.
