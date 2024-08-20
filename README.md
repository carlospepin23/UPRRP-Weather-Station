# UPRRP Weather Station

This repository contains the code and configuration files for the automated Weather Station project implemented during July to August 2021 as part of the UPRRP Upward Bound & T3 Alliance collaboration. The project was created at the University of Puerto Rico, Rio Piedras Campus, utilizing an AcuRite - Iris (5-in-1) Pro Weather Station, paired with a Raspberry Pi (RPi) board to broadcast real-time weather conditions. The code was implemented using Node-RED on a Raspberry Pi computer kit. **Note:** The project is no longer operational.

## Project Overview

As part of the activity, our team designed and deployed a weather monitoring system that autonomously collected and transmitted real-time data on local weather conditions. This information was shared with the campus community via X (Twitter) and was accessible through a ThingSpeak channel. The weather station was located on top of El Edificio Monserrate Rivera, Primer Piso, Ave. Universidad, Río Piedras.

## Key Features

- **Automated Weather Station**: Equipped with an AcuRite - Iris (5-in-1) Pro Weather Station and a Raspberry Pi to measure atmospheric pressure, temperature, humidity, wind speed, wind direction, and rainfall.
- **Real-Time Data Broadcast**: Weather data was continuously monitored and shared on the UPR STEAM X account, providing the campus with up-to-date weather information.
- **ThingSpeak Integration**: Data was logged and visualized on the ThingSpeak platform for further analysis and historical reference.
- **Node-RED**: The code and configurations were developed using Node-RED on a Raspberry Pi computer kit.

## Repository Structure

- **All Flows (JSON)**: Contains all the Node-RED configuration flows, providing an overview of the project's logic and operations.
- **Current Flow (JSON)**: The master configuration file managing the weather station's data collection and broadcasting processes.
- **Bmepressure (JSON)**: Focuses on the atmospheric pressure readings obtained from the BME sensor.
- **API Twitter**: Scripts and configurations used to connect the weather station to the X (Twitter) API.

## Setup and Installation

1. **Clone this repository**:
    ```bash
    git clone https://github.com/yourusername/UPRRP-Weather-Station.git
    cd UPRRP-Weather-Station
    ```

2. **Install Required Dependencies**:
    Ensure your Raspberry Pi is configured with Node-RED and other necessary libraries and tools. Refer to the `requirements.txt` (if applicable) or install the necessary packages using:
    ```bash
    sudo apt-get install python3-pip
    pip3 install -r requirements.txt
    ```

3. **Configure API Keys**:
    Update the API keys for X (Twitter) and ThingSpeak in the configuration files.

4. **Deploy the Weather Station**:
    Import the JSON files into Node-RED and start the weather station to begin collecting and broadcasting weather data.

## Accessing Weather Data

- **X (Twitter)**: Follow the weather updates on the UPR STEAM account [here](https://x.com/UBSTEAM).
- **ThingSpeak**: View the data logs and visualizations on the ThingSpeak channel [here](https://thingspeak.com/channels/1442446).

**Note:** The project is no longer operational.
