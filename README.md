🌦️ PyQt5 Weather App

A simple and clean desktop weather application built using Python, PyQt5, and the OpenWeatherMap API.
The app allows users to enter a city name and instantly see the current temperature, weather emoji, and description.

⸻

✨ Features
	•	🌍 Search weather by city name
	•	🌡️ Displays temperature in Celsius
	•	😄 Shows weather emoji based on conditions
	•	📝 Displays weather description (e.g. clear sky, light rain)
	•	🚨 Handles common API and network errors gracefully
	•	🎨 Clean and modern UI using Qt Stylesheets

⸻

🖼️ Preview

(Optional: Add a screenshot here)

Enter city name
[ London ]
[ Get Weather ]

12°C
☀️
clear sky


⸻

🛠️ Technologies Used
	•	Python 3
	•	PyQt5 (GUI)
	•	Requests (HTTP requests)
	•	OpenWeatherMap API

⸻

📦 Installation

1️⃣ Clone the repository

git clone https://github.com/your-username/weather-app-pyqt5.git
cd weather-app-pyqt5

2️⃣ Install dependencies

pip install PyQt5 requests

3️⃣ Get an API Key
	1.	Go to 👉 https://openweathermap.org/api
	2.	Create a free account
	3.	Copy your API key
	4.	Replace this line in the code:

api_key = "YOUR_API_KEY_HERE"


⸻

▶️ Run the App

python weather_app.py


⸻

🚨 Error Handling

The app handles:
	•	Invalid city names
	•	Invalid API key
	•	Network issues
	•	Server errors (400, 401, 404, 500, etc.)

Clear messages are shown directly in the UI.

⸻

📁 Project Structure

weather-app/
│
├── weather_app.py
├── README.md


⸻

🌈 Weather Emoji Logic

Condition	Emoji
Thunderstorm	⛈️
Drizzle	🌦️
Rain	🌧️
Snow	❄️
Fog/Mist	🌁
Clear	☀️
Clouds	🌥️


⸻

🔒 Security Note

⚠️ Do not commit your real API key
Use environment variables or a config file for production projects.

⸻

🚀 Future Improvements
	•	🔄 Unit toggle (°C / °F)
	•	📍 Auto-detect location
	•	📊 5-day forecast
	•	🎨 Dark mode
	•	📱 Mobile version (PyQt / Kivy)

⸻

🙌 Acknowledgements
	•	OpenWeatherMap API
	•	PyQt5 Documentation

⸻

📜 License

This project is open-source and free to use for learning purposes.

⸻
