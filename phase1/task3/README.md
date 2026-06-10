# Phase 1 - Task 3: DHT22 Sensor with Error Handling and JSON Output

## Objective

Read temperature and humidity data from a DHT22 sensor using ESP32 with robust error handling and JSON serial output.

## Hardware Used

* ESP32 Development Board
* DHT22 Temperature and Humidity Sensor
* Jumper Wires
* USB Cable

## Features Implemented

* Temperature and humidity measurement using DHT22
* Retry mechanism for failed sensor readings (`NaN` handling)
* JSON formatted serial output
* Status flag (`ok`) indicating successful sensor read
* Deep Sleep implementation (Bonus)

## JSON Output Format

```json
{"temp":29.1,"humidity":67.3,"ok":true}
```

## Files Included

### Main Implementation

* `Task3_DHT22_JSON.ino`

### Deep Sleep Version

* `Task3_DHT22_DeepSleep.ino`

### Output Log

* `serial_log_output`

### Screenshot

* `screenshot_deep_sleep`

## Working

1. ESP32 initializes the DHT22 sensor.
2. Sensor values are read periodically.
3. If a reading fails, the system retries up to three times.
4. Data is published in JSON format through the Serial Monitor.
5. In the Deep Sleep version, the ESP32 wakes up, reads the sensor, prints the JSON data, and returns to sleep.

## Result

Successfully implemented DHT22 sensor interfacing with ESP32, robust error handling, JSON serial output, and deep sleep functionality.
