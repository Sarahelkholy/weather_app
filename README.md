# Weather App 🌤️

A Flutter weather application that shows real-time weather information based on your current location.

---

## ✨ Features

- Automatically detects your location

- Shows current temperature, humidity, and wind speed

- Weather description (sunny, rainy, cloudy, etc.)

- Clean and responsive UI
 
---


## 🖼️ Screenshots

| permission | home |
|------------|------|
|<img width="1080" height="2400" alt="Screenshot_1759311722" src="https://github.com/user-attachments/assets/65e40a9c-d804-4128-a8a7-5da878d42d66" />|<img width="1080" height="2400" alt="Screenshot_1759312100" src="https://github.com/user-attachments/assets/dd3c9d24-072c-4737-a51b-3335220e7605" />|



---

## Getting Started 🚀

# Prerequisites

- Flutter SDK >= 3.0.0

- Dart >= 3.0.0

- Android Studio or VS Code

# Installation

- Clone the repository:

git clone https://github.com/Sarahelkholy/weather_app.git


- Navigate into the project directory:

cd weather_app


- Install dependencies:

flutter pub get


- Run the app:

flutter run


# Make sure to allow location permission on your device/emulator for the app to work.

---

## 🛠️ Project structure

```

lib/
├── blocs/  
│   └── weather_bloc/             
│
├── data/
│   └── my_data.dart      
│
├── screens/   
│   └── home_screen.dart      
│
├── widgets/   
│   └── day_info.dart      
└── main.dart

```
## Dependencies 📦

- weather – for fetching weather data
  
- geolocator – for getting device location

- bloc – for state management

---

## API

- The app uses the weather package to fetch real-time weather data for your current location.

- You need a valid OpenWeatherMap API key to use it.

- Add your OpenWeatherMap API key in the data file.

---
