Codacy
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/823522ee74ba4d4d99af22948340780d)](https://www.codacy.com/gh/05AnshulThakur/M2-EmbSys/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=05AnshulThakur/M2-EmbSys&amp;utm_campaign=Badge_Grade)

CI  
[![CI](https://github.com/05AnshulThakur/M2-EmbSys/actions/workflows/main.yml/badge.svg)](https://github.com/05AnshulThakur/M2-EmbSys/actions/workflows/main.yml)

Codiga
![Codiga Badge](https://api.codiga.io/project/31598/score/svg)  ![Codiga Badge]( https://api.codiga.io/project/31598/status/svg)

## Description:
It is very uncomfortable to sit on the seat of a car when it is cold and not having required temperature. The sensor will sense the temperature of the seat and the heater will heat the seat to the required temperature. The Heater will generate the heat and a uart display will show the temperature. Here we have used ATmega328 microcontroller to make all the decisions.

## Application:
1. Cars In winters.
2. Areas where winter season is very long and vehicle seats are cold.
3. Truckers can also use this to make seat temperature comfortable.
 
## Requirements:

### High Level Requiremnets:
| ID | Description | 
| ----- | ----- | 
| HR01 | It shall sense the temperature of the seat. |
| HR02 | It shall Display the reading. |
| HR03 | It shall start heating the seat . |
| HR04 | It shall stop after reaching the appropriate temperature.|

 ### Low Level Requirements:
| ID | Description | HLR ID |
| ------ | --------- | ------ |
| LR01 | Temperature sensor will detect the temperature. | HR01 |
| LR02 | Display will show the reading. | HR02 |
| LR03 | The heater shall start heating the seat . | HR03 |


## 4 W's And 1 H
### Who:
Drivers of vehicles.
### What:
It will heat the seat.
### When:
When the temperature of seat is low , it can be heated to required temperature.
### Where:
Where there are long winters.
### How:
The sensor will sense the temperature and heater can heat the seat.

## SWOT Analysis
![S W O T](https://user-images.githubusercontent.com/98889318/157021144-4f70591a-6e28-4caf-a785-ab064151422f.png)

## Structural Design:
### Block Diagram:
![Block Diagram](https://user-images.githubusercontent.com/98889318/156899380-c48627df-3d39-4732-8d49-2ffd382b4cf0.png)


### Explanation of Components:

### LIGHT-EMITTING DIODE:
A light-emitting diode (LED) is a semiconductor light source that emits light when current flows through it.

### TEMPERATURE SENSOR:
Temperature sensor is a device, used to measure the temperature using an electrical signal.

### MICROCONTROLLER:
It is the brain of the whole system. All the decision making and calculations are done by it.

### HEATER:
It will heat the seat.

### POWER SOURCE:
It provides power to the whole system to work according to the microcontroller:

### ACTUATOR (MOTOR):
It is used to irrigate the field with water.

### INPUT DEVICE:
It is used to give input values to the microcontroller.


## Behavioural Design:
  ### Flow Chart:
  ![Pic](https://user-images.githubusercontent.com/98889318/156899559-87efacb1-046b-41c0-b7a8-ae1fb064100e.png)
