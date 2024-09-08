# Weather App

A Python-based weather application that allows users to check current weather information for any city using the OpenWeatherMap API. The app provides temperature in Celsius & Fahrenheit, weather description, and an emoji representation of the weather condition.

## Features
- Fetches current weather for any city.
- Displays temperature in Celsius & Fahrenheit.
- Shows appropriate weather description and emoji.
- User-friendly graphical interface built using PyQt5.

## Technologies Used
- **Python**: The primary programming language.
- **PyQt5**: Used for building the graphical user interface (GUI).
- **Requests**: Library used for making HTTP requests to the OpenWeatherMap API.
- **OpenWeatherMap API**: Provides real-time weather data.

## Prerequisites
- Python 3.x installed on your machine.
- Install the required Python libraries:
  ```bash
  pip install -r requirements.txt
  ``` 
## Installation

### Clone the repository:
  ```bash
  git clone https://github.com/denex-a-poulose/weather-app.git
  ```

### Navigate to the project directory:
  ```bash
  cd weather-app
  ```
### Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```


### Set up your OpenWeatherMap API key:

- Go to OpenWeatherMap API and sign up to get your API key.
- Store your API key in an .env file in the root of the project

 ```bash
WEATHER_API_KEY=your_api_key_here
  ```

## Usage

### Run the application:

```bash
   python weather_app.py
```

- Enter the city name in the input field, and press the Get Weather button to retrieve the weather details.

## Contributing
- If you'd like to contribute to the project, feel free to open a pull request or submit an issue.
