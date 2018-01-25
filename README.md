# Introduction

## This file is a fork of klein0r's project

You can see the original README down below. Nothing has changed on the code so far (late January 2018).

This fork is meant to be further developed by the "Smarthome Freunde" community (https://t.me/SmarthomeFreunde) on Telegram or anyone who is interested and willing to do so. 

The initial idea is to provide a fully working out-of-the-box smarthome environment based on the Docker technology and a preconfigured FHEM as well as a few more containers (see below). The hardware basis due to the Docker technology could be almost anything with an amd64 architecture (like e.g. Intel NUC etc.)

## Why fork the existing project? 

Even though this project is just great, the out-of-the-box approach doesn't fully work yet as homebridge and mySQL for example do not work right away. Fixing this is complex and time consuming. It is more of a community thing to do. 

But why only fix? New containers or further features would be a cool thing to have. Possible integrations could be the following to only name a few.  

- Portainer
- ioBroker
- LoxBerry
- Kodi
- Plex
- SmartVISU
and many more ...

special thanks to klein0r! To all the rest have fun using and developing!

# (OLD README) FHEM Docker Base

## Contains

- FHEM + haus-automatisierung.com FHEM frontend style + Tablet UI + ABFALL Module
- MQTT configured
- mySQL-Logging

## Requirements

- Docker
- Docker-Compose

## Install

```
git clone https://github.com/klein0r/fhem-docker.git fhem-docker (this is the path to the original repo!)
cd fhem-docker
docker-compose up -d
```

- FHEM: http://[ip]:8083/fhem
- Node-Red: http://[ip]:1880/

## Defaults

- FHEM-WEB: 8083 (8084 and 8085 have been deleted)
- mySQL-User: fhemuser
- mySQL-Password: 2jRHnEi3WuNSQAcX7
- Homekit-Pairing-Code: 012-34-567
