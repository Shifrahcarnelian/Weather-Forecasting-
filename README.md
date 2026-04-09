## Weather App (Python CLI)

A simple command-line weather application built using Python that fetches real-time weather data and a 5-day forecast for any city using the OpenWeatherMap API.

---

## Features

* Get current weather details
* View 5-day weather forecast (with timestamps)
* Displays wind speed, humidity, pressure, and more
* Continuous input loop until user exits
* Handles invalid city names gracefully

---

## Technologies Used

* Python
* requests library
* OpenWeatherMap API
* datetime module

---

## Project Structure

```
weather-app/
│
├── weather.py      
└── README.md       
```

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
```
### 2. Install Dependencies

Make sure Python is installed, then install the required library:

```bash
pip install requests
```
### 3. Get API Key

1. Go to [https://openweathermap.org/api](https://openweathermap.org/api)
2. Sign up and generate your API key
3. Replace this line in the code:

```python
API_KEY = "YOUR_API_KEY"
```

with:

```python
API_KEY = "your_actual_api_key"
```
### 4. Run the Application

```bash
python weather.py
```
## Usage

* Enter a city name when prompted
* Example:

```
Enter city name (or type 'exit' to quit): Chennai
```

* Output includes:

  * Current weather
  * 5-day forecast with date and time

* Type `exit` to stop the program

---
## Sample Output

```
Current Weather in Chennai:
Temperature: 32°C
Feels Like: 35°C
Humidity: 70%
Pressure: 1012 hPa
Weather: Clear sky
Wind Speed: 3.5 m/s

5-Day Weather Forecast for Chennai:
2026-04-09 12:00 | Temp: 33°C | Weather: Clear sky | Wind Speed: 3.2 m/s
...
```
## Notes

* Requires internet connection
* API has rate limits (free tier)
* Forecast data is in 3-hour intervals

## Future Improvements

* Add GUI (Tkinter or Web app)
* Add location auto-detection
* Convert to mobile app
* Save search history
* Add weather icons

## Contribution

Feel free to fork and improve this project.

---

## License

This project is open-source and free to use.
