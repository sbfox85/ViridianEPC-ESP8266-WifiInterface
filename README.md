# ViridianEPC-ESP8266-WifiInterface

Current Status : PLANNING
Objectives:
- Control charge rate of Viridian EPC depending on user selection.
- Provide kWh values using a SDM120 meter.
- Allow MQTT Control, thus making it possible to vary charge rate over wifi dependng upon available power. In my case this will be based on an off grid Solar setup, and diesel generator for emergencies (see other projects).

In my project it will be housed along with all EVSE components in a polycarbonate IP rated enclosure for portable use. I plan to use RFID to select charge current settings, with the unit defaulting to 10amp upon power up. This is because I could be plugged in to a UK 13amp plug (which suports 10amp continuous safely). Selection of a higher current will be by means of using the RFID card to cycle through menu options. This doubles up as anti -tamper, and maintains IP rating. Ideally some sort of cable detection would be good, but for my own use manual selection is fine.

Hardware Components:
- Mainpine EPC
- DAC, to provide analogue voltage signal to EPC
- PSU to power ESP8266/Wemos
- SDM120 Meter - to provide power and kWh data.
- ESP8266, in my case a Wemos D1 Mini.
- LCD Display
