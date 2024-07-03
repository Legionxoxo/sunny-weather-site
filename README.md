

**Weather App**

This is a simple weather app that allows users to search for the current weather conditions of a city. The app uses the OpenWeatherMap API to fetch the weather data and displays it in a user-friendly format.

**Features**

* Search for the current weather conditions of a city
* Displays the city name, temperature, humidity, wind speed, and weather icon
* Supports multiple weather conditions (e.g. Clouds, Clear, Rain, Drizzle, Mist)
* Uses the OpenWeatherMap API to fetch weather data

**Technical Details**

* The app uses HTML, CSS, and JavaScript to create the user interface and logic.
* The app uses the Fetch API to make requests to the OpenWeatherMap API.
* The app uses the JSON format to parse the weather data returned by the API.

**Code Structure**

* The code is organized into a single JavaScript file.
* The `checkWeather` function is responsible for fetching the weather data and updating the UI.
* The `searchBtn` event listener is responsible for triggering the `checkWeather` function when the search button is clicked.

**Known Issues**

* None known.

**Future Development**

* Add more features to the app, such as:
	+ Support for multiple units (e.g. Fahrenheit, Celsius)
	+ Display of weather forecasts for the next few days
	+ Integration with other weather APIs
* Improve the app's user interface and user experience.

**API Key**

* The app uses an API key from OpenWeatherMap to fetch weather data. The API key is stored in the `apiKey` variable.

**API URL**

* The app uses the following API URL to fetch weather data: `https://api.openweathermap.org/data/2.5/weather?units=metric&q=<city>&appid=<apiKey>`.

I hope this README file helps! Let me know if you have any questions or need further clarification.
