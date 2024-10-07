# App-Clima-Js

This App allows users to view the current weather conditions and forecast at their computer's location. Unlike the **App-Clima-React** project, this version is built entirely using **JavaScript** and **HTML**, without the need for user login.

## Features

- **Current Location Weather**: Automatically detects the user's location and provides real-time weather data.
- **Minimal Setup**: No need for logging in or creating accounts.
- **Live Server Integration**: Uses the **live-server** npm package for local development and quick deployment.
- **navigator.geolocation**: obtained coordinstes latitude and longitude.
- **Api weather condition**: https://api.openweathermap.org/data/2.5/weather?lat=${latitude}&lon=${longitude}&exclude=hourly,minutely,alerts&appid=${apiKey}&units=${unit}.

## Technologies Used

- **HTML**: Structuring the content of the application.
- **CSS**: Basic styling and responsive design.
- **JavaScript**: Core logic to fetch and display weather data.

### Prerequisites

Make sure you have **Node.js** installed on your machine. This app uses **live-server** for easy local deployment.

### Installation

1. Clone the repository:

   
bash
   git clone https://github.com/RodrigoM11/App-Clima-Js.git

### Operation 

Clone the repository, with the terminal in the project folder, execute live-server and it will start working
