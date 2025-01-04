# ClimaSense

ClimaSense is a modern Android weather forecast application that provides accurate and intuitive climate information. Utilizing the OpenWeatherMap API, the app delivers up-to-date meteorological data and detailed forecasts.

## Features

- Current and future weather forecasts
- Search by current location and city
- Weather alert notifications
- Home screen widget
- Offline support
- Intuitive and responsive user interface

## Technologies Used

- Kotlin
- Android Jetpack (ViewModel, LiveData, Room)
- Retrofit for REST API calls
- Coroutines for asynchronous programming
- MVVM (Model-View-ViewModel) Architecture
- OpenWeatherMap API
- GitHub Actions for CI/CD

## Project Setup

### Prerequisites

- Android Studio Arctic Fox or higher
- JDK 11
- OpenWeatherMap account to obtain an API key

### Setup Steps

1. Clone the repository: https://github.com/Mrprey/ClimaSense

2. Open the project in Android Studio.

3. Create an `apikey.properties` file in the project root and add your API key: `OPEN_WEATHER_MAP_API_KEY="your_api_key_here"`

4. Sync the project with Gradle files.

5. Run the app on an emulator or physical device.

## Usage

After installation, the app will request permission to access the device's location. Grant the permission to get weather forecasts for your current location.

To search for the weather in a specific city, use the search bar at the top of the main screen.

## Contributing

Contributions are welcome! Please read the CONTRIBUTING.md file for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Contact

Anderson Silva - prey.anderson2@gmail.com

## Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for providing weather data
- [Android Jetpack](https://developer.android.com/jetpack) for making Android development easier
- All contributors who participated in this project
