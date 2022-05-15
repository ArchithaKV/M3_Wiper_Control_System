# Requirements:
## Wiper Control System:

## INTRODUCTION
The use of transportation vehicles has expanded dramatically over the world in recent years. As a result, it is critical to strengthen the safety features of automobiles. It is critical to conduct a survey and study to detail the automatic operated wiper in order to achieve and meet the above notion. Windshield Wipers are essential for ensuring the driver's safety while driving. As a result, the goal is to build a system that controls an automatic operated wiper that is controlled by an electronic sensor. We explore numerous sorts of sensors used in wiper automation in the research paper.

The operational speed of a wiper is controlled by a wiper speed control system in accordance with frequencies. The pulse signal is digitally processed to provide a control signal. A wiper driver circuit receives the control signal and adjusts the operational speed or timing in line with it. And the main purpose of the wiper system is to clean the windscreen sufficiently to provide suitable visibility at all times. 

# Swot Analysis
## Advantages
 * Provide clear vision to driver in rainy season
 * Help to remove dust and water from wind shield
 * Easy to operate
 
## Disadvantages 
 * Regular maintaince required
 * changing of wiper quarterly
 * Not fully automatic

The STM32F407 Kit takes advantage of the high-performance STM32F407 microcontrollers' capabilities to make it simple for users to create audio-based applications. It comes with an ST-LINK embedded debug tool, an ST-MEMS digital accelerometer, a digital microphone, an audio DAC with integrated class D speaker driver, LEDs, pushbuttons, and a USB OTG micro-AB connector.Ethernet connectivity, an LCD display, and other features have been added to the STM32F4 DISCOVERY kit. The STM32F405xx and STM32F407xx families are built around the high-performance Arm® Cortex®-M4 32-bit RISC core, which runs at up to 168 MHz.

# FEATURES OF STM32F407VG MICROCONTROLLER

In a LQFP100 package, the STM32F407VGT6 microcontroller has a 32-bit ARM Cortex-M4 with FPU core, 1-Mbyte Flash memory, and 192-Kbyte RAM.
On-board ST-LINK/V2 or ST-LINK/V2-A on STM32F4 DISCOVERY (old reference) or STM32F407G-DISC1 (new order code)
USB ST-LINK with three separate interfaces and re-enumeration capability.
Virtual Com port Debug port (with new order code only)
Large-scale storage (with new order code only)
Board power is supplied through USB or an external 5 V supply source.
3 V and 5 V external application power supply

## USES
This Microcontroller is utilised in printing and scanning machines ,heat ventilation, air conditioning, and security systems.
This module can be found in a variety of household products.

## WORKING PRINCIPLE
Assume that the automobile is the microcontroller. If the button is hit, the first led (red) will turn on, Clicking again  the wiper will start, and the second led (blue) will turn on for a desired rate. If the button is pressed again, the third led (green) will turn on, and the wiper's speed will be increased in comparison to the previous one. The fourth press will turn on the fourth led (orange), and the wiper speed will be increased in accordance with the previous one. The microcontroller (vehicle) is turned off after the fifth click.

# 4W'S

## WHAT
Windscreen wipers are necessary for maintaining sufficient view for the driver, especially in modern high-speed cars.

## WHY
To keep the windscreen clean enough to give adequate view at all times.

## WHEN
The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.

## WHO
Mark Anderson invented on 1902


## High Level Requirements
| Test ID | Description | Exp I/P| Exp O/P|Test case
| --- | --- | --- | ---- |-----|
| T_01 |Ignition key at ACC |User button is pressed & held for 2 sec| Red Led is ON |Pass|
| T_02| Wiper is ON| User button is Pressed | Blue,Green & Orange led is ON |Pass|
| T_03 | Wiper is OFF|  User button is Pressed| Blue,Green & Orange led is OFF |Pass|
| T_04|Igintion key at lock |User button is pressed & held for 2 se| Red Led is OFF|Pass|


## Low Level Requirements
| Test ID | Description | I/P|  O/P|
| --- | --- | --- | ---- |
| L_01 |  user button press for 2 sec| red Led on| wiper on|
| L_02| single press the button|Blue,Green,Orange Led glow|Wiper Rotates at different Hz(2,4,&8)|
| L_03 |  user button press for 2 sec| red Led off wiper off|

