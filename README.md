# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
# NAME: THEJASWINI D
# REGISTER NUMBER: 212223110059
# DEPARTMENT: B.E.CSE(IOT)
# YEAR: III
# DATE: 23.02.2026
## Aim:
To understand and implement various arithmetic and logical operations in Programmable Logic Controller (PLC) ladder logic.

## Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports arithmetic and logical functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger arithmetic and logical operations.
Output Devices: LEDs or other indicators to visualize the results of operations.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.
## Theory:
Arithmetic and logical operations in PLC ladder logic are essential for handling complex decision-making and calculations within automation processes. Arithmetic operations (e.g., addition, subtraction, multiplication, division) and logical operations (e.g., AND, OR, NOT) allow PLCs to perform calculations, make comparisons, and control actions based on specific conditions.

## Types of Operations:
Arithmetic Operations:

Addition (ADD): Adds two values and stores the result in a specified memory location.
Subtraction (SUB): Subtracts one value from another.
Multiplication (MUL): Multiplies two values.
Division (DIV): Divides one value by another.
Logical Operations:

AND Operation: The output is TRUE only when all inputs are TRUE.
OR Operation: The output is TRUE when any input is TRUE.
NOT Operation: Inverts the input logic.
Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Arithmetic Operations:

Addition (ADD):
Create a rung with an input (e.g., push button) linked to an ADD instruction.
Set the operands (e.g., two values) and the destination to store the result.
Subtraction (SUB):
Create a rung with an input linked to a SUB instruction.
Set the values and the destination to store the result.
Multiplication (MUL):
Create a rung with an input linked to a MUL instruction.
Set the values and the destination to store the result.
Division (DIV):
Create a rung with an input linked to a DIV instruction.
Set the values and the destination to store the result.
Create Ladder Logic for Logical Operations:

AND Operation:
Create a rung with two inputs connected in series to simulate an AND operation.
Assign an output to visualize when both inputs are TRUE.
OR Operation:
Create a rung with two inputs connected in parallel to simulate an OR operation.
Assign an output to visualize when any input is TRUE.
NOT Operation:
Create a rung with a single input connected to a NOT function.
Assign an output to visualize the inverted logic.
Simulate the Ladder Logic:

Arithmetic Operations:
Run the simulation in the PLC software. Trigger each operation by pressing the input button, and observe the output values.
Logical Operations:
Simulate the AND, OR, and NOT logic by toggling the inputs and observing the outputs.
Download and Execute:

Download the ladder logic program to the PLC if available and run it.
Test the arithmetic and logical operations with physical push buttons and observe the LEDs or other output devices.


## Outputs:

<img width="1214" height="467" alt="Screenshot 2026-02-23 103701" src="https://github.com/user-attachments/assets/0d9cf1f3-0afe-4946-8125-8271dc8b5453" />

<img width="966" height="513" alt="Screenshot 2026-02-23 103716" src="https://github.com/user-attachments/assets/0fee04c0-e0d5-4519-944b-bb3cf5fd053d" />

<img width="841" height="459" alt="Screenshot 2026-02-23 104733" src="https://github.com/user-attachments/assets/a4d30c78-1748-4e7f-8abc-8c4cfe4d6818" />

<img width="948" height="415" alt="Screenshot 2026-02-23 104753" src="https://github.com/user-attachments/assets/d11c1e89-78a5-47ba-9c2e-260590c71abe" />

<img width="886" height="405" alt="Screenshot 2026-02-23 104806" src="https://github.com/user-attachments/assets/2400d9a3-4922-4bf1-b8bb-8a8ef6ac4a90" />

##  Simulation Screenshots:
## ADDITION:
<img width="1218" height="551" alt="Screenshot 2026-02-23 103534" src="https://github.com/user-attachments/assets/06cc7f34-cb75-43e0-843f-0592710efa84" />

## SUBTRACTION:
<img width="1246" height="602" alt="Screenshot 2026-02-23 103549" src="https://github.com/user-attachments/assets/62e86df3-b549-4172-951b-dfb3da60a118" />

## MULTIPLY:
<img width="1244" height="611" alt="Screenshot 2026-02-23 103603" src="https://github.com/user-attachments/assets/1eced454-a6de-471a-834b-776a0c21a087" />

## DIVISION:
<img width="1236" height="604" alt="Screenshot 2026-02-23 103619" src="https://github.com/user-attachments/assets/316a5a68-1a0e-43ab-a581-21865e5c6dbc" />

## OR:
<img width="1233" height="601" alt="Screenshot 2026-02-23 104606" src="https://github.com/user-attachments/assets/e75f2a59-9729-4cd9-afbc-4991d2c1c28e" />

## AND:
<img width="1241" height="602" alt="Screenshot 2026-02-23 104619" src="https://github.com/user-attachments/assets/a8cebc4e-ebea-422c-9484-735a36e61c68" />

## XOR:
<img width="1245" height="606" alt="Screenshot 2026-02-23 104633" src="https://github.com/user-attachments/assets/4442fa2c-1c24-4f48-a7f1-2bebd60b0d1c" />

## NEGATIVE(NOT):
<img width="1232" height="590" alt="Screenshot 2026-02-23 104645" src="https://github.com/user-attachments/assets/d8922b75-caf9-4408-a4d0-cd59205d631a" />

## DECREMENT:
<img width="1241" height="598" alt="Screenshot 2026-02-23 104658" src="https://github.com/user-attachments/assets/047f84bc-09ab-418a-a90b-e118aae7056f" />

## INCREMENT:
<img width="1228" height="601" alt="Screenshot 2026-02-23 104712" src="https://github.com/user-attachments/assets/2f787f38-2c9c-4c24-8845-be700bf2c48d" />

## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
