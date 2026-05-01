# DroneFlyWeather

DroneFlyWeather is an Android weather app built for drone pilots who need quick, practical flight guidance before takeoff. It combines forecast data, hourly and daily outlooks, flight condition labels, and location-based weather details in a clean Jetpack Compose interface.

## Features

- Current weather summary for the selected location
- Flight condition labels such as Great, Good, Caution, and No Fly
- Hourly forecast strip for the next 24 hours
- 7-day weather outlook
- Wind, gust, humidity, UV, cloud cover, visibility, sunrise, and sunset details
- City search and saved cities
- GPS location support
- Drone model selection for more tailored flight insight
- Clean modern UI built with Jetpack Compose

## Why this app exists

Drone pilots often need more than a normal weather app. DroneFlyWeather focuses on the conditions that matter most before a flight, especially wind, gusts, rain chance, visibility, and overall flying safety.

## Tech stack

- Kotlin
- Jetpack Compose
- Material 3
- Android ViewModel
- StateFlow
- Accompanist Permissions
- Weather and forecast data integration

## Project structure

```text
app/
├── src/main/java/com/vinyldown/dronefly/
│   ├── data/
│   ├── ui/
│   └── viewmodel/
├── src/main/res/
└── build.gradle.kts
```

## Getting started

### Requirements

- Android Studio
- Android SDK
- Kotlin support enabled
- Internet connection for weather data

### Run locally

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/DroneFlyWeather.git
```

2. Open the project in Android Studio.
3. Let Gradle sync.
4. Run the app on an emulator or Android device.

## Rename notes

The app display name can be changed through `app_name` in `strings.xml`, while the project name and package name are managed separately through Gradle and project settings.

## GitHub

To push the project to GitHub:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/DroneFlyWeather.git
git push -u origin main
```

## Open-source license

This project can use the MIT License for a simple permissive open-source setup, or GNU GPL if all distributed modifications should remain open source.

## Roadmap

- Better flight scoring logic
- Weather map improvements
- Notifications for good flight windows
- More drone profiles
- Better location favorites management
- Play Store release polishing

## Contributing

Contributions, improvements, and bug fixes are welcome. Open an issue first for major changes so the direction can be discussed before implementation.

## Disclaimer

DroneFlyWeather is a planning tool and should not replace pilot judgment, local regulations, manufacturer limits, or official aviation guidance. Always verify conditions before flying.
