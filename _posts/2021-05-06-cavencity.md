---
title: Cavencity
tags: [Arduino, Radio, RF24]
desc: Ventilation in a city apartment
date: 2021-05-23
---

# Cavencity

Ventilation in a city apartment.

##Overview

![Overview diagram](/resources/cavencity-diagram-overview.png)

![Modules diagram](/resources/cavencity-diagram-modules.png)


## Source code

Repository [link](https://github.com/cavensio/cavencity)


## Master MCU

Source code 
[cavencity_master.ino](https://github.com/cavensio/cavencity/blob/master/cavencity_master/cavencity_master.ino)

TODO

Example

```c
const uint8_t CAVE_ADDRESS[][6] = {"cave0", "cave1", "cave2"};

const uint8_t CHANNEL = 69;
const uint8_t RADIO_SPEED = RF24_2MBPS; //RF24_250KBPS
const uint8_t RADIO_POWER = RF24_PA_LOW; //RF24_PA_HIGH
const uint8_t RADIO_CE_PIN = 9;
const uint8_t RADIO_CS_PIN = 10;
```

## Slave MCU

Source code 
[cavencity_slave.ino](https://github.com/cavensio/cavencity/blob/master/cavencity_slave/cavencity_slave.ino)

TODO

## Desktop client

Source code
[link](https://github.com/cavensio/cavencity/tree/master/cavencity_desktop_client)

TODO

## Dummy master MCU

Source code
[cavencity_dummy_master.ino](https://github.com/cavensio/cavencity/blob/master/cavencity_master/cavencity_dummy_master.ino)

TODO

