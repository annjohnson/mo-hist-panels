# mo-hist-panels
A repository for the interactive voting booth installation for the Missouri History Museum.

# Hardware
Alitove 150led/m ws2812 addressable leds
  38 pixels per strip, 8 strips per panel
  2 panels per booth
  3 booths

Raspberry Pi B+
  Install Mosquitto
  Install Node-RED

Falcon PiCap
  1 PiCap per booth

5v 60A Power Suppy
  1 per booth

# Software
Control xLights playlists using MQTT triggers, triggered by input from user apps.
App and all software will be created using Node-RED.

# xLights
TODO: Create playlists for each animation.
