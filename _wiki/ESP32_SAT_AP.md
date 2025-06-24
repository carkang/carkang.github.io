---
layout: wiki
title: ESP32 Access Point (AP) and STATION
cate1: about ESP32 ap and sta mode
cate2:
description: ESP32 AP STATION
keywords: ESP32, Webserver,SAT,AP,WIFI
type:
link:
mermaid: false
sequence: false
flow: false
mathjax: false
mindmap: false
mindmap2: false

---

Content here

The ESP32 can act as a Wi-Fi station, as an access point, or both. In this tutorial we’ll show you how to set the ESP32 as an access point using Arduino IDE.


In most projects with the ESP32, we connect the ESP32 to a wireless router (see our ESP32 web server tutorial). This way we can access the ESP32 through the local network.

In this situation the router acts as an access point and the ESP32 is set as a station. In this scenario, you need to be connected to your router (local network) to control the ESP32.


But if you set the ESP32 as an access point (hotspot), you can be connected to the ESP32 using any device with Wi-Fi capabilities without the need to connect to your router.

In simple words, when you set the ESP32 as an access point you create its own Wi-Fi network and nearby Wi-Fi devices (stations) can connect to it (like your smartphone or your computer).



