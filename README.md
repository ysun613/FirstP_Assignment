# Flutter Weather Check-In App

## Overview
This project is an application that allows users to check in with weather data integration. It's composed of a Flutter frontend (`main.dart`), a Dart script for fetching weather data (`demo.dart`), and a Python Flask backend (`app.py`). The application provides functionalities like retrieving current weather information and managing user check-ins with associated weather data.

## Structure
- `main.dart`: The main Flutter application file, setting up the user interface and application logic.
- `demo.dart`: A Dart script responsible for fetching and displaying weather data from an external API.
- `app.py`: A Python Flask server that handles backend operations, including database interactions and API endpoints for IP address retrieval and data storage.

## Prerequisites
- Flutter installed for frontend development.
- Dart SDK for running Dart scripts.
- Python with Flask for the backend server.
- SQLite for database management.

## Setup and Installation
1. **Flutter App Setup:**
   - Ensure Flutter is installed on your machine.
   - Navigate to the directory containing `main.dart`.
   - Run `flutter pub get` to install dependencies.

2. **Weather Data Script Setup:**
   - Requires Dart SDK.
   - Navigate to the directory containing `demo.dart`.
   - Run the script via Dart command line.

3. **Backend Server Setup:**
   - Ensure Python is installed with Flask.
   - Navigate to the directory containing `app.py`.
   - Install required Python packages: `pip install flask sqlite3`.
   - Initialize the database by running `app.py`.

## Running the Application
- **Frontend:**
  - Run `flutter run` in the directory of `main.dart`.
- **Backend:**
  - Start the Flask server by running `python app.py`.

## API Endpoints
- `/get_ip`: GET request to retrieve the client's IP address.
- `/save_punch`: POST request to save user check-in data.



