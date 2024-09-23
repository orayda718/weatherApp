# Weather App

A simple web application that allows users to check the current weather conditions in any city around the world. The app uses the OpenWeather API to fetch real-time weather data.

## Features

- Search for weather by city name.
- Displays current temperature, humidity, wind speed, and weather conditions.
- Updates the weather icon based on the current conditions (cloudy, clear, rainy, etc.).
- Handles errors such as invalid city names.

## Technologies Used

- **HTML**: Structure of the web page.
- **CSS**: Styling of the web page for a modern and clean user interface.
- **JavaScript**: Handles the API requests and dynamic content updates.
- **OpenWeather API**: Fetches real-time weather data.

## Usage

1. Enter the name of a city in the search box.
2. Press the search button or hit "Enter" to fetch and display the weather details.
3. If the city name is invalid, an error message will be displayed.

## API

This application uses the [OpenWeather API](https://openweathermap.org/) to retrieve weather data.

- **API Endpoint**: `https://api.openweathermap.org/data/2.5/weather`
- **Parameters**:
  - `q`: City name.
  - `appid`: Your API key.
  - `units`: Metric (for temperature in Celsius).

## Live Demo

You can view the app live at: **[Live Weather App](https://orayda718.github.io/weatherApp/)**

## Installation

To run the project locally:

1. Clone the repository.
   ```bash
   git clone https://github.com/orayda718/weatherApp.git
2. Open index.html in your web browser.