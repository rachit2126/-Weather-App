# 🌦 Weather App

A simple Weather Application built using **HTML, CSS, and JavaScript** that fetches live weather data from the **OpenWeatherMap API**.  
This project demonstrates how to work with APIs, handle asynchronous JavaScript, and update the UI dynamically.

---

## 🚀 Project Overview

This app allows users to:

- Enter the name of a city
- Fetch real-time weather data
- Display:
  - City name
  - Temperature in Celsius
  - Weather description
- Show an error message if the city is not found

The goal of this project is to understand how JavaScript communicates with external APIs and updates webpage content.

---

## 🛠 Technologies Used

| Technology | Purpose |
|-----------|---------|
| HTML | Page structure |
| CSS | Styling and layout |
| JavaScript | App logic |
| Fetch API | Getting data from server |
| OpenWeatherMap API | Weather data source |

---

## ⚙️ How the App Works

1. The user enters a city name.
2. When the **Get Weather** button is clicked:
   - JavaScript reads the input.
   - A request is sent to the OpenWeatherMap API.
3. The API responds with weather data in JSON format.
4. The app extracts:
   - City name
   - Temperature
   - Weather description
5. The information is displayed on the screen.
6. If the city is invalid, an error message is shown.

---

## 💡 Concepts Practiced

- DOM Manipulation
- Event Listeners
- Async / Await
- Fetch API
- JSON Data Handling
- Error Handling
- Conditional UI Rendering

---

## 🔑 API Integration

This project uses:

**OpenWeatherMap API**

Data is requested using this format:

https://api.openweathermap.org/data/2.5/weather?q=CITY_NAME&appid=API_KEY&units=metric

---

## 📂 Project Structure

weather-app/
│── index.html
│── README.md

yaml
Copy code

---

## 🌍 Live Demo

After enabling GitHub Pages, the app can be accessed through a browser.

---

## 📈 Learning Outcome

This project helps in understanding:

✔ How web apps fetch real-time data  
✔ How APIs work  
✔ How asynchronous JavaScript functions  
✔ How dynamic content is displayed  

---

## ✨ Future Improvements

- Show weather icons
- Add humidity and wind speed
- Auto-detect user location
- 5-day forecast
- Loading animation

---

## 👨‍💻 Author

Created as a beginner-friendly project to practice JavaScript API integration.
