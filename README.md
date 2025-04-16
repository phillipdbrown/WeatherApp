# Weather App

A simple weather application built with **Flutter** using the **OpenWeather API** to display real-time weather information based on the user's location.

## Features
- Displays current weather information including city name, temperature, weather description, and icon.
- Fetches the user's location using the `geolocator` package.
- Handles location permissions gracefully with the `permission_handler` package.
- Simple and clean UI with loading state and error handling.

## Screenshots
### Main Screen
![Weather App Main Screen](img/phone.png)
![Weather App Main Screen](img/web.png)

### Structure File
![Structure File](img/structure.png)
## Prerequisites
- **Flutter SDK**: Ensure you have Flutter installed. [Install Flutter](https://flutter.dev/docs/get-started/install)
- **OpenWeather API Key**: Sign up at [OpenWeatherMap](https://openweathermap.org/) to get your API key.
- **Android/iOS Emulator or Physical Device**: For testing the app.

## Installation
1. **Clone the repository**:
   ```bash
   git clone <your-repository-url>
   cd weather_app