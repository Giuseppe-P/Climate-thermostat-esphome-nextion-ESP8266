# Climate-thermostat-esphome-nextion ESP8266
# ESPHOME - HOME ASSISTANT - Thermostat Nextion Nextion-3.2 inch

I do not assume responsibility for incorrect use or lack of competence.

Touch screen thermostat for inserts and pellet fireplaces.
Separate logic with heating switching on and modulation management based on the setpoint temperature via two relays, one of which is activated and deactivated on total switching on and off, and the second is activated and deactivated based on the set temperature, allowing thermo-fireplace modulation.

![](https://github.com/Giuseppe-P/Climate-thermostat-esphome-nextion/blob/main/HA_ESPHOME_TERMOSTATO_NEXTION_ONLINE.png)

For use with a single contact for standard boilers just ignore the connection to the second relay

ESPHOME Documentation:
https://esphome.io/index.html

Home Care Assistant Documentation:
https://www.home-assistant.io/

Nextion documentation:
https://nextion.tech/

Necessary hardware:

1 - Raspberry Pi 3 or higher for home assistant installation

2 - ESP8266-12 chips

3 - NEXTION 3.2 inch touch screen panel

4 - Relay 5v system ignition (I used a transistor circuit, but you can use a ready-made board)

5 - Relay 5v modulation management (I used a transistor circuit, but you can use a ready-made board)

6 - ds18b20 (temperature sensor)

Software:

1 - download and copy the home assistant image to the SD card for raspberryPi

2 - add ESPHOME add on to your Home Assistant

3 - upload firmware to yaml on ESP8266 via Home Assistant add-on

4 - upload the .HMI file to the next touch panel

5 - copy the contents of configuration.yaml and paste it into configuration.yaml in Home Assistant

6 - In addition to sending Alexa Telegram notifications and HA push notifications, the automation file also contains daily and weekly timer management via home assistant helpers to be created as in the image

![](https://github.com/Giuseppe-P/Climate-thermostat-esphome-nextion/blob/main/helpers.jpg)

Good making
