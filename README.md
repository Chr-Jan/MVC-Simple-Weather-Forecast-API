Weather Forecast API Integration Instructions

1. Controller Setup:
   - Add the Weather API to your controller named "WeatherController."
   - Use the following code:
     ```
     private readonly string apiKey = "Insert API Key Here";
     ```

2. API Request:
   - Insert your API key and a city name into this URL to get weather information in JSON format:
     ```
     https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}
     ```

3. JSON Formatting:
   - For better readability, paste the JSON response into a JSON viewer like [CodeBeautify](https://codebeautify.org/jsonviewer).

4. Integration:
   - Incorporate the code into your C# project.

Note: Replace "Insert API Key Here" with your actual OpenWeatherMap API key.

Enjoy using the Weather Forecast API in your project!
