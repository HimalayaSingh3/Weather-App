
# Weather App

A simple weather application built using **HTML**, **CSS**, and **JavaScript** that allows users to get current weather information for any city around the world. The app uses the OpenWeatherMap API to fetch real-time weather data.

## Features

- Search for current weather by city name
- Display temperature, weather condition, humidity, and wind speed
- Responsive design for different device sizes
- Dynamic background based on weather conditions (e.g., sunny, cloudy, rainy)

## Technologies Used

- **HTML**: For structuring the layout of the app
- **CSS**: For styling and making the app responsive
- **JavaScript**: For fetching weather data and updating the UI dynamically
- **OpenWeatherMap API**: For real-time weather data


## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/HimalayaSingh3/Weather-App.git
    ```
2. Navigate into the project directory:
    ```bash
    cd weather-app
    ```
3. Open the `index.html` file in your web browser:
    ```bash
    open index.html
    ```
   or simply double-click the `index.html` file.

## How to Use

1. Enter the name of the city in the search bar.
2. Click the **Search** button or press **Enter**.
3. The current weather information for the entered city will be displayed, including:
   - Temperature (in Celsius)
   - Weather condition (Clear, Cloudy, Rain, etc.)
   - Humidity percentage
   - Wind speed (in km/h or mph)
4. Background changes dynamically based on weather conditions.

## API Key Setup

To use this app, you'll need an API key from [OpenWeatherMap](https://openweathermap.org/api).

1. Sign up at OpenWeatherMap and generate an API key.
2. In the `script.js` file, replace the placeholder `YOUR_API_KEY_HERE` with your actual API key.

```javascript
const apiKey = 'YOUR_API_KEY_HERE';
Contributing
Feel free to fork the repository and submit a pull request if you have any suggestions or improvements!

License
This project is licensed under the MIT License. See the LICENSE file for more details.

