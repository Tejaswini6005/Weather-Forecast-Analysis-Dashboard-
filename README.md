🌦 Weather Dashboard – Power BI
📌 Project Summary

This project is a real-time Weather Dashboard built in Power BI using a Weather API instead of static CSV files.
The main objective is to demonstrate API integration, data transformation, and dashboard creation in Power BI.

🎯 Project Goal

Connect Power BI with a Weather API for real-time weather data.

Perform data extraction, transformation, and modeling in Power Query.

Build an interactive dashboard to analyze current weather, forecasts, and air quality across multiple cities.

🌍 Data Source – Weather API

Provides real-time weather, forecast, and historical data.

Requires authentication via API Key.

Data returned in JSON format, compatible with Power BI.

Free Tier: Up to 1M calls/month with 3-day forecast.

🔑 Steps Followed
1. API Setup

Signed up for Weather API → Verified email → Generated API key.

Tested API queries in API Explorer (Example: Ajmer).

2. Load Data into Power BI

Used Get Data → Web to connect API → JSON output imported.

Extracted:

Current Weather

Forecast by Day

Forecast by Hour

Air Quality Index (AQI)

Location Details

3. Data Transformation (Power Query)

Duplicated queries for multiple cities (Ajmer, Hyderabad, Mumbai, Noida, etc.)

Appended queries into a Master Table.

Split Master Table into separate tables:

Current Data

Forecast by Day

Forecast by Hour

Location Data

Cleaned data → removed unnecessary columns & duplicates.

4. Data Modeling

Manually created relationships in Model View.

Location Name set as the primary key across tables.

Removed unwanted auto-generated relationships for clarity.

5. Visualization & Dashboard

Added city slicer to switch between cities dynamically.

Used a dark theme for professional look.

Created a measures table for calculated metrics.

Dashboard shows:

Temperature & Humidity

Forecast (Daily & Hourly)

Air Quality Index (AQI)

City & Location details

Used custom visuals: cards, slicers, and interactive charts.

📈 Dashboard Features

✅ Real-time weather updates via API
✅ City selection slicer
✅ Current weather cards (Temp, Humidity, Wind, AQI)
✅ Forecast by day & hour (Line/Bar charts)
✅ Dark theme with customized visuals

🚀 How to Use

Clone this repository.

Open the Weather_Dashboard.pbix file in Power BI Desktop.

Replace with your own Weather API key inside the data source settings.

Refresh the dashboard → Real-time weather data will load.

📌 Tools & Skills

Power BI Desktop – Data modeling & dashboard creation

Power Query (M Language) – Data extraction & transformation

DAX – Calculated measures

Weather API – Real-time JSON data

📜 Author

Tejaswini Singh
