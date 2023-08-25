##This Repo is a version of Joseph Hewitt wardriver.uk Rev3 with updated code for support for the BW16 RTL8720DN 5GHZ Board



# wardriver.uk Rev3

## Introduction

This repository is for the 3rd revision of the wardriver.uk created by [Joseph Hewitt](https://twitter.com/jhewitt_net). The wardriver.uk scans for nearby WiFi networks and Bluetooth devices and logs information about them to a CSV file which can be uploaded to [Wigle.net](https://wigle.net). A fully assembled Wardriver features 2 ESP32 modules, GPS, a SIM800L GSM module, an i2c LCD, a DS18B20 temperature sensor, and an SPI micro SD card reader/writer.

The main code is split up into 2 separate files (A and B) for the 2 different ESP32 boards within the Wardriver.

For information about the Wardriver hardware, please see [the official wiki](https://wardriver.uk)

## Repository Version

The `main` branch of this project is the testing/alpha branch; you should only use it if you are contributing code or want to help debug the latest features. Please use the `Releases` tab on the right to download stable versions.

The `main` branch is tesed for issues on every pull request, see the status of this test below:

![CI Status Badge](https://github.com/JosephHewitt/wardriver_rev3/actions/workflows/arduinobuild.yml/badge.svg)

## Flashing

 

If using the official PCB, the code in "B" corresponds to the board soldered above the silkscreen text "Made by Joseph Hewitt". The source file "A" is for the remaining ESP32. You may flash the boards when they are soldered to the PCB or before soldering -- it's your choice.

To upload code to your ESP32 boards, please use the following configuration in the `Tools` Arduino IDE dropdown menu:

- Board: `ESP32 Dev Module`
- Upload Speed: `921600`
- CPU Frequency: `240MHz (WiFi/BT)`
- Flash Frequency: `80MHz`
- Flash Mode: `DIO`
- Flash Size: `4MB (32Mb)`
- Partition Scheme: `Minimal SPIFFS (1.9MB APP with OTA/190KB SPIFFS)`
- PSRAM: `Disabled`
- Arduino Runs On: `Core 1`
- Events Run On: `Core 1`

If you have upload issues, try lowering the upload speed. Some users also report having to hold the "boot" button on the ESP32 board after connecting it to their PC before pressing the upload button in the Arduino IDE.

 

 
 

- Visit [Wigle.net](https://wigle.net/) and press the "Uploads" button in the top toolbar.
 
