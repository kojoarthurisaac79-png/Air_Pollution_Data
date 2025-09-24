This project explores and analyzes pollution data stored in a SQL table called Pollution_Data.
The dataset contains measurements of air quality indicators, weather conditions, and prominent pollutants recorded over time.

The aim is to:
	•	Understand trends in air quality.
	•	Practice SQL queries ranging from basics (SELECT, WHERE) to advanced concepts (Window Functions, CTEs, Stored Procedures).
	•	Demonstrate how SQL can be applied to real-world environmental datasets.

⸻

Dataset Structure

Table Name: Pollution_Data

Column Name               Description
date                      Date of observation (converted from text to DATE format)

aqi                       Air Quality Index (indicator of overall air pollution)

pm25_avg                  Average PM2.5 concentration 

pm25_min                  Minimum PM2.5 concentration        

pm25_max                  Maximum PM2.5 concentration


•	Data Cleaning
	•	Converting text dates to SQL DATE format.
	•	Renaming columns for clarity.
	•	Basic Queries
	•	Filtering records by pollutant, temperature, and AQI ranges.
	•	Aggregating averages and maximums.
	•	Window Functions
	•	Using ROW_NUMBER, RANK, DENSE_RANK.
	•	Applying LAG & LEAD to compare AQI across days.
	•	Rolling averages to detect trends.
	•	Stored Procedures
	•	Automating repetitive analysis tasks (e.g., monthly AQI reports).


   Insights You Can Generate
	•	Monthly and yearly air quality trends.
	•	Impact of temperature and humidity on pollution levels.
	•	Identification of the most frequent prominent pollutant.
	•	Short-term and long-term pollution fluctuations.

  Contributions are welcome! Feel free to:
	•	Add new queries or procedures.
	•	Suggest improvements to data cleaning.
	•	Create visualizations based on SQL results.

  This project is not just about SQL queries — it’s about learning how data can tell a story about our environment.
