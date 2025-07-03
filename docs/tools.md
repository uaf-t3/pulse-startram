---
layout: default
title: Tools
permalink: /tools/
---
<nav>
  <a href="{{ '/' | relative_url }}">Home</a> |
  <a href="{{ '/about/' | relative_url }}">About</a> |
  <a href="{{ '/contact/' | relative_url }}">Contact</a> |
  <a href="{{ '/downloads/' | relative_url }}">Downloads</a> |
  <a href="{{ '/docs/' | relative_url }}">Docs</a> |
  <a href="{{ '/pulse/' | relative_url }}">PULSE</a> |
  <a href="{{ '/startram/' | relative_url }}">STARTRAM</a> |
  <a href="{{ '/tools/' | relative_url }}">Tools</a> |
</nav>

# Tools We Used

## PULSEtastic (Github)
PULSEtastic is an open-source software toolkit created as part of the PULSE project to help process and transmit environmental sensor data over long-range Meshtastic LoRa radio networks. It simplifies the messy output typically received through serial connections by cleaning and formatting incoming messages, making it easier to use the data in tools like NodeRED. Designed for accessibility, it's especially useful in education settings where students are working hands-on with real-time sensor systems. You can find it [here](https://github.com/uaf-t3/PULSEtastic).


## Meshtastic Flasher
The Meshtastic Flasher is a user-friendly tool designed to easily install or update Meshtastic firmware on LoRa-based devices (like ESP32 or nRF52 boards) using your web browser.

Key Features:
- Web-based flashing: No setup required—just plug in your device and point Chrome or Edge to the official flasher at [flasher.meshtastic.org](flasher.meshtastic.org)

- Cross-platform support: Works on Windows, macOS, Linux, and different hardware types

## RPi Image
This is the Raspberry Pi operating system we used, me made some adjustments from the stock image that T3 uses. You can find a link to download it in the [downloads](https://t3.uaf.edu/pulse-startram/downloads/) page.

## [modpoll](https://github.com/gavinying/modpoll)
We used modpoll as a simple and reliable way to query Modbus sensors over serial and forward that data to MQTT. It let us quickly pull readings from devices and integrate them into our system without needing to write a bunch of custom code. One big advantage was being able to create device templates, which makes it easier for other students or researchers using the same Modbus gear to get started fast.

## [rtl433_to_mqtt](https://github.com/dayne/rtl433_to_mqtt)
This tool did for RTL433 sensors what modpoll did for Modbus, it gave us a stable way to forward wireless sensor data to MQTT. We originally tried using a NodeRED node for RTL433, but it was inconsistent. This tool was more reliable, easier to control, and fit better into our existing pipeline. It worked great for decoding Acurite sensors and made it easy to get that data into our system for logging and transmission.
