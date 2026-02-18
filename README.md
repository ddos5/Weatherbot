> Weatherbot

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)

**Weatherbot** is a lightweight and efficient Telegram bot designed to provide real-time weather updates. This project was developed to simplify checking meteorological data directly within the messenger interface, eliminating the need for third-party weather apps.

The bot utilizes external APIs to fetch accurate data and presents it in a user-friendly format.

## Functionality

* **Real-time Weather Data:** The bot connects to a weather API to retrieve the current temperature, humidity, wind speed, and weather conditions for any requested location.

* **City Search:** Users can request weather information by simply sending the name of the city. The bot processes the input and queries the backend for the specific location.

* **Configuration Management:** The project uses a dedicated `config.py` file to securely handle API keys and tokens, separating sensitive data from the main logic.

* **Telegram Integration:** Built specifically for the Telegram platform (`main_weather_tg_bot.py`), ensuring fast response times and mobile-friendly output.

## HOW TO USE

* **Clone the repository**
  ```bash
  git clone https://github.com/ddos5/Weatherbot.git
* **Go to the project directory**
  ```bash
  cd Weatherbot
* **Install dependencies**
  ```bash
  pip install pytelegrambotapi requests
* **Configure the bot**
  Open `config.py` and insert your Telegram Bot Token and OpenWeatherMap API Key.
* **Run the bot**
  ```bash
  python main_weather_tg_bot.py
  
