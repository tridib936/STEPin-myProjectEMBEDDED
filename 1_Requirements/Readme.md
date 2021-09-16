# Requirements
## Introduction
Vehicles today have a lot of features that make travelling safe and comfortable. Air conditioners in vehicles have been an integral part of it in recent times. Another such feature is a seat heater. In cold countries, the air conditioner warms up the car, but the seat may be still too cold to sit on. So a seat heater is implemented to make it more comfortable.

## Cost and Features and Timeline
A seat heater consistes of a temperature sensor and a heater, both of which are not too costly. It comes along with some other parts such as a microcontroller and some buttons. All together this is a cheap but usefull feature which can be used even in the distant future without much hike in price.

## Defining Our System
Our system, ie seat heater consists of a microcontroller, Atmega328, a temperature sensor, a heater and a button to check if the person is seated or not.

## SWOT ANALYSIS
![swot embedded](https://user-images.githubusercontent.com/61946877/133629807-44c4940f-3cda-47d0-b9f5-a288c324d2f3.png)

## 4W's and 1'H
### Who:
    This project can be used by anyone who wants to feel comfortable while travelling by car in cold conditions. This will need to be implemented by the car manufacturer for the person to use.
### What:
    The user will not have to feel the cold seat against him/her while driving the car.
### When:
    This project can be used by any person who buys a car with this feature.
### Where:
    A user will need a car to use this project.
### How:
    This project will be made in C languege with Atmega328 using multifile approach.
    
## Detail requirements
### High Level Requirements:

|ID|	Description|	status|
|---|---|---|
|HLR_1|	Switching on and off|	Implemented|
|HLR_2|	Taking input from the temperature sensor|	Implemented|
|HLR_3|	Giving output from the heater|	Implemented|

### Low level Requirements:

|ID|	Description|	status|
|---|---|---|
|LLR_2-HLR_2|	Identifying how much temperature needs to be increased|	Implemented|
