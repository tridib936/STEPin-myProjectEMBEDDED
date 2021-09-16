# TEST PLAN:
## Table no 1: High level test plan

|Test ID|	Description|	Exp I/P|	Exp O/P|	Actual Out|	Type Of Test|
|---|---|---|---|---|---|
|H_01|	Switching on|	HIGH	|The program should start|	The program starts|	Requirement based|
|H_02|	Taking input from the temperature sensor|	temperature input|	The microcontroller should then send control to heater if required|	The program proceeds|	Scenario based|
|H_03|	Giving output from the heater|	Temperature input from sensor|	Seat starts heating|	Seat heats|	Boundary based|

## Table no 2: Low level test plan

|Test ID|	Description|	Exp I/P|	Exp O/P|	Actual Out|	Type Of Test|
|---|---|---|---|---|---|
|L_02-H_02|	Identifying how much temperature needs to be increased|Input to heater if the temperature is low|	Seat heats|Seat heats|	Requirement based|
