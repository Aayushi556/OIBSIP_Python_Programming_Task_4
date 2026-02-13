# 🌦️ Weather App (HTML + CSS + JavaScript)

A simple and beautiful **Weather Web App** that fetches real-time weather data using the **OpenWeather API**.

Users can enter any city name and instantly see:
- Temperature 🌡️
- Humidity 💧
- Weather description ☁️
- Weather emoji 🌤️

---

## ✨ Features

- Real-time weather data using API
- Clean and responsive UI
- Dynamic weather emoji based on conditions
- Error handling for invalid city
- Simple and beginner-friendly project

---

## 🖥️ App Preview

The app includes:
- City input field
- Get Weather button
- Weather card showing:
  - City name
  - Temperature (°C)
  - Humidity
  - Weather condition
  - Weather emoji

---

## ⚙️ Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeather API

---

## 🔑 API Used

This project uses the **OpenWeather API**:

https://openweathermap.org/api

---

## ▶️ How to Run

1. Download or clone this repository
2. Keep all files in same folder:
   - `index.html`
   - `weather_app.css`
   - `weather_app.js`
3. Open **index.html** in your browser

That's it 🎉

---


---

## 🧠 How It Works

1. User enters a city name
2. App sends request to OpenWeather API
3. API returns weather data in JSON format
4. JavaScript extracts:
   - City name
   - Temperature
   - Humidity
   - Weather description
5. App dynamically updates the weather card

---

## 🌡️ Temperature Conversion

OpenWeather gives temperature in **Kelvin**.  
The app converts it to Celsius using:


---

## 😀 Weather Emoji Logic

| Weather Condition | Emoji |
|---|---|
| Thunderstorm | ⛈️ |
| Rain | 🌧️ |
| Snow | ❄️ |
| Fog | 🌫️ |
| Clear | ☀️ |
| Clouds | ☁️ |

---

## ⚠️ Error Handling

The app safely handles:
- Empty input
- Invalid city name
- API fetch errors

User sees a clear error message on screen.

---

## 💡 Future Improvements

- Add weather icons 🌤️
- Show wind speed 💨
- Add 5-day forecast 📅
- Add dark mode 🌙
- Detect user location 📍

---

## 👩‍💻 Author

Made with ❤️ using HTML, CSS & JavaScript

---

⭐ If you like this project, give it a star on GitHub!

## 📂 Project Structure

