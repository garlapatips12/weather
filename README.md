# Weather Forecasting Web App 🌦️

A responsive weather forecasting web application built using
HTML, CSS, and Vanilla JavaScript.

The application uses the SheCodes Weather API to fetch real-time
weather information for cities around the world and displays the
current weather along with a 5-day forecast.

## Features

- Search weather by city name
- Display current temperature
- Display weather condition and description
- Display humidity
- Display wind speed
- Display weather icons
- Display a 5-day weather forecast
- Responsive and user-friendly interface
- Real-time weather data using an external API

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Axios
- SheCodes Weather API

## How It Works

1. The user enters a city name in the search box.
2. JavaScript gets the city name from the input field.
3. Axios sends a GET request to the SheCodes Weather API.
4. The API returns the weather information.
5. JavaScript extracts the required data from the API response.
6. The webpage is dynamically updated with the current weather.
7. A second API request is made to retrieve the forecast.
8. The 5-day forecast is displayed on the webpage.

## Weather Information Displayed

The application displays:

- City name
- Current temperature
- Weather condition
- Humidity
- Wind speed
- Weather icon
- Maximum and minimum temperatures
- 5-day forecast

## API Integration

The application uses the SheCodes Weather API to retrieve weather
data.

Axios is used to make HTTP GET requests to the API.

Example API request:

```text
https://api.shecodes.io/weather/v1/current

## Project Structure
weather/
│
├── README.md
├── index.html
├── index.js
└── styles.css
