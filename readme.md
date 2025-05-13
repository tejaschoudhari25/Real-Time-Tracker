# Real-Time Location Tracking

![Real-Time Location Tracking](https://private-user-images.githubusercontent.com/143324250/443169008-16dc46c4-8935-4fa2-9203-739257a10fa4.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcxMzM4NzksIm5iZiI6MTc0NzEzMzU3OSwicGF0aCI6Ii8xNDMzMjQyNTAvNDQzMTY5MDA4LTE2ZGM0NmM0LTg5MzUtNGZhMi05MjAzLTczOTI1N2ExMGZhNC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTEzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxM1QxMDUyNTlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zYzU5MjQwYWViZmJmMWIwNjI4M2RiNzFjZWM1NjFhMTQwOTAwMmFkMjlhZGRiN2FhYmRlNjRkYzFlNTdmMjIzJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.5WXOPcU14pfX1NCcoasUaEZ2_7dFOubwfixuDSIC0ZA)

## Overview

Welcome to the **Real-Time Tracking** project! This web application is designed for real-time location tracking and monitoring. It utilizes WebSocket technology to provide real-time updates, displaying the location of tracked entities on a map. All connected users can view everyone's location on the map in real-time.

## Features

- **Real-time Location Updates**: Uses WebSocket technology for instant location updates.
- **Interactive Map**: Displays locations on an interactive map using OpenStreetMap and Leaflet.js.
- **Multi-user Support**: Multiple connected users can view locations simultaneously.

## Technologies Used

- **JavaScript**: The programming language used for both client-side and server-side logic.
- **Node.js**: JavaScript runtime built on Chrome's V8 JavaScript engine.
- **Express.js**: A fast, unopinionated, minimalist web framework for Node.js.
- **Socket.IO**: Enables real-time, bidirectional communication between the server and clients.
- **OpenStreetMap**: Provides the map data.
- **Leaflet.js**: An open-source JavaScript library for mobile-friendly interactive maps.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/realtime-location-tracker.git
   ```
2. Navigate to the project directory:
   ```bash
   cd realtime_location_tracker
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

## Usage

1. Start the server:
   ```bash
   node app.js
   ```
2. Open your web browser and go to `http://localhost:3000` to view the application.
