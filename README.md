# 🌤️ SkyPulse — Live Weather Dashboard

A sleek, minimal weather dashboard that delivers real-time weather data for any city in the world — built with pure HTML, CSS, and JavaScript.

🔗 **Live Demo:** [live-weather-dashboards.netlify.app](https://live-weather-dashboards.netlify.app)

<img width="1891" height="908" alt="Image" src="https://github.com/user-attachments/assets/3a681f1b-c2f5-4729-bf87-4d8bba26ffa3" />
<img width="1908" height="905" alt="Image" src="https://github.com/user-attachments/assets/1022a562-6b5f-44f5-8df5-f21503fe6930" />

## ✨ Features

- 🔍 **City Search** — Search any city worldwide instantly
- 🌡️ **Live Temperature** — Current temp with feels-like reading
- 💧 **Detailed Stats** — Humidity, wind speed, visibility, pressure
- 🌅 **Sunrise & Sunset** — Local times for any city
- 🌦️ **Weather Icons** — Dynamic emoji icons based on weather condition
- ⭐ **Animated Starfield** — Beautiful dark UI with twinkling stars
- ⌨️ **Keyboard Support** — Press Enter to search
- 📱 **Responsive** — Works on mobile and desktop

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/skypulse.git
cd skypulse
```

### 2. Get your API Key

- Go to [OpenWeatherMap](https://openweathermap.org/) and create a free account
- Generate your API key from the dashboard

### 3. Add your API Key

Open `index.htm` and replace the API key on line ~170:

```javascript
const API_KEY = "YOUR_API_KEY_HERE";
```

### 4. Open in browser

Just open `index.htm` directly in your browser — no server or build step needed!

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling, animations, glassmorphism |
| Vanilla JavaScript | Logic, API calls |
| OpenWeatherMap API | Live weather data |
| Google Fonts | Bebas Neue + DM Sans |

## 📁 Project Structure

```
skypulse/
│
└── index.htm       # Single file — all HTML, CSS, and JS
```

## 🌐 API Reference

This project uses the OpenWeatherMap Current Weather API:

```
GET https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric
```

Free tier allows up to 60 calls/minute — more than enough for personal use.

## 📸 UI Highlights

- Dark navy background (`#0a0f1e`) with glassmorphism cards
- Gradient accent colors — sky blue (`#38bdf8`) + indigo (`#818cf8`)
- Floating weather emoji animation
- Smooth fade-in/fade-up transitions on load

## ⚠️ Note

Keep your API key private. Do not commit it to public repositories. Use environment variables or a backend proxy for production deployments.

## 📄 License

MIT License — free to use, modify, and distribute.
