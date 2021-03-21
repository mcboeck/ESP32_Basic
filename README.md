# ESP32_Basic
Basic Sketch to set WiFi, IP and Hostname through a captive portal for ESP32 based on the WiFiManager library.

With this Sketch it is possible to change the WiFi settings, IP-Address and Hostname settings through a webpage.

On the first boot it opens a AP with the name ESP_Config. Password 12345678

When connected a Captive Portal opens to change the settings.

The settings are stored on the EEPROM.

OTA can be done whith set IP /update for example: "http://172.20.10.1/update".
