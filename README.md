Movement Tracker Application

Overview

The Movement Tracker Application is a mobile app developed using Kotlin and Android Studio. It allows users to track their movements in real time, providing insights into their routes, distances traveled, and movement patterns. The app utilizes GPS and location services to log user activity and displays data visually on an interactive map.

Features

Real-Time Location Tracking: Monitor your movements on an interactive map.

Route History: View past routes taken, including timestamps.

Distance Calculation: Measure distances traveled during a session.

Movement Analytics: Get insights into your speed and travel patterns.

Offline Support: Save data locally when offline and sync when connected.

Technologies Used

Programming Language: Kotlin

Development Environment: Android Studio

Map Integration: Google Maps API

Location Services: Android Location Manager

Database: Room Database (for storing location history)

Setup Instructions

Prerequisites

Install Android Studio.

Install a Java Development Kit (JDK).

Enable developer options and USB debugging on your Android device.

Steps to Run the Project

Clone this repository:

git clone <repository_url>

Open the project in Android Studio.

Sync the project with Gradle files.

Obtain a Google Maps API Key:

Go to the Google Cloud Console.

Create a new project and enable the Maps SDK for Android.

Generate an API key and add it to the google_maps_api.xml file.

Build and run the application on an emulator or a physical Android device.

Usage

Open the app and grant location permissions.

Start a new tracking session by tapping the "Start Tracking" button.

View your movement in real-time on the map.

Stop the session to save your route and view the analytics.
