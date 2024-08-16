# IMU-equipped Pen for Handwriting Recognition

## Overview

This project involves building an IMU-equipped pen designed to recognize handwritten numerals. The pen utilizes accelerometer and gyroscope sensors to capture multidimensional movement data. The goal is to classify these movements into one of several numeral classes (0 to 9) to recognize the handwritten digit.

## Features

- **Handwriting Recognition**: Classifies handwritten numerals based on sensor data.
- **Sensor Data Collection**: Captures accelerometer and gyroscope data.
- **Data Processing**: Converts sensor data into a format suitable for analysis.

## Components

- **IMU-equipped Pen**: Contains accelerometer and gyroscope sensors.
- **ESP32 Microcontroller**: Processes sensor data.
- **Arduino IDE**: Used for writing and uploading the code to the ESP32.
- **Visual Studio Code (VS Code)**: Utilized with the Terminal Capture extension for data collection.

## Data Collection

1. **Code for Capturing Data**:
   The code for capturing accelerometer and gyroscope data is written in Arduino. The ESP32 is programmed to read data from the IMU sensors and print it out at a 10ms sampling interval (100Hz sampling rate).

2. **Terminal Capture**:
   To streamline the data collection process, the Terminal Capture extension for VS Code was used. This extension allows capturing and saving sensor data from the VS Code terminal into a `.txt` file.

3. **Data Conversion**:
   The `.txt` file with raw data was processed and converted into CSV format. This transformation made the data more manageable and ready for analysis.
