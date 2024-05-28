# Circadian Weather App Dashboard

**An intuitive app that adjusts your lighting to match your circadian rhythm based on real-time weather and time of day.**

## Technologies Used

- Python
- Streamlit
- Azure IoT Hub
- Requests
- TimezoneFinder
- Pytz
- PIL (Pillow)
- `python-dotenv`

## Problem Statement

This project aims to enhance well-being by synchronizing indoor lighting with natural circadian rhythms. By adjusting LED colors based on the current time and weather conditions, it helps maintain a healthy sleep-wake cycle and improves productivity and mood.

## How to Run

### Prerequisites

- Python 3.6 or higher
- Streamlit
- Requests
- TimezoneFinder
- Pytz
- PIL (Pillow)
- Azure IoT Hub SDK for Python

### Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/circadian-weather-app.git
    cd circadian-weather-app
    ```

2. Install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```

3. Set your Azure IoT Hub connection string and device ID as environment variables:
    ```sh
    export IOT_HUB_CONNECTION_STRING="HostName=iotdevice-esp32.azure-devices.net;SharedAccessKeyName=iothubowner;SharedAccessKey=R0mDqvmO/fU+pxKGyZDw4KSH7z3kibnHjAIoTGqyAew="
    export DEVICE_ID="Esp32-Wroom"
    ```

4. Add your custom logo image to the `img` directory.

### Running the Application

Run the Streamlit application:
```sh
streamlit run app.py

**# Reflections

## What You Learned

- Integrating Azure IoT Hub with Python applications.
- Using Streamlit for rapid web application development.
- Implementing geolocation and weather data APIs.
- Enhancing user experience through dynamic and responsive UI design.

## Questions/Problems Faced

- **Connection Issues**: Establishing a reliable connection to the IoT Hub and ensuring consistent message delivery to the ESP32 device.
- **API Rate Limits**: Handling API rate limits and errors gracefully while fetching geolocation and weather data.
- **Time Zone Handling**: Accurately determining and displaying local times for various locations.

## Links

- **Web App**: [Circadian Weather App](https://yourappurl.com)
- **Demo Video**: [Youtube Demo](https://youtube.com/yourdemovideo)
**
