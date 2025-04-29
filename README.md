# WEATHER-FORCASTING
This code represents the structure and functionality of a Weather App built using HTML, CSS, and JavaScript. Below is a breakdown of the key parts and their purposes:

1. HTML Structure:
Document Setup: It starts with a basic HTML5 structure, including a <head> section for metadata like the title, character set, and viewport settings for responsiveness.

Video Background: The background is animated using a <video> element that plays a video in the background (background.mp4, rain.mp4, sunny.mp4, or cloudy.mp4), based on the weather condition.

Main Content:

Search Box: There is an input field (<input>) for entering a location (city) and a search button to fetch the weather for the entered city.

Weather Information Section: Displays temperature, weather description, humidity, wind speed, and "feels like" temperature.

Sunrise and Sunset: Displays the times for sunrise and sunset.

Forecast Section: A 5-day weather forecast is displayed with daily temperature and weather icons.

2. CSS Styles:
Global Styles: Basic reset of margin and padding, and setting the font for the entire document using * selector. It also ensures a dark-themed background (#111) with white text (#fff).

Background Video: The video has a position: absolute style, so it covers the entire viewport, ensuring it doesn't interfere with the content.

Container Styling: The main container has a transparent background with some blur (backdrop-filter: blur(10px)) and rounded corners.

Weather Box: The weather details (temperature, description, and icon) are centrally aligned and styled to stand out.

Forecast Cards: These are laid out horizontally and include weather data for the next few days.

3. JavaScript Functionality:
API Calls to OpenWeatherMap:

Weather Data: When the user enters a city and clicks the search button, the app makes an API call to OpenWeatherMap to get the current weather for that city.

Forecast Data: It also makes a secondary API call to get the 5-day forecast for the city.

Dynamic Updates: The weather information (temperature, humidity, wind speed, sunrise/sunset, etc.) is dynamically updated in the HTML based on the response from the API.

Background Update: The background video is updated based on the current weather condition. It switches between different videos (rain.mp4, sunny.mp4, or cloudy.mp4), depending on whether the weather is rainy, clear, or cloudy.

Error Handling: If the user enters an invalid city or the API fails to return data, an alert is shown with the message "City not found!"

4. External Resources:
Boxicons: A library is included for icons (<link rel="stylesheet" href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css">), which is used to display weather-related icons like a wind icon, thermometer, sun, and moon.

OpenWeatherMap API: This app makes use of OpenWeatherMap's public API to fetch weather and forecast data. An API key (5bc06f50ea4133a580ffe081f9969b09) is used to authenticate requests.

5. Key Features:
Real-time Weather Info: Shows live weather data like temperature, humidity, wind speed, and description of the weather condition.

Dynamic Forecast: Displays a 5-day weather forecast with icons representing weather conditions and the corresponding temperatures for each day.

Background Video: The background changes based on the weather (rain, clear sky, or cloudy) to give users a more immersive experience.

Responsive Design: The app is designed to work on different screen sizes and is centered and styled to look good on mobile devices.

Key Technologies:
HTML5: For structure and layout.

CSS3: For styling and animations (background video, responsive design, etc.).

JavaScript: For interactivity, making API calls, and dynamically updating the content.

OpenWeatherMap API: To fetch weather and forecast data based on the user's city input.

Conclusion:
This code is a simple but effective weather application that combines weather data, dynamic background changes, and a modern, clean interface to provide real-time weather information and a 5-day forecast for any city input by the user. It uses web technologies like HTML, CSS, JavaScript, and an external API to create a functional and visually appealing weather app.










Author : Shadab Rathore
