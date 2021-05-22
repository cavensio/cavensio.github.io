---
title: Cavencity
tags: [Arduino, Radio, RF24]
desc: Ventilation in a city apartment
date: 2021-05-10
---

# Cavencity

Ventilation in a city apartment.

Overview
![Overview diagram](/resources/cavencity-diagram-overview.png)

Modules
![Modules diagram](/resources/cavencity-diagram-modules.png)

Source code repository [link](https://github.com/cavensio/cavencity)


## Master

TODO schema
TODO photo

Source code 
[cavencity-master.ino](https://github.com/cavensio/cavencity/blob/master/cavencity-master/cavencity-master.ino)


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
[cavencity-slave.ino](https://github.com/cavensio/cavencity/blob/master/cavencity-slave/cavencity-slave.ino)

## TODO

