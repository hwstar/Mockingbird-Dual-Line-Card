# Mockingbird-Dual-Lane-Card
A dual subscriber line card for the Mockingbird Telephone Exchange

![alt text](https://github.com/hwstar/Mockingbird-Dual-Line-Card/blob/main/assets/dual-line-card.jpg)

An interface card design for the Mockingbird Telephone Exchange. 

Features: 
* Provides two subscriber line interfaces.
* STM32F103C8T6 microcontroller.
* Accessed from the Main Microcontroller over I2C
* ATTEN signal to main microcontroller to tell it when there is an event to service.
* Audio bandpass filter for the received audio.
* Uses one R-TONE KS0835 SLIC module for each telephone line interface.
* Analog RX audio output, and TX audio input.
* Designed n KiCAD 8.0.

The main project website is on hackaday.io here: https://hackaday.io/project/196044-mockingbird-telephone-exchange
