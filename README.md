# Movement Tracker Application

## Overview

The Movement Tracker Application is a mobile app developed using Kotlin and Android Studio. It allows users to track their movements in real time, providing insights into their routes, distances traveled, and movement patterns. The app utilizes GPS and location services to log user activity and displays data visually on an interactive map.

## Features

- **Real-Time Location Tracking**: Monitor your movements on an interactive map
- **Route History**: View past routes taken, including timestamps
- **Distance Calculation**: Measure distances traveled during a session
- **Movement Analytics**: Get insights into your speed and travel patterns
- **Offline Support**: Save data locally when offline and sync when connected

## Technologies Used

- **Programming Language**: Kotlin
- **Development Environment**: Android Studio
- **Map Integration**: Google Maps API
- **Location Services**: Android Location Manager
- **Database**: Room Database (for storing location history)

## Setup Instructions

### Prerequisites

1. Install Android Studio
2. Install a Java Development Kit (JDK)
3. Enable developer options and USB debugging on your Android device

### Steps to Run the Project

1. Clone this repository:
2. Open the project in Android Studio
3. Sync the project with Gradle files
4. Obtain a Google Maps API Key:
   - Go to the Google Cloud Console
   - Create a new project and enable the Maps SDK for Android
   - Generate an API key and add it to the `google_maps_api.xml` file
5. Build and run the application on an emulator or a physical Android device

## Usage

1. Open the app and grant location permissions
2. Start a new tracking session by tapping the "Start Tracking" button
3. View your movement in real-time on the map
4. Stop the session to save your route and view the analytics

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
