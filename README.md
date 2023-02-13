# WorkShop AI Essentials with Nano 33 BLE sense

This is a workshop for secondary schools on AI essentials.

This workshop is based on the following tutorials:

* [TensorFlow Lite gesture training tutorial](https://github.com/arduino/ArduinoTensorFlowLiteTutorials).
* [Get Started With Machine Learning on Arduino](https://docs.arduino.cc/tutorials/nano-33-ble-sense/get-started-with-machine-learning)
* [TensorFlow Lite for Microcontrollers TensorFlow Website](https://www.tensorflow.org/lite/microcontrollers)
* [AI@EDGE Workshop](https://ai-edge-workshop.netlify.app/)

## Overview

1. Introduction into AI
2. Hello World on Microcontroller (sinus wave)
3. Flex your muscles (edge impuls)

### Dependencies

* Board: Arduino Mbed OS Nano Boards
* Library: Arduino_LSM9DS1
* Library: Harvard_TinyMLx

## Raspberry Pi OS image

This workshop is optimized to run on a [Raspberry Pi 400](https://www.raspberrypi.com/products/raspberry-pi-400/) or any other [Raspberry Pi 4](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/) device.
Make sure to install the 64-bit Raspberry OS.
Use [Raspberry Pi Imager](https://www.raspberrypi.com/software/) to flash the SD card.

## Raspberry Pi Workstation Setup

Setup the Raspberry Pi using the setup script as follows:

```bash
curl -sL https://bit.ly/setup-ai-rpi | bash -s --
```

**Note: some parts of the script can take quite a while, this is normal.**

## Hardware requirements

Necessary hardware to do the workshop:

- [Raspberry Pi 4](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/) or [Raspberry Pi 400](https://www.raspberrypi.com/products/raspberry-pi-400/) with Screen, Mouse, Keyboard, SD card with the correct OS. Only [Raspbian buster 64 bit](http://downloads.raspberrypi.org/raspios_arm64/images/raspios_arm64-2021-05-28/) is supported.
- [Nano 33 BLE Sense](https://docs.arduino.cc/hardware/nano-33-ble-sense)
- Long USB Cable

## Project files

All project files can be found in the repository of the workshop. The files are cloned in the home directory of the `pi` user when running the installation script.

## Issues

Feel free to submit issues and enhancement requests.

## Other Useful Sources

* [Say hello to the "Hello, World" of machine learning](https://developers.google.com/codelabs/tensorflow-1-helloworld)
* [Deep Learning](https://srdas.github.io/DLBook/)
