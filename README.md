# Weather Forecast API Integration Instructions

## 1. Controller Setup:
   - Add the Weather API to your controller named "WeatherController."
   - **Use the free API from [OpenWeatherMap](https://openweathermap.org/appid)**
   - Use the following code:
     ```csharp
     private readonly string apiKey = "Insert API Key Here";
     ```

## 2. API Request:
   - Insert your API key and a city name into this URL to get weather information in JSON format:
     ```
     https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}
     ```

## 3. JSON Formatting:
   - For better readability, paste the JSON response into a JSON viewer like [CodeBeautify](https://codebeautify.org/jsonviewer).

## 4. Integration:
   - Incorporate the code into your C# project.

## Changing Preset Cities:
   - To change preset cities, find the OpenWeatherMap API city code for the desired city.
   - Replace the existing city names with the corresponding OpenWeatherMap API city codes in your code.

Note: Replace "Insert API Key Here" with your actual OpenWeatherMap API key.

Enjoy using the Weather Forecast API in your project!
