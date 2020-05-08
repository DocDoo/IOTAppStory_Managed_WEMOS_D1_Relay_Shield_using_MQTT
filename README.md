# IOTAppStory_Managed_WEMOS_D1_Relay_Shield_using_MQTT
 IOTAppStory.com managed Lolin WeMos D1 Mini sketch using MQTT to receive commands for activating or deactivating the Relay shield
 
This app listens for thee different MQTT commands and takes action based on these.

Command 1: "IAS_Config_Start" triggers the WeMos D1 Mini to immediately restart and enter IOTAppStory Configuration Mode
Command 2: "On" triggers the WeMos to close the relay shield
Command 3: "Off" triggers the WeMos D1 Mini to open the relay shield

I use this app to remotely start and stop a fan I have monted in my workshop which pulls hot air from an ajoining greenhouse. It is my Loxone smarthouse system which monitors the temperatures in the two rooms and manages when the fan is started and stopped.

I wanted to use MQTT to handle all communication between my IoT devices as I have extended the Loxone smarthouse system with the Loxberry solution and this solution allows me very elegantly to use MQTT with the smarthouse.
