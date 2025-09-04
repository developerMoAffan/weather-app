# Weather App 🌦️

A simple Python weather application built while following [Dave Gray's Python Course](https://www.youtube.com/).
The app fetches real-time weather data using an external API and displays it in a user-friendly way.

---

## 🚀 Features

* Get current weather for any city 🌍
* Shows temperature, weather condition, and more
* Uses `requests` for API calls
* Environment variables managed with `python-dotenv`

---

## 📦 Requirements

* Python 3.8+
* Virtual environment (`venv`) recommended

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ⚙️ Setup & Usage

1. Clone this repository:

   ```bash
   git clone git@github.com:your-username/weather-app.git
   cd weather-app
   ```

2. Create a virtual environment:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate   # Linux/Mac
   .venv\Scripts\activate      # Windows
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Create a `.env` file in the project root:

   ```env
   WEATHER_API_KEY=your_api_key_here
   ```

   👉 Get a free API key from [OpenWeather](https://openweathermap.org/api).

5. Run the app:

   ```bash
   python weather.py
   ```

---

## 📂 Project Structure

```
weather-app/
│-- weather.py
│-- .env.example
│-- requirements.txt
│-- README.md
│-- .gitignore
│-- .venv/
```

---

## 📝 Notes

* This project was created as a learning exercise from Dave Gray’s Python Course.
* Feel free to fork and extend it — e.g., add a GUI with Tkinter, or display 5-day forecasts.

---

## 📜 License

This project is for educational purposes. You may use and modify it freely.
