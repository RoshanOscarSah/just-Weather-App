# Mausam - Flutter Weather App

## Introduction

A **Flutter** weather app is designed to provide users with accurate information using their current location to display current weather data. It uses an API to display current weather data. This app is well-managed using **MVVM** architecture and **GETX**.

## Features

- Display current weather conditions including temperature, humidity, wind speed, and more from Weather API.
- Weather condition based app theme.
- Automatic user location detection for accurate weather information.
- Icons based on weather from API.
- User-friendly minimal interface.
- Error handling for API requests and network connectivity issues.
- Blur app for privacy while in background.

## Getting Started

Follow these steps to get the app up and running:

1. Clone the repository
2. Install dependencies: `flutter pub get`
3. Add OpenWeatherMap API KEY on lib/res/app_url/api_key.dart `const apiKey = '<YOUR API KEY>';`
4. Run the app: `flutter run`

## API Key

The app integrates with a weather API to fetch weather data. The API key should be placed in the `lib/res/app_url/api_key.dart` file. You can obtain an API key by signing up on the [OpenWeatherMap API](https://openweathermap.org/) website. Must use your own API key.

## Dependencies

- [GetX](https://pub.dev/packages/get) - State management and dependency injection.
- [Http](https://pub.dev/packages/http) - For making HTTP requests to the weather API.
- [Intl](https://pub.dev/packages/intl) - Internationalization and formatting of dates.
- [Geolocator](https://pub.dev/packages/geolocator) - Getting device location.
- [Geocoding](https://pub.dev/packages/geocoding) - Getting latitude and longitude from address.
  t
