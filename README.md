# ESP NodeNet
A DYI home ESP wireless network consisting of a Broker (ESP32) connecting multiple Client ESP devices throughout my home consisting of ESP32s, ESP8266s, ESP-01s and Sonoffs as well as some older PK-Link switches. The broker also connects to Alexa enabling 101-voice commands for broker and network nodes. The broker also provides a web-monitor for debugging, monitoring and controling any network device. Client have their own internet/LAN connection [HTTP] and use a single socket server to communicate within the natwork itself enabling node to node communications.
