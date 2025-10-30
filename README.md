# EXPERIMENT-03-DEVELOPING-COUNTER-LADDER-LOGIC-FOR-PLC-
## NAME: PANIMALAR P
## REGISTER NUMBER: 212222110031
## DEPARTMENT: CSE(IoT)
## YEAR: IV

### Aim:
To understand and implement various counter operations in Programmable Logic Controller (PLC) ladder logic.

### Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports counter functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger the counter operations.
Output Devices: LEDs or other indicators to visualize the counter outputs.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.

### Theory:
Counters in PLCs are used to count events or occurrences, such as the number of items passing on a conveyor belt, the number of cycles a machine runs, or how many times a process has started or stopped. Counters are commonly used in automation to perform tasks like stopping a machine after a set number of products or signaling a notification when a count reaches a specific value.

### Types of Counters:
Up Counter (CTU) Functionality:

The up counter counts every time the input condition becomes TRUE (ON). When the accumulated value reaches the preset value, the counter output becomes TRUE. If the reset input is triggered, the counter resets to zero.
Down Counter (CTD) Functionality:

The down counter decreases the count every time the input condition becomes TRUE (ON). When the count reaches zero, the counter output becomes TRUE. The counter can be reset by a reset input to the preset value.
Up/Down Counter (CTUD) Functionality:

The up/down counter can increment or decrement the count based on two different inputs. One input increments the count, while the other decrements it. When the count reaches the preset value or zero, the respective outputs become TRUE. The counter can be reset as required.


### Procedure:
Setup the PLC Programming Environment:
Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Counters:
Up Counter (CTU):

Create a rung with an input (e.g., a push button) linked to a CTU instruction.
Set the preset value (e.g., 10 counts). Assign an output to indicate when the preset value is reached.
Down Counter (CTD):

Create a rung with an input linked to a CTD instruction.
Set the preset value (e.g., 5 counts). Assign an output to indicate when the counter reaches zero.
Up/Down Counter (CTUD):

Create a rung with separate inputs for counting up and counting down.
Set the preset value (e.g., 8 counts). Assign outputs for when the count reaches the preset value or zero.
Simulate the Ladder Logic:
Up Counter (CTU):

Run the simulation in the PLC software. Press the input button repeatedly and observe the counter increment until the preset value is reached, at which point the output activates.
Down Counter (CTD):

Run the simulation, press the input button repeatedly, and observe the counter decrement. When the counter reaches zero, the output activates.
Up/Down Counter (CTUD):

Simulate both the up and down counting inputs. Observe how the counter increments or decrements and how the output is activated when the count reaches the preset value or zero.
Download and Execute:
Download the ladder logic program to the PLC if available and run it.
Test the counters with the physical push buttons and observe the LEDs or other output devices.
### Outputs:
Up Counter (CTU): The output LED or indicator should activate when the preset count (e.g., 10) is reached.
Down Counter (CTD): The output should activate when the count reaches zero.
Up/Down Counter (CTUD): The output should activate when the count reaches the preset value or zero, depending on the inputs.

### Simulation Screenshots:

##  COUNTER

<img width="1919" height="1014" alt="image" src="https://github.com/user-attachments/assets/8424f8d7-1624-4a70-8bf7-9e92ccfb1199" />

<img width="1919" height="1023" alt="image" src="https://github.com/user-attachments/assets/a5e16297-10d0-4107-8dd8-d1b796f5ecf1" />


<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/9b6e9146-b2cb-4a88-b15c-9117f81ba0f8" />

<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/074fd551-3d48-4e92-a48a-cca415bcdc61" />

<img width="1907" height="1018" alt="image" src="https://github.com/user-attachments/assets/e1f5bd54-1ed4-496d-9f72-f5e2763af280" />

<img width="1919" height="1017" alt="image" src="https://github.com/user-attachments/assets/6f1ddb25-9154-4e76-a6bf-d6915a49a7f6" />

## UP COUNTER

<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/d10a73d8-310f-4d4b-ba69-ea6d46cfde5f" />
<img width="1504" height="155" alt="image" src="https://github.com/user-attachments/assets/1789d325-bf08-4f96-b08e-6d333e369175" />
<img width="1501" height="200" alt="image" src="https://github.com/user-attachments/assets/80580b9e-e153-419e-a77d-b80c70d1517a" />
<img width="1500" height="250" alt="image" src="https://github.com/user-attachments/assets/fc879771-5efa-44ef-ba39-3bccbda69c6d" />

## DOWN COUNTER
<img width="1463" height="647" alt="image" src="https://github.com/user-attachments/assets/335fb845-a6ec-4828-b76e-593fe5555e80" />
<img width="1351" height="375" alt="image" src="https://github.com/user-attachments/assets/0b591846-3700-465f-8845-2e8ff21df6e9" />
<img width="1502" height="229" alt="image" src="https://github.com/user-attachments/assets/3244f3c8-f554-4d12-85ba-e8a2806379f7" />
<img width="1504" height="339" alt="image" src="https://github.com/user-attachments/assets/b218a96b-d074-46b6-84eb-8ec7feb2615b" />
<img width="1509" height="312" alt="image" src="https://github.com/user-attachments/assets/385d8af6-42f6-47e0-8c7a-b555fd2c8058" />


## UP/DOWN COUNTER - 1

<img width="1606" height="651" alt="image" src="https://github.com/user-attachments/assets/bb44dd6f-189d-438b-99ad-beeb9302e3a0" />
<img width="1406" height="548" alt="image" src="https://github.com/user-attachments/assets/dfef5e5d-791d-4bbc-9310-700a3ce2bca0" />
<img width="1505" height="220" alt="image" src="https://github.com/user-attachments/assets/f852d690-42b9-43eb-858e-3a1792d28661" />
<img width="1503" height="193" alt="image" src="https://github.com/user-attachments/assets/052d4a4f-22e7-4ed5-a633-4c2cb2d01e1c" />
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/2de494fd-0783-49fa-a752-f2d404ef3841" />
<img width="1919" height="1025" alt="image" src="https://github.com/user-attachments/assets/dcab747b-726a-4d3b-8d7f-014544fa9971" />



## UP/DOWN COUNTER - 2

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/949f1ac1-4242-480d-a46f-3da6e3207f2c" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/411bacdb-e831-41a1-9c7d-3849c6c004c2" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/73cb3c01-7cf9-457e-8b02-c7d94cb29774" />




### Results:
The ladder logic programs for Up Counter (CTU), Down Counter (CTD), and Up/Down Counter (CTUD) were successfully implemented and tested. The outputs behaved as expected, indicating correct counting operations. The experiment demonstrated how counters are essential in automation for counting events and managing process sequences.
