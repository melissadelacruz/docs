---
title: Playing Music on a Speaker from SD Card
date: 2024-12-2
authors:
  - name: Melissa De La Cruz
  - name: Giselle Mendoza
  - name: Dustin Miller
---

![relevant graphic or workshop logo](image/path)

## Introduction

This tutorial aims to let others recreate one of the many steps from our project. Our group followed these steps in order to figure out some parts to the hardware side of our device. The integration of the SD card and speaker was done through thorough testing and this tutorial happens to be one of the tests done for the project. Our goal is for readers to learn how to test a speaker and amplifier, as well as integrate an SD card adapter to play an MP3 file through the speaker.

### Learning Objectives

- Understand the basics of speaker and amplifier functionality and how to test them
- Learn how to connect and configure an SD card adapter for audio playback
- Gain hands-on experience with hardware integration and troubleshooting techniques
- Develop the ability to play MP3 files through a speaker using an SD card adapter
- Apply systematic testing methods to ensure proper functionality of connected components
- Build foundational knowledge of audio device assembly and configuration for similar projects


## Getting Started


### Required Downloads and Installations

[Arduino Documentation](https://docs.arduino.cc/libraries/sd/): Comprehensive guide for programming sd card with Arduino.\
[ESP32-S3 Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf): Detailed specifications for the microcontroller.\
[Original Audio Hookup Guide](https://learn.sparkfun.com/tutorials/i2s-audio-breakout-hookup-guide/all): Original source used for this tutorial.\
[Arduino IDE](https://www.arduino.cc/en/software): IDE needed for microcontroller of use.\
[Arduino Audio Library (zip)](https://github.com/earlephilhower/ESP8266Audio/archive/master.zip): To use the library, you can add the library from Arduino by selecting Sketch ** > **Include Library ** > **Add .ZIP Library... and selecting the .zip file from wherever you store your file downloads. This will be used for the audio output of the speaker.

Ensure you familiarize yourself with these resources as they will be helpful throughout the tutorial.

### Required Components

List your required hardware components and the quantities here.

| Component Name | Quanitity | Notes |
| -------------- | --------- | ----- |
| Small Speaker  |1          | For audio output. Ensure it matches the amplifier specifications.
| Amplifier      |1          | To amplify the audio signal from the microcontroller.
| Breadboard     |1          | For prototyping the circuit connections.
| Jumper Cables  |Several    | To connect the components on the breadboard.
| Buttons        |2          | For controlling playback or other functionalities.
| SD Card        |1          | To store MP3 files for playback.
| SD Card Adapter|1          | For interfacing the SD card with the microcontroller.
| Microcontroller (ESP32-S3)|1| A powerful microcontroller with built-in Wi-Fi and Bluetooth support.
| USB-C cable    | 1         | To supply power to the microcontroller and upload code.
| Screw Terminal | 1 | To connect the amplifier to the speaker.

### Required Tools and Equipment

computer, soldering station, wire stripper

## Part 01: Speaker Testing

### Introduction

We will be testing the functionality of the speaker.

### Objective

- Learn how to set up a basic circuit to connect the speaker to the microcontroller.
- Understand how to install and use an audio library in the Arduino IDE.
- Configure the microcontroller to generate audio signals for the speaker.
- Test the speaker by playing simple audio output (e.g., tones or basic sound effects).


### Background Information

Give a brief explanation of the technical skills learned/needed
in this challenge. There is no need to go into detail as a
separation document should be prepared to explain more in depth
about the technical skills 

### Components

- List the components needed in this challenge

### Instructional

Teach the contents of this section

## Example

### Introduction

Introduce the example that you are showing here.

### Example

Present the example here. Include visuals to help better understanding

### Analysis

Explain how the example used your tutorial topic. Give in-depth analysis of each part and show your understanding of the tutorial topic

## Additional Resources

### Useful links

List any sources you used, documentation, helpful examples, similar projects etc.