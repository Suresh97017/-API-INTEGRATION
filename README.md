# -API-INTEGRATION

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : DAKAMARRI SURESH

*INTERN ID* : CT04DF2473

*DOMAIN* : FULL STACK WEB DEVELOPMENT

*DURATION*  :  4 WEEKS

*MENTOR*  :  NEELA SANTOSH

DESCRIPTION :

This project is a basic web application that fetches and displays current weather information for any city entered by the user. It uses HTML, CSS, and JavaScript and connects to a public weather API — OpenWeatherMap. The project is simple but demonstrates key concepts of web development, API integration, and real-time data fetching.

Purpose of the Project :

The purpose of this project is to allow users to input the name of any city in the world and get up-to-date weather information. It is useful for learning how websites interact with external data sources like APIs. It also shows how to handle user input, make HTTP requests, and update the web page dynamically based on the API response.

 Technologies Used : 
 
This project is built using the following technologies:

HTML (HyperText Markup Language): Used to create the structure of the webpage. It includes elements like text input, buttons, and containers to display the weather data.

CSS (Cascading Style Sheets): Used to style the webpage, making it visually appealing. It styles the background, buttons, input box, and the weather display section.

JavaScript: The core functionality is written in JavaScript. It captures the user input (city name), sends a request to the OpenWeatherMap API, and displays the response on the page.

OpenWeatherMap API: This is a public API that provides weather data such as temperature, humidity, wind speed, and weather conditions (e.g., "Clear", "Rain", "Cloudy").

 How It Works :
 
User Input: The user types the name of a city (e.g., “London”) into the input box and clicks the "Get Weather" button.

API Request: When the button is clicked, JavaScript runs a function that constructs a request URL using the city name and an API key. This request is sent to the OpenWeatherMap API using the fetch() method.

Getting Data: If the city exists and the API responds successfully, it returns weather information in JSON format. The JavaScript code extracts important data like:

City name and country

Temperature in Celsius

Weather condition and description

Humidity and wind speed

Display on Webpage: The data is then displayed inside a styled div element on the page. If the city is not found, an error message is shown.

Responsive Experience: Users can try different cities, and the page updates dynamically without refreshing.

NOTE:

API Key Requirement :

To make the project work, you need to register at OpenWeatherMap and get a free API key. This key is like a password that allows you to use the API. 


OUTPUT :

WEATHER-API
