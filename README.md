# RestAPIClient

Company:CODTECH IT SOLUTIONS

Name: Padmasri V.G

Intern Id: CT04DH1472

Domain:Java development

Duration: 4 weeks

Mentor: NEELA SANTOSH

DESCRIPTION:

This project is a Java-based REST API client that fetches real-time weather data for any user-specified city using public APIs. It demonstrates how to make HTTP requests, parse JSON responses, and display structured weather data in the console. The application is developed using IntelliJ IDEA, one of the most popular Java development environments, and utilizes the JSON.simple library for lightweight JSON parsing.

Tools & Technologies Used:
Programming Language: Java (Java SE 8 or higher)

Editor/IDE: IntelliJ IDEA (Community Edition)

Libraries: org.json.simple for JSON parsing

APIs Used:

Open-Meteo Geocoding API: To get latitude and longitude from a city name.

Open-Meteo Weather Forecast API: To fetch real-time weather information based on geographic coordinates.

 Key Features:

Accepts city name as user input.

Fetches location coordinates using the Open-Meteo Geocoding API.

Uses coordinates to query the Open-Meteo Weather API.

Displays structured weather data:

Current time

Temperature (°C)

Relative humidity (%)

Wind speed (m/s)

Gracefully handles API errors and invalid city input.

Modular design using separate methods for fetching data, reading API response, and displaying results.

 How It Works:

The user is prompted to enter a city name.

The program sends a GET request to the Open-Meteo Geocoding API to retrieve that city’s geographic coordinates.

These coordinates are then used to send another GET request to the Open-Meteo Weather Forecast API.

The weather data received in JSON format is parsed using the JSON.simple library.

The parsed data is neatly displayed to the user in the console.

The program continues running until the user types "No" to exit.

 Where It Can Be Applied:

This project can be applied in various learning and practical scenarios:

Educational Use: It serves as an excellent beginner-level project for learning REST API integration, JSON parsing, and network programming in Java.

Weather Dashboard Backend: Can be used as the backend logic for a simple weather app or a desktop weather widget.

IoT Integration: This logic can be embedded in smart devices that rely on weather conditions (e.g., automated irrigation systems).

Interview Practice: Demonstrates practical skills in working with APIs and parsing data, which are often asked in developer interviews.

 Extensibility:

This project can be extended to include:

GUI using Java Swing or JavaFX

Saving data to a text or CSV file

Displaying forecast for multiple days

Integrating additional APIs like OpenWeatherMap or WeatherAPI

 Conclusion:
 
This Weather API Client project showcases the ability to consume public REST APIs, parse real-time data, and present it in a user-friendly format using Java. Built with IntelliJ IDEA and open-source libraries, it is a robust foundation for more complex weather-related applications or as a stepping stone into real-world API development.

OUTPUT:

![Image](https://github.com/user-attachments/assets/22f0c13a-e840-4175-871b-b07551c38883)
