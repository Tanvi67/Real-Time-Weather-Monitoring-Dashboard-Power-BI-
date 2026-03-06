# 🌦️ Weather & Air Quality Analytics Dashboard

A Power BI dashboard that integrates real-time weather forecasts and air quality data using the OpenWeather API to provide interactive insights on temperature trends, pollution levels, and environmental conditions across multiple cities.

---

# 📊 Project Overview

This project is an interactive **Power BI dashboard** designed to analyze **real-time weather conditions and air pollution data** for multiple cities.  
The dashboard integrates external APIs to provide insights on temperature trends, weather forecasts, and air quality metrics through intuitive visualizations.

The goal of this project is to demonstrate **API integration, data transformation, data modeling, and dashboard design** in a real-world analytics scenario.

---

# 🚀 Key Features

- Real-time weather monitoring
- Hourly and 7-day weather forecasts
- Sunrise and sunset indicators
- Air Quality Index (AQI) tracking
- Pollutant analysis (PM2.5, PM10, CO, NO₂, O₃, SO₂)
- Multi-city comparison using slicers
- Interactive Power BI visuals

---

# 🛠️ Tools & Technologies

- Power BI
- Power Query (M Language)
- DAX (Data Analysis Expressions)
- OpenWeather API
- JSON Data Integration

---

# 🌐 Data Sources

Weather and air pollution data are retrieved from the **OpenWeather API**, which provides:

### Weather Data
- Current weather conditions
- Hourly forecast
- Daily forecast

### Air Pollution Data
- Air Quality Index (AQI)
- Pollutant concentrations such as PM2.5, PM10, CO, NO₂, O₃, and SO₂.

---

# 🗂 Data Model

The dashboard uses a **Star Schema Data Model**.

### Dimension Tables
- **DimCity** – City name with latitude and longitude
- **DimDate** – Date, day, and day name

### Fact Tables
- **FactCurrentWeather**
- **FactHourlyForecast**
- **FactDailyForecast**
- **FactAirPollutionCurrent**
- **FactAirPollutionForecast**

---

# ⚙️ Data Pipeline

1. A city dataset stores city names along with latitude and longitude.
2. Power Query functions dynamically call the OpenWeather API using these coordinates.
3. JSON responses from the API are transformed into structured tables.
4. Data is organized into fact and dimension tables.
5. Power BI visualizations present the insights interactively.

---

# 📈 Dashboard Insights

The dashboard allows users to:

- Monitor real-time weather conditions
- Track air quality levels
- Analyze temperature and forecast trends
- Compare environmental conditions across cities

---

# 📸 Dashboard Preview

Add screenshots of your dashboard here.

```
images/dashboard.png
images/weather_forecast.png
images/air_quality.png
```

---

# 📚 Skills Demonstrated

- API Data Integration
- Data Cleaning and Transformation
- Power Query (M Language)
- Data Modeling (Star Schema)
- DAX Calculations
- Data Visualization in Power BI

---

# 🔮 Future Improvements

- Historical weather trend analysis
- Automated data refresh
- Weather alerts and extreme condition monitoring
- Predictive analytics using machine learning

---

# 👨‍💻 Author

Your Name  
Aspiring Data Analyst / Business Intelligence Developer
