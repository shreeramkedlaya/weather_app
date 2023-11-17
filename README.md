# Flutter Weather App with Flutter Bloc

![Flutter](https://img.shields.io/badge/Flutter-3.16.0-blue.svg)
![Dart](https://img.shields.io/badge/Dart-2.18.0-green.svg)
![Bloc](https://img.shields.io/badge/Bloc-8.1.3-purple.svg)

A simple weather app developed using Flutter and Flutter Bloc to demonstrate state management and API integration.

## Features

- Display current weather conditions.
- Retrieve weather forecasts for the next few days.
- Search for weather information by city.
- Responsive design for various screen sizes.


## Getting Started

These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Flutter installed on your machine. [Install Flutter](https://flutter.dev/docs/get-started/install)
- Emulator or physical device for testing.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/flutter-weather-app.git
2. Navigate to the project directory:
    ```bash
    cd weather-app
3. Get the dependencies:

    flutter pub get
4. Run the app:
    
    ```bash
    flutter run
5. Dependencies
    - flutter_bloc - State management library.
    - http - HTTP client for making API requests.
    - equatable - Simplifies equality comparisons.
    - intl - Internationalization and localization.
6. API Key
This app uses the OpenWeatherMap API to fetch weather data. You need to obtain an API key by signing up on OpenWeatherMap and replace the placeholder in lib/data/weather_repository.dart with your actual API key.

```
lib\data\my_data.dart

const String apiKey = 'YOUR_API_KEY';
```
