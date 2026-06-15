# esp32-stuff
Here's a collection of random ESP32/ESP8266/ESPHome stuff

The two files inverter.yaml and single-pow-hvm62k-48v-lip.yaml connect to my 4 PowMR inverters (with two ESP32s).  You can use the single.yaml file by itself if you have only one, but if you have more than one, the inverter.yaml file includes multiple copies via packages, and if you have more than you have UARTs, multiple ESP32s will talk to each other via UDP and present "unified" values (prefixed with star).

Note that I misunderstood how names and IDs work, so all of the ID parameters can be removed.
