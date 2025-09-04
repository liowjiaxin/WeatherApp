# 🌤️ Weather App  

A simple and responsive weather application built with **HTML, CSS, and JavaScript**.  
It fetches real-time weather data from the **OpenWeatherMap API** and displays key information such as temperature, weather description, humidity, and wind speed.  

## ✨ Features  
- 🔍 Search weather by **city name**  
- 📍 Fetch weather based on **user’s current location** (Geolocation API)  
- 🌡️ Displays temperature, humidity, wind speed, and description  
- 🖼️ Dynamic **weather icons** from OpenWeatherMap  
- 📱 Mobile-friendly UI with clean design  
- ⚠️ Error handling for invalid cities and denied location access  

## 🛠️ Tech Stack  
- **Frontend:** HTML, CSS, JavaScript  
- **API:** [OpenWeatherMap API](https://openweathermap.org/api)  

## 🚀 How to Use  
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
Open index.html in your browser.

Enter a city name in the search bar or allow location access to get weather automatically.

## 🔑 Setup (API Key)
Sign up at OpenWeather to get a free API key.

Open index.html and replace this line with your key:
```
const apiKey = "put-your-api-key-here";
```
## 🛡️ Notes
The API key is exposed in frontend apps, so don’t use this setup in production.

For production, proxy the API through a backend server.

