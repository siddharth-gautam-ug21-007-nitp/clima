# Clima - Weather App 🌦️

Clima is a simple and intuitive weather app built with Flutter that provides real-time weather information for any location around the globe.

![Clima App Screenshot](screenshots/clima_screenshot.png)

## Features

- **Current Weather:** Get the current weather conditions for any city.
- **Location-based:** Automatically detects your location for instant weather updates.
- **Search Functionality:** Search for weather information by city name.

## Technologies Used

- Flutter: A UI toolkit for building natively compiled applications for mobile, web, and desktop from a single codebase.
- OpenWeatherMap API: Used for fetching real-time weather data.

## Getting Started

To run the Clima app on your local machine, follow these steps:

1. Clone the repository:
   git clone https://github.com/your-username/clima-app.git
2. Navigate to the project directory:
   cd clima-app
3. Install dependencies:
   flutter pub get
4. Run the app:
   flutter run

## Configuration
To use the Clima app, you'll need to obtain an API key from OpenWeatherMap. Once you have the API key, add it to the api_key.dart file in the lib directory:

// lib/api_key.dart

const String openWeatherMapApiKey = 'YOUR_API_KEY_HERE';


## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to enhance the app.

