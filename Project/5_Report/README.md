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
