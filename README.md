# Bus Tracking System
Simple and Modular plan for creating College Bus Tracking System project for our college. [Under-Development]

<img src = https://github.com/user-attachments/assets/2150d1aa-a0b5-4d71-81d3-57fd2a524df6 width="300" height="200">

# Development Steps
Hardware Components : Arduino Uno, SIM808 module, GPS module

Connections:

1. Connect SIM808 to Arduino for GSM/GPRS communication.

2. Connect GPS module to Arduino to retrieve location data.

3. Power the setup with a 5V battery pack or USB.

Arduino Code (bus_tracker.ino):

1. Retrieves location coordinates using GPS.

2. Sends location and bus number to the backend server via SIM808.

# Tech Stack
Frontend (HTML, CSS, JS) Features:

1. Simple form to input route or bus number.

2. Displays buses nearby with Google Maps.

Backend (Node.js and Express) Features:

1. API to receive location updates from buses.

2. API to fetch nearby buses based on user input.

3. Stores bus data in MySQL.

Database (MySQL)
# Deployment

1. Using Heroku or Render for backend deployment.
2. Using GitHub Pages for the frontend.
3. Setting the Arduino device to communicate with the deployed backend server.

# Testing

1. Simulate location data from Arduino.

2. Testing the frontend by entering coordinates near your campus.
