# Node-RED Weather Forecast Project

This is a Node-RED project that utilizes three different APIs to provide weather-related information to users. The project retrieves data from the OpenWeather API for current weather information, the RestCountries API to fetch details about the country of the city searched, and the Weather Forecast API (Tomorrow.io) for a 5-day weather forecast. The project offers data about the city's current temperature, humidity, minimum and maximum temperatures, 5-day weather forecast, and information about the country, including its capital, population, area, and Google Maps website. The application is user-friendly and responsive, ensuring a seamless experience for users across different devices 📱.

## Features

### Current Weather Information
- Display of the current temperature in the searched city.
- Information on humidity levels.
- Minimum and maximum temperatures for the day.
- Feels like temperature.

### 5-Day Weather Forecast
- A 5-day weather forecast for the searched city, allowing users to plan ahead.
- Sunrise and sunset time for each day.

### Country Information
- Display of country details, such as capital, population, and area.
- Integration with Google Maps for geographical context.

## Usage

1. Enter the name of the city you want to search for in the provided input field.
2. Click the search button.
3. The application will fetch and display the current weather data, 5-day weather forecast, and information about the corresponding country.

## API Integration

- **OpenWeather API**: Used to fetch current weather data.
- **RestCountries API**: Used to obtain information about the country associated with the city.
- **Weather Forecast API (Tomorrow.io)**: Used to retrieve a 5-day weather forecast.

## Testing

Postman was used to test the APIs integrated into this project to ensure reliable data retrieval and processing.

## Adaptation

The project's frontend display was initially sourced from Bootsnip but was subsequently customized and adapted to accommodate the specific features and functionality of this application.


## Desktop Display:
![image](https://github.com/laraberns/node-red-weather-app/assets/133805423/6a42fb4e-7adc-459b-b365-c8cf8d9ea741)

## Mobile Display :
![ezgif-3-08a62e6f9f_50](https://github.com/laraberns/node-red-weather-app/assets/133805423/9d220812-9ee3-43da-a2e6-f8e2489490e6)

## Flow on Node-RED:
![image](https://github.com/laraberns/node-red-weather-app/assets/133805423/f0b50cba-1e5f-494e-9767-edceed327b98)




