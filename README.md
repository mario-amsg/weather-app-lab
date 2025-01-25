# Weather App

Weather Application for Costa Rica using an API that displays temperature and rain probability.

-------------------------

# Getting Started

## Prerequisites

    - Make sure to have [Homebrew](https://brew.sh) configured as you will need to run `brew` commands to install software.

Follow these steps to setup the **Weather App Project** on your local machine:

1. Locate an appropriate location to clone the repository on your local machine and run the following commands:
    ```bash
    git clone https://github.com/mario-amsg/weather-app-lab.git
    cd weather-app-local
    ```

2. This application uses **Node.js** and **Node Packet Manager (npm)**, thus you will need to install them and verify their installation by running the following commands:
    ```bash
    brew install node
    node --version
    npm --version
    ```

3. Next setup your API key using by:

    1) Sign up for a free API key from [OpenWeather API](https://openweathermap.org/api)
    2) Create a `.env` file in the root of the project and add:
        ``bash
        REACT_APP_WEATHER_API_KEY=your_api_key_here
        ```

4. Finally start the application by running the following command:
    ```bash
    npm start
    ```
    > Note: This application will run locally at: http://localhost:3000/

-------------------------

# Usage Examples

    - Search for a City: Enter city name (e.g., "Santo Domingo") into the search bar.
    - Error Handling: If a city is not found or the request fails, the application will display an error message.

-------------------------

# Features

    - Real-time weather data.
    - Displays temperature, chance of rain and weather conditions.
    - User-friendly interface
    - Eror handling for invalid queries of failed requests.

-------------------------

# Contributing

Contributions are always welcome.

To contribute perform the following steps:

1. **Fork** the repository.
2. Create a new branch such as feature or fix. You can use the following git command:
    ```bash
    git checkout -b feature/feature-name
    ```
3. Make your changes and commit them using:
    ```bash
    git commit -m "Your commit message"
    ```
    > Note: Please provide a clear, short and concise commit message of your change.

4. Push your branch with:
    ```bash
    git push origin feature/feature-name
    ```
5. Finally open a pull request to the `main` branch.

-------------------------

# License

This project is licensed under the MIT License. See the License file for more details.
