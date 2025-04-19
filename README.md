# WeatherApp-Flask

This is a simple Python-based weather application built with Flask. The app allows users to get current weather information for any city using the [OpenWeatherMap API](https://openweathermap.org/).

---

## Features
- **City-Based Weather Search**: Enter a city name to get real-time weather information.
- **Default City**: If no city is entered, Miami's weather is shown as the default.
- **Detailed Weather Info**:
  - City Name
  - Weather Description
  - Temperature
  - Feels Like Temperature
- **Error Handling**: Displays a user-friendly error page if the city is not found.

---

## Tech Stack
- **Python**: Core programming language.
- **Flask**: Backend web framework for handling HTTP requests and rendering templates.
- **Waitress**: Production-grade WSGI server for deployment.
- **HTML Templates**: Used for rendering the user interface.

---

## Setup and Installation

### Prerequisites
- Python 3.7+
- A valid API key from [OpenWeatherMap](https://openweathermap.org/api)
- `pip` (Python package installer)

### Installation Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/94mohabd/WeatherApp-Flask.git
   cd WeatherApp-Flask

