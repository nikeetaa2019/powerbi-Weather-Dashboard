Weather Dashboard using WeatherAPI & Power BI
This project is a visually interactive weather monitoring dashboard created using Power BI, which fetches live and forecast weather data via the WeatherAPI. The dashboard displays real-time temperature, humidity, air quality index, UV index, wind speed, and 7-day weather forecasts for multiple cities like Pune, Kolhapur, Mumbai, and Nagpur.

Features
Real-time Weather Data (via API)

Multi-city Comparison (Pune, Kolhapur, etc.)

Air Quality Index (AQI), CO, PM10, PM2.5, NO2, SO2, O3 levels

Temperature, Humidity, Wind Speed, Pressure, Visibility

7-Day Weather Forecast Line Chart

Sunrise and Sunset Timings

Chance of Rain (Bar chart)

Tools & Technologies Used
Power BI Desktop

WeatherAPI (Free tier)

JSON to Table transformation in Power Query

Custom visuals and formatting

Web connector in Power BI

Dashboard Screenshots
Kolhapur Weather Dashboard
Pune Weather Dashboard

How It Works
API Integration

Data is fetched using WeatherAPI

Power BI Web Connector

The API URL is used with the "Web" data source to load JSON responses.

Power Query Transformations

JSON is parsed and expanded

Tables are shaped into a clean, structured dataset

Visualizations

Cards for current weather

Line charts for 7-day temperature

Donut chart for AQI index

Bar charts for rain chance

Icons, slicers, and location toggles


