# Days 1–2 · Task 1 Report

## Project

**WiFi Edge Nodes (Intermediate) – Zelbytes Agritech**

## Objective

Configure the ESP8266 development environment, verify firmware upload capability, establish a Git-based project repository, and prepare the board for future edge telemetry applications.

## Hardware Details

| Parameter               | Value                             |
| ----------------------- | --------------------------------- |
| Board                   | NodeMCU ESP8266 (ESP-12E/ESP-12F) |
| USB Interface           | CH340 USB-to-Serial Converter     |
| Wireless Connectivity   | Built-in Wi-Fi                    |
| Development Environment | Arduino IDE                       |

## Software Configuration

* Installed Arduino IDE.
* Installed ESP8266 Board Support Package.
* Verified CH340 USB driver functionality.
* Configured board settings for firmware upload.

## Board Verification

### Blink Test

A Blink sketch was uploaded successfully to verify:

* USB communication
* Bootloader functionality
* Firmware upload capability

**Result:** Successful

### Wi-Fi Scan Test

A Wi-Fi scanning sketch was executed to detect nearby wireless networks and verify wireless subsystem operation.

**Result:** Successful

## Flash Configuration

| Parameter           | Value                        |
| ------------------- | ---------------------------- |
| Flash Size          | 4MB (FS:2MB OTA:~1019KB)     |
| Upload Speed        | 115200 baud                  |
| Board Configuration | NodeMCU 1.0 (ESP-12E Module) |

## Repository Structure

wifiedgenode/
│
├── README.md
├── firmware/
│   ├── blink.ino
│   └── wifi_scan.ino
│
└── docs/
└── day1_task1.md

## Outcomes

* ESP8266 development environment configured successfully.
* USB driver installation verified.
* Firmware upload process validated.
* Wi-Fi functionality tested and confirmed.
* GitHub repository established following firmware project organization practices.

## Conclusion

The ESP8266 NodeMCU board was successfully configured and validated for edge-node development. The development workflow, repository structure, and firmware upload process are now ready for subsequent tasks involving sensor integration, cloud connectivity, and telemetry applications.
