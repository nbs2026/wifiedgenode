# Task 8: Dual Transport Telemetry

## Objective

Send the same sensor payload (Temperature, Humidity, and Soil Moisture) using both HTTPS Telemetry and MQTT Publish.

## Hardware

* ESP32
* DHT22 Sensor
* Soil Moisture Sensor

## Methodology

1. Connect ESP32 to Wi-Fi.
2. Read sensor values.
3. Create a JSON payload.
4. Send the payload via HTTPS.
5. Publish the same payload via MQTT.
6. Handle HTTP errors.
7. Verify data in the IoT Lab dashboard.

## Results

* Sensor data sent successfully via HTTPS.
* Sensor data published successfully via MQTT.
* Data verified in MQTT logs and telemetry history.
