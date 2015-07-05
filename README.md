It used MQTT.js to monitor topic thru websocket

![screenshot](https://github.com/blue119/mqtt-monitor/blob/master/screenshot.png)

## Configuration

You can use the demo server of mosquitoo.org, if you'd like to setup one own server.

- modify config.json
    - set server to test.mosquitto.org/mqtt
    - set port to 8080

- Feching the config.json with XHR, Therefor You have to run HTTP server on the top of directory.
    - with `python -m SimpleHTTPServer`

## 3rd Party Plugins
- browserMqtt.js is converted from [MQTT.js](http://github.com/mqttjs/MQTT.js/).js with browserfy.
- angular-1.4.1.js
- jquery-1.6.2.js

## TODO
- Add topic on the fly
- colorize each topic
- send message

