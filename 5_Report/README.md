# Abstract :- 

A Wiper Speed Control System Controls the operational speed of the wiper in accordance with the rain condition.
This Wiper Speed Control System is used in all types of vehicles the main purpose is to clean the rain air drops present in front screen of the vehicles. 
It is very difficult to drive the vehicles in rain condition so in this case we will use wipers to clean the front screen of vehicles which is mirror so that we can drive the vehicles even in rain also

# Features :-
1.It shall lock the car when button is pressed ONCE.

2.It shall open the car when button is pressed TWICE.

3.It shall wiper on and it moves clock wise direction when button is pressed THREE times.

4.It shall wiper off and it moves anti clock wise direction when button is pressed FOUR times.

5.It shall wiper complete one cycle when the button is pressed FIVE times.

# WORKING PROCESS
* The RED LED is considered for the ACC position. Once the push button is pressed for 2 seconds, the RED LED keeps continuously glowing until the stop of the engine signifying the engine condition to be turned ON.
* On press of the user input push button, the other three Blue, Green and Orange LEDs come ON one at a time with the set frequency. The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz.
* The LED glow pattern stops on the 4th press; the wiper action starts with the next press.
* If the push button is pressed for 2 seconds continuously, the RED light goes off and the pattern stops bringing it to default position which signifies the engine is turned OFF.

# SWOT ANALYSIS
## Strength

* The wiper comes back to default position even if stooped in the middle
* Safety for the driver as well as the passengers in the vehicle
* Clear Visibility to the Driver for neat ride.

## Weakness 
* The total cost of the wiper system is high if implemented in real-time.
* The major disadvantage is that STM32 contains only one button for all the operation
* User has to undergo a sequence to acquire desired result and can't attain his result directly with the press of the button.

## Opportunities
* Rain sensing and automatic operation can be implemented as further enhancement.

## Threats 
* Replacing the board is not possible if it malfunctions.
* Can't have more functions as the functionality of the board is very basic.

# 5WS AND 1H
## WHAT
It is Wiper Control system which is generally deployed in all the automobiles in order to ensure safety for the passengers and drivers during rainy conditions.

## WHERE
It is an element which is present in the windshield of the automobile.

## WHO
It is highly useful for drivers of any kind of automobile who needs clear vision of the road in case of dust or rain.

## WHEN
It is recommended to operate during dust or rain

## WHY
To get a clear vision of the road.

## HOW
It is implemented with the help of STM32 with the desired operation of turning on the engine, changing of speeds and turning off with the help of Embedded c Programming.

# REQUIREMENTS
## High level requirements
| ID | Description | Status |
| --- | --- | --- | 
| HR_01 | ACC Mode Operation |	Implemented |
| HR_02 |	Wiper ON |	Implemented |
| HR_03 |	Wiper Speed Change |	Implemented |
| HR_04 |	Wiper OFF |	Implemented |
## Low level requirements
| ID |	Description | Operation |	Status |
| --- | --- | --- | --- |
| LR_01 |	Button pressed once for 2 secs | Red LED ON |	Implemented |
| LR_02 |	Button pressed second time | 1 Hz speed - Blue, Green Orange alternative |	Implemented |
| LR_03	|Button pressed third time | 4 Hz speed - Blue, Green Orange alternative |	Implemented |
| LR_04	|Button pressed fourth time | 8 Hz speed - Blue, Green Orange alternative |	Implemented |
| LR_05 |	Button pressed again for two seconds |Turn Off all LEDs |	Implemented |

![flow drawio](https://user-images.githubusercontent.com/68462123/167984507-39e7a274-725d-4490-9e44-343fc49e0197.png)


The figure bellow shows test plan and output




![QEMU](https://user-images.githubusercontent.com/68462123/167822701-48fdfbe6-8b64-4430-ba32-4b9a2077d9b6.png)

