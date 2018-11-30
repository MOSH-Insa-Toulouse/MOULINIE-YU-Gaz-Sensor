# Connected gas sensor / LoRa TTN
Project 5th ISS - MOSH - TP Gas Sensor
Authors: MOULINIÉ Dorian & YU Juan from INSA Toulouse - 5 ISS

# Description

This main goal of this project is to build a connected nanoparticle gas sensor to monitor the concentration of gas.

For this, we used an Arduino UNO and RN2483 LoRa chip to send data on the The Things Network.

# Content

KiCad PCB Files: A shield for the gas sensor and the LoRa Module to plug in an Arduino Uno

## Overview

This shield is composed of:

 - a LoRa Module (RN2483) as transceiver
 - a Gas sensor
 - an amplifier (LTC1050)
 - a Groove connector for future calibration of the Gas Sensor

First, we created the project with an anduino UNO
Then, we created a library symbole for LTC 1050
Afterwards, we created the following circuit : 

### PCB
