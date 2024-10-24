# Weather Real-Time Data Processing System - Weatherry

## Objective:
This project implements a **weather monitoring system** with **real-time data processing** using rollups and aggregates to generate daily weather summaries, alerting thresholds, and visualizations of weather data trends and alerts.

## Features:
- **Daily Weather Summary:** Roll up daily weather data and calculate aggregates such as average, maximum, and minimum temperature, along with the dominant weather condition.
- **Alerting Thresholds:** Define user-configurable temperature or weather condition thresholds (e.g., alert if temperature exceeds 35°C for two consecutive updates) and trigger alerts.
- **Visualizations:** Display daily summaries, historical trends, and alerts.

## Test Cases:
- **System Setup:** Ensure successful startup and connection to the OpenWeatherMap API.
- **Data Retrieval:** Test weather data retrieval and parsing at configurable intervals.
- **Temperature Conversion:** Verify conversion of temperature values from Kelvin to Celsius or Fahrenheit.
- **Daily Summary:** Ensure correct daily summary calculations.
- **Alerting Thresholds:** Verify proper triggering of alerts when thresholds are breached.

## Bonus:
- Add more weather parameters (e.g., humidity, wind speed).
- Integrate weather forecasts and summaries for predicted conditions.

## Running the Project:
### Tools Required:
- **VS Code**
- **Node.js**
- **MongoDB Compass** (optional for better data visualization of Data)

### Setup Instructions
1. Clone the project or download the ZIP file and extract it.
   ```bash
   git clone <repository-url>
2. Run the following command to install necessary packages:
   ```bash
   npm install mongoose express dotenv ejs
3. Start the project:
   ```bash
   node index.js
4. Open your browser and go to:
   ```bash
   http://localhost:3000

Boom! Your weather monitoring project is up and running. Enjoy monitoring weather data with real-time updates, alerts, and visualizations! give this also in that format



