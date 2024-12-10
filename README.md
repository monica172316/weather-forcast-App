# weather-forcast-App
# Provincial Weather Update Website

## Project Overview

This is a dynamic, user-friendly web application that provides real-time weather information for various cities within a province. The website allows users to search for weather details by city name and displays comprehensive weather information with intuitive visual representations.

## Features

- **Real-time Weather Data**: Fetch current weather information using a third-party API
- **City Search**: Easy-to-use search functionality for finding weather conditions
- **Responsive Design**: Mobile-friendly and works across different devices
- **Dynamic Visual Indicators**:
  - Weather icons represent current conditions
  - Background color changes based on weather type
- **Detailed Weather Information**:
  - Temperature
  - Humidity
  - Wind Speed
  - Weather Conditions

## Technologies Used

- **Frontend**: 
  - HTML5
  - CSS3
  - JavaScript (ES6+)
- **API Integration**: Fetch API for weather data retrieval
- **Icon Library**: Font Awesome for weather icons

## Prerequisites

Before you begin, ensure you have met the following requirements:

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection
- API key from a weather service provider

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/monica172316/weather-forcast-App.git
   ```

2. Navigate to the project directory:
   ```bash
   cd provincial-weather-website
   ```

3. Open the `index.html` file in your web browser, or use a local development server

## Configuration

1. Open `script.js`
2. Replace the following placeholders:
   ```javascript
   const API_KEY = 'your_api_key_here'; // Replace with your actual API key
   const API_BASE_URL = 'https://api.example.com/weather'; // Replace with the actual API base URL
   ```

## Usage

1. Enter the name of a city in the search input
2. Click the "Search" button
3. View the current weather details and visual representation

## API Integration

This project uses a third-party weather API. You'll need to:
- Sign up for an API key from a weather service provider
- Ensure the API response matches the expected data structure in `script.js`

## Customization

- Modify `styles.css` to change the appearance
- Update `script.js` to add more weather details or change icon mapping
- Adjust the background color classes in CSS for different weather conditions

## Troubleshooting

- **No Weather Data**: Verify your API key and internet connection
- **Incorrect Data**: Check API documentation and ensure correct data parsing
- **Performance Issues**: Implement error handling and loading states

## Recommended API Providers

- OpenWeatherMap
- WeatherAPI
- AccuWeather
- Visual Crossing Weather API

## Security Considerations

- Never expose your API key in client-side code for production
- Use backend proxy or environment variables in a production environment
- Implement rate limiting and error handling

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the ICU License. See `LICENSE` for more information.

## Contact

Monica Phiri -monicaphiri90@gmail.com

Project Link: [https://github.com/monica172316/weather-forcast-App](https://github.com/monica172316/weather-forcast-App)
