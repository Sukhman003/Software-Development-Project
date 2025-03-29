# WeatherApp-Android
# Overview: #
This project is an Android weather application developed in Java using Android Studio. It utilizes the OpenWeatherAPI to retrieve weather data and provides users with real-time weather information for a given location. The app allows users to search for specific cities and displays the current weather conditions along with the forecast for the upcoming days.

# Features: #

- [x] Current Weather Display: The app displays the current weather conditions, including temperature, humidity, wind speed, and weather description (e.g., sunny, cloudy, rainy).
- [ ] 
- [x] Forecast Display: Users can view the weather forecast for the upcoming days, including temperature and weather conditions.
- [x] Search Functionality: Users can search for specific cities to get weather information for those locations.

- [x] Location-based Weather: The app can also retrieve weather data based on the user's current location using the device's GPS or network.
Unit Selection: Users can choose between different units of measurement, such as Celsius or Fahrenheit, for displaying temperature.
- [x] Error Handling: The app handles errors gracefully, displaying appropriate messages when there are network issues or invalid search queries.
Technologies and APIs Used:

- [x] Java: The primary programming language used for Android app development.
- [x] Android Studio: The integrated development environment (IDE) for building Android applications.
- [x] OpenWeatherAPI: An API that provides access to weather data, including current weather and forecasts, for various locations worldwide.
- [x] Google Play Services: Used to access the device's GPS or network for location-based weather data.
- [x] Retrofit: A type-safe HTTP client for Android used to make API requests and handle responses.
- [x] JSON: The weather data retrieved from the OpenWeatherAPI is in JSON format, and parsing techniques are used to extract relevant information.
Setup and Installation:

# Installation #
- [x] Clone the repository or download the project source code
      
<p> Open Android Studio and select "Open an existing Android Studio project."
Navigate to the project directory and select the project.
Gradle will build the project automatically. If any dependencies are missing, install them using the Android Studio prompt.
Obtain an API key from the OpenWeatherAPI website by signing up for a free account.
Replace the placeholder API key in the project code with your generated API key.
Connect an Android device or start an emulator to run the application.
Build and run the app from Android Studio, and it will be installed on the device/emulator.
</p>

# Usage: # 

Upon launching the app, users will be greeted with a search bar to enter the desired city.
Users can enter the city name and tap on the search button to retrieve weather information.
The current weather conditions for the specified city will be displayed, including temperature, humidity, wind speed, and weather description.
Users can scroll down to view the weather forecast for the upcoming days.
To switch between temperature units, users can access the settings or preferences menu within the app.
Users can also allow the app to access their current location for location-based weather information by granting the necessary permissions.
The app will handle errors gracefully and display appropriate messages if there are network issues or invalid search queries.

Contributing
Contributions are welcome! If you find any bugs or want to add new features, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.
