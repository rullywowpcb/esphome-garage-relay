# esphome-garage-relay


ESPhome code for Garage Door Relay using ESP8266

If my code has helped you, consider buying me a beverage:
https://www.buymeacoffee.com/rullywow

I wanted to share my ESPhome code for controlling my 2-car garage. Originally, I deployed a Wemos D1 mini and a 2-channel relay using Arduino code and MQTT in order to control my garage doors via Home Assistant. I wanted to migrate my setup to ESPhome to take advantage of some great features such as OTA updates.

This project uses the following hardware:

- Wemos D1 Mini (or Pro) or just about any ESP8266 PCB
- 2ch Optocoupled Relay (SainSmart or similar)
- Reed switches to know when the door is open or closed. I recommend heavy-duty weatherproof metal ones used for gates
- Assorted wiring (alarm wire works well along with Dolphin-style crimp connectors)

I also used a small project enclosure, 5V microUSB (to power the D1 and Relay Board) and some 3D printed mounts which were glued into the enclosure
