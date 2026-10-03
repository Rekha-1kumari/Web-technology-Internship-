# Week 4: WeatherPulse - Live Weather Dashboard

**Author:** Rekha Kumari  
**Repository:** [github.com/Rekha-1kumari/Web-technology-Internship-](https://github.com/Rekha-1kumari/Web-technology-Internship-)  

---

## Project Overview
WeatherPulse is a responsive weather dashboard web application built with vanilla JavaScript using `async/await` and the `fetch` API. It consumes the Open-Meteo REST API to provide real-time weather conditions, 24-hour hourly forecasts, and 7-day extended forecasts.

### Key Features:
1. **Live REST API Integration:**
   - Geocoding API for city search worldwide.
   - Forecast API for current weather, hourly forecast, and daily outlook.
2. **Current Weather & Details:**
   - Displays current temperature, feels-like temperature, and weather description with icons.
   - Additional details: Humidity, Wind Speed, Surface Pressure, UV Index, Sunrise, and Sunset.
3. **Location & Units:**
   - "Detect My Location" button using browser Geolocation (`navigator.geolocation`).
   - Temperature unit toggle between Celsius (°C) and Fahrenheit (°F).
   - Quick search chips for popular and recently searched cities.
4. **Error Handling:**
   - Handles offline status, network issues, and invalid city names with user-friendly alerts.

---

## How to Run
Open `index.html` in any web browser. Make sure you have an active internet connection to fetch live data from the Open-Meteo API.