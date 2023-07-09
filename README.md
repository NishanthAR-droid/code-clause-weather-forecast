# Weather Forecasting Application

This is a weather forecasting application built with React JS and Tailwind CSS, utilizing the OpenWeatherMap API. The application provides users with hourly and daily forecasts, along with various weather data such as temperature, maximum and minimum temperature, humidity, real feel, sunrise, sunset, and local time at the selected location.

## Technologies Used

- JavaScript
- React JS
- Tailwind CSS
- luxon
- unicons
- react-toastify

## Key Features

- Fetch weather data from OpenWeatherMap API
- Display temperature, max and min temperature, humidity, real feel, sunrise, sunset, hourly forecasts, and daily forecasts
- Show local time at the selected location
- Quick links for popular locations
- City search using a text box
- Current location-based search

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/NishanthAR-droid/code-clause-weather-forecast
   ```

2. Navigate to the project directory:
   ```
   cd weather-forecasting-app
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Obtain an API key from [OpenWeatherMap](https://openweathermap.org/) by creating an account.

5. Create a `.env` file in the project root directory and add your API key:
   ```
   REACT_APP_API_KEY=your-api-key
   ```

6. Start the application:
   ```
   npm start
   ```

7. Open your browser and navigate to `http://localhost:3000` to see the application running.

## Usage

- Select a location from the quick links at the top or enter a city name in the search box to fetch weather forecasts.
- The application will display the temperature, max and min temperature, humidity, real feel, sunrise, sunset, hourly forecasts, and daily forecasts for the selected location.
- The local time at the selected location will also be shown.

## Contributing

Contributions to this project are welcome. Feel free to open issues and submit pull requests to contribute to the application's development.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather data API.
- [React JS](https://reactjs.org/) for the JavaScript library used in building the application's user interface.
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework.
- [luxon](https://moment.github.io/luxon/) for the JavaScript library used for handling dates and times.
- [unicons](https://iconscout.com/unicons) for the collection of open-source vector icons.
- [react-toastify](https://github.com/fkhadra/react-toastify) for the React notification library used for displaying notifications in the application.
