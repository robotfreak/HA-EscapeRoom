# HA-EscapeRoom
Home Assistant Escape Room. Building an Escape room with Home Assistant, ESPHome, MQTT with a Raspberry Pi 4 and some ESP32 boards. Inspired by 
https://gist.github.com/MarkBaggett/ae50c11b6eaf00c3b86ad639730d37f1

## Hardware needed
* Rasperry Pi 4 or 5, Power Supply and SD-Card (32GB or higher)
* some ESP32 boards
* BAsic Electronics Parts (Buttons, LEDs, Sensors, Actors )
 
## Software needed
* Home Assistant OS for Raspberry Pi
* ESPHome Add-On
* Mosquitto Add-On
* AppDaemon Add-On
* Hass.io Access Point Add-On (optional)
* Terminal & SSH Add-On (recommended)

## Installation

### Home Assistant installation
Install Home Assistant 12 via Raspi Imager on the SD Card. See https://www.home-assistant.io/installation/raspberrypi/ for Installation. Do not use the Home Assistant Docker Image, because we need the App Store to install some Addons 

### Addon installations
Install the ESPHome, Mosquitto broker, Terminal & SSH and the AppDaemon add-ons from the Add-on Store. Open Setup, Add-Ons. Click on Add-On Store. Search for the Add-Ons and install them.
For the optional Hass.io Access Point Add-On you will need to add https://github.com/mattlongman/Hassio-Access-Point as 3rd Party Add-On Repository. See https://www.home-assistant.io/hassio/installing_third_party_addons/

## Configuration
