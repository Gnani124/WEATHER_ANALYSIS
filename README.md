Interactive weather dashboard using Weather API with real-time data visualization in Power BI.

**Repository:** `Weather-API-Dashboard-PowerBI`

**Description:**

This repository contains an interactive Power BI dashboard built using real-time data from a Weather API. The dashboard offers comprehensive visual insights into weather conditions, environmental factors, and air quality to support data-driven decisions for environmental monitoring, city planning, or personal awareness.


🖥️ **Dashboard Overview**

### 🌤️ Real-Time Weather Dashboard

Displays key weather and environmental metrics with live API data.

**💡 Key Metrics:**

* Temperature (Current, Min, Max)
* Humidity, Visibility, UV Index
* Wind Speed and Direction
* Rain Probability and Precipitation
* Sunrise and Sunset Times

### 🌫️ Air Quality Analysis

Breakdown of major pollutants and overall AQI status.

**📊 Visuals:**

* AQI Gauge by City
* Pollutant Levels (PM10, PM2.5, CO, NO2, SO2, O3)
* Temperature Trends Over Time
* Weather Forecast for 7 Days
* Rainfall and Humidity Heatmaps
* Comparative City Analysis (if multiple cities are tracked)

---

📌 **Key Insights**

* Real-time API-driven weather and pollution tracking.
* Clear visualizations for environmental monitoring.
* Helpful for decision-makers in climate, health, and travel sectors.



--- https://www.weatherapi.com/api-explorer.aspx  ----- API Link


--- key = Json.Document(Web.Contents("http://api.weatherapi.com/v1/forecast.json?key=39f17bc9098f4d20873133753252306&q=Andhra pradesh&days=7&aqi=yes")) --- im using this Api link 

![Screenshot 2025-06-25 151850](https://github.com/user-attachments/assets/842d198d-29d0-4577-8d38-b30a48104131)


