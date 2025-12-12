This project analyzes hourly air quality data (PM10 and PM2.5) using the Open-Meteo Air Quality API for both past and forecasted days. 
PM10 and PM2.5 levels are strongly correlated, with pollution frequently exceeding safe levels (>50 µg/m³), and peak around 3 PM before gradually decreasing. 
The analysis includes high pollution flags, hourly trends, and feature engineering to enhance insights. Cleaned data is stored in an SQLite database, and visualizations like heatmaps, bar charts, and line plots clearly highlight patterns and correlations. 
Tools used include Python (pandas, requests, matplotlib, seaborn) and SQLite, enabling efficient data collection, analysis, and storage.
