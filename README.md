# 🌦️ Weather Data Collector

## 📌 Overview
This project collects real-time weather data from the [OpenWeather API](https://openweathermap.org/api) and logs it into a Google Sheet. It tracks temperature, humidity, sky conditions, wind speed, and other useful metrics for various cities across the world.

It is composed of two Jupyter Notebooks:
- 📘 `weather_data_collector.ipynb`: Automatically fetches and appends weather data to Google Sheets.
- 🤖 `weather_bot.ipynb`: A chatbot-style interface that allows users to interactively request weather information.

## 🛠️ Technologies Used
- **Python**
- **OpenWeatherMap API**
- **Google Sheets API (via gspread)**
- **Jupyter Notebook**

## 🗂️ Features
- Collects weather data in real time for any city
- Saves data to Google Sheets in a structured format
- Supports chatbot-style user interaction
- Handles multiple cities with looping logic
- Logs timestamps, weather icons, sunrise/sunset, and more

## 📊 Google Sheet

The collected weather data is stored in the Google Sheet. You can access it here:

[Weather Data Google Sheet](https://docs.google.com/spreadsheets/d/1K-YGMhduhrLbnfIiMd0atYu064Nm9vshZ6_K59SddM4/edit?usp=sharing)

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/Stephen200798/weather-data-collector.git
cd weather-data-collector
