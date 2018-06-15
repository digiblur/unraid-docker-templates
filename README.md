# digiblur's unRaid-Docker-Templates

Template files for various Docker Containers for use with Lime Technology, Inc. unRaid Server

The docker containers referenced in this repo point to Docker Containers maintained by other individuals.  These templates were created to make it easy for the average unRaid user to quickly install the containers without researching the various container variables and requirements.

## UNMS - Ubiquiti Network Management System 
![alt text](https://raw.githubusercontent.com/digiblur/unraid-docker-templates/master/images/unms_icon.png?raw=true "HA-Dockermon")

https://unms.com/
  - Docker container maintained at - https://github.com/oznu/docker-unms

## Speedtest - Self hosted HTML5 Speedtest site 
![alt text](https://raw.githubusercontent.com/digiblur/unraid-docker-templates/master/images/speedtest_icon.png?raw=true "Speedtest")

  - Docker container maintained at - https://github.com/adolfintel/speedtest/tree/docker

No Flash, No Java, No Websocket, No BS. This is a very lightweight Speedtest implemented in Javascript, using XMLHttpRequest and Web Workers. Great for troubleshooting bandwidth, ping and jitter issues through a reverse proxy with unRaid.

## TasmoAdmin  
![alt text](https://raw.githubusercontent.com/digiblur/unraid-docker-templates/master/images/tasmoadmin_icon.png?raw=true "HA-Dockermon")

TasmoAdmin (previously SonWEB) is an administrative Website for Home Automation Devices flashed with [Sonoff-Tasmota](https://github.com/arendst/Sonoff-Tasmota). 
Video Tutorial: https://www.youtube.com/watch?v=vJUhRyi3-BQ

  - Docker container maintained at - https://github.com/reloxx13/TasmoAdmin

## HA-Dockermon - HomeAssistant Docker Container Monitor
![alt text](https://raw.githubusercontent.com/digiblur/unraid-docker-templates/master/images/ha-dockermon_icon.png?raw=true "HA-Dockermon")

A simple Node service which checks the status of a Docker Container and returns a RESTful response. It can also be used to issue start, stop, and restart commands. The primary purpose of this service is to interface with Home Assistant. Build automations/notifications for all of your docker containers and much more!

  - Docker container maintained at - https://github.com/philhawthorne/ha-dockermon
  - Custom HomeAssistant component to automatically add all the container "switches" to HA - https://github.com/HalfDecent/HA-Custom_components/tree/master/hadockermon

