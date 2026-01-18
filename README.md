## Java Weather API Client

A lightweight Java application that retrieves real-time weather data for a user-specified city by chaining two public APIs:

1. A **Geocoding API** to resolve latitude and longitude  
2. A **Weather API** to fetch current conditions using those coordinates  

This project demonstrates REST API consumption, JSON parsing, and clean modular design in Java.

---

## Features

- Accepts a city name as user input
- Resolves latitude and longitude via a geocoding API
- Fetches live weather data using coordinates
- Parses and displays JSON responses
- Handles invalid input and API errors gracefully
- Modular and extensible design

---

## How It Works

1. User enters a city name  
2. Geocoding API returns latitude and longitude  
3. Coordinates are passed into the Weather API  
4. Weather data is returned as JSON  
5. The application parses and displays relevant information  

