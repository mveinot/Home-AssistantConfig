# Home-AssistantConfig

This configuration supports reading instantaneous power use in amps from an Efergy Elite recieved via an RTL-SDR and passed in to HA via rtl-433 over MQTT
This value is multiplied by 120V and collected as Watts

An integration is performed on this value and the kWh is determined

From here, daily, weekly and monthly utility meters are defined.


This also receives ISP speed test results from speedtest-cli performed on another system and tranismitted via MQTT in JSON form and extracts the upload, download, ping, and jitter values and logs them
