# data-analysis-Dashboard
This project is a Power BI dashboard focused on analyzing air quality levels across various locations. It provides insights into pollution trends by visualizing key metrics such as PM2.5, PM10, NO₂, CO, SO₂, and AQI (Air Quality Index).

# Dashboard Preview:
Dashhborad Preview (https://github.com/user-attachments/assets/80b4a414-56ec-4681-95de-27ccb5d6e4c3)
Air Quality Dashboard – Power BI Project

Overview:
This Power BI dashboard is built to analyze and visualize air quality data across different regions and time periods. The purpose is to provide an intuitive and interactive platform for users to explore air pollution trends and make informed decisions based on environmental data.

# Key Insights
Identified most polluted cities and time periods
Tracked seasonal variations in air pollution
Compared pollutant levels to WHO standards
Suggested areas for environmental action

# Key Metrics:
- PM2.5: Fine particulate matter with a diameter less than 2.5 micrometers.
- PM10: Particulate matter with a diameter of 10 micrometers or less.
- NO₂ (Nitrogen Dioxide): A gaseous air pollutant produced as a result of road traffic and other fossil fuel combustion processes.
- CO (Carbon Monoxide): A colorless, odorless gas that can be harmful when inhaled in large amounts.
- SO₂ (Sulfur Dioxide): A toxic gas produced by the burning of fossil fuels.
- AQI (Air Quality Index): A composite index used to communicate how polluted the air currently is or how polluted it is forecast to become.

# Dashboard Features:
- Date Slicer: Allows users to filter data based on time range.
- City/Location Filter: Enables comparison of pollution levels across cities or monitoring stations.
- Line Charts: Show trends over time for each pollutant.
- Bar Charts: Visualize pollutant concentration by city or day.
- Card Visuals: Display key AQI metrics like Max AQI, Average AQI, and Number of Days with Poor Air Quality.
- Map Visualization (if used): Plots the locations and respective AQI levels for a geographical perspective.
- Heatmap: Shows the intensity of pollution by month or week.

# Data Preparation:
- Null values were handled either by forward-filling or replacing with mean/median values.
- Date columns were transformed for better time-series analysis.
- Categorical fields such as city names were normalized for consistency.
- AQI categories (Good, Satisfactory, Moderate, Poor, Very Poor, Severe) were created using DAX based on AQI value ranges.

# Technologies Used:
- Power BI Desktop
- USED Power Query for data cleaning

# Project Goal:
The aim of this dashboard is to assist users in understanding air quality dynamics in a visual format, encourage awareness of pollution levels, and provide tools for analysis and reporting.

Instructions to Use:
1. Open the `power bi project.pbix` file using Power BI Desktop.
2. Use the slicers to filter data by date or city.
3. Hover over visuals to see detailed insights.
4. Customize or extend the dashboard with your own data source if needed.

"""



