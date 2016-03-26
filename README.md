# Real-Time Slack Bot for Arduino

Copyright (C) 2016, Uri Shaked

License: MIT.

This bot let you control the colors of a NeoPixel Ring through Slack. It uses the Slack Real Time Messaging API to listen for slack messages.
Read more about it in my blog post.

Before running this Sketch, make sure the set the following constants in the program:

* `SLACK_BOT_TOKEN` - The API token of your slack bot
* `WIFI_SSID` - Your WiFi signal name (SSID)
* `WIFI_PASSWORD` - Your WiFi password

In addition, you will need to install the following Arduino libraries: [ADAFruit_NeoPixel](https://github.com/adafruit/Adafruit_NeoPixel), [WebSockets](https://github.com/Links2004/arduinoWebSockets), [ArduinoJson](https://github.com/bblanchon/ArduinoJson).
