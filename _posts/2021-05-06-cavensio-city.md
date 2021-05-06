---
title: Cavensio-city
tags: [Arduino, Radio, RF24]
desc: Ventilation in a city apartment
date: 2021-05-06
---

# Cavensio-city

Ventilation in a city apartment.

TODO overview
TODO diagram

Source code repository [link](https://github.com/cavensio/cavensio-city)


## Master

TODO schema
TODO photo

Source code 
[cavensio-city-master.ino](https://github.com/cavensio/cavensio-city/blob/master/cavensio-city-master/cavensio-city-master.ino)


Example

```c
const uint8_t CAVE_ADDRESS[][6] = {"cave0", "cave1", "cave2"};

const uint8_t CHANNEL = 69;
const uint8_t RADIO_SPEED = RF24_2MBPS; //RF24_250KBPS
const uint8_t RADIO_POWER = RF24_PA_LOW; //RF24_PA_HIGH
const uint8_t RADIO_CE_PIN = 9;
const uint8_t RADIO_CS_PIN = 10;
```

## Slave

TODO schema
TODO photo

Source code 
[cavensio-city-slave.ino](https://github.com/cavensio/cavensio-city/blob/master/cavensio-city-slave/cavensio-city-slave.ino)

## TODO

