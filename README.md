This project connects to the broker mqtt://industrial.api.ubidots.com:1883.

It uses ESP-MQTT library which implements mqtt client to connect to mqtt broker.

## How to use

### Hardware Required

This project can be executed on any ESP32 board, the only required interface is WiFi and connection to internet.

### Configure the project

* Open the project configuration menu (`idf.py menuconfig`)
* Configure Wi-Fi consist SSID and PASSWORD

Navigate to the main directory

```
cd main
```

### Build and Flash

Build the project and flash it to the board, then run monitor tool to view serial output:

```
idf.py -p PORT flash monitor
```

(To exit the serial monitor, type ``Ctrl-]``.)

See the Getting Started Guide for full steps to configure and use ESP-IDF to build projects.

