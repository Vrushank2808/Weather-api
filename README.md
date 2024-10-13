Here is a more detailed README for your Weather API repository:

---

# Weather API 🌤️

This project is a simple weather application that allows users to search for real-time weather information using city names. It retrieves and displays weather details like temperature, humidity, wind speed, and weather conditions using an external weather API.

## Features

- Search for current weather by city name.
- Displays:
  - Temperature (in Celsius or Fahrenheit)
  - Weather condition (clear, cloudy, rainy, etc.)
  - Humidity
  - Wind speed
- User-friendly and responsive interface.

## Technologies Used

- **HTML5**: For creating the structure of the webpage.
- **CSS3**: For styling the web pages and making the interface responsive.
- **JavaScript**: For making API calls and dynamically displaying weather data.
- **OpenWeather API**: External API used for fetching real-time weather data.

## Installation and Setup

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Vrushank2808/Weather-api.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Weather-api
   ```
3. Open the `index.html` file in your browser to run the application.

## API Setup

You need to obtain an API key from [OpenWeather](https://openweathermap.org/api) to fetch the weather data. After registering and getting your API key, add it to the JavaScript code where the API call is made (usually in the script.js file).

Example:
```javascript
const apiKey = 'YOUR_API_KEY';
```

## How It Works

1. User inputs a city name.
2. The app sends a request to the OpenWeather API.
3. The API responds with weather data, which is displayed on the webpage.

## Screenshots

![image](https://github.com/user-attachments/assets/f4763ddf-4311-4e75-8076-93d4088a5697)
![image](https://github.com/user-attachments/assets/7ca5d7af-729e-47ff-890d-e676596d2ff8)
![image](https://github.com/user-attachments/assets/4fb4caf6-9c0d-422c-b90d-d13863ce3138)

## Future Enhancements

- Add hourly and weekly forecast features.
- Integrate map-based weather searching.
- Allow user to save favorite cities.

## License

This project is open-source and available under the MIT License.

---

Once you have a screenshot, you can save it in your repository and reference it in the `Screenshots` section.
