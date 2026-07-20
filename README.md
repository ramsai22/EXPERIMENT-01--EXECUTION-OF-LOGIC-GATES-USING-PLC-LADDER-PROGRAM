 # EXP1: EXECUTION OF LOGIC GATES USING PLC LADDER PROGRAM.
 
 # NAME : PAIDA RAM SAI
 # REGISTER NUMBER : 212223110034
 # DEPARTMENT : B.E.CSE(IOT)
 # YEAR : FINAL YEAR
 # DATE : 20.07.2026

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:
## AND GATE:
 <img width="327" height="250" alt="image" src="https://github.com/user-attachments/assets/5cf9dd15-a6e2-4d1e-880d-d113ef1f2d0d" />
 
## OR GATE:
 <img width="324" height="254" alt="image" src="https://github.com/user-attachments/assets/1e6935d4-47f8-4452-aecb-05fe4197dac7" />
 
## NOT GATE:
 <img width="214" height="159" alt="image" src="https://github.com/user-attachments/assets/8321a8ed-43b3-4e1b-88de-a151e3f22772" />
 
## NAND GATE:
 <img width="333" height="250" alt="image" src="https://github.com/user-attachments/assets/ebaa3105-cfe5-474e-b809-6c83415a019a" />
 
## NOR GATE:
 <img width="330" height="249" alt="image" src="https://github.com/user-attachments/assets/7fc0c378-9e21-42bb-bd6a-e950b9323c17" />
 
## XOR GATE:
 <img width="326" height="248" alt="image" src="https://github.com/user-attachments/assets/99d7a304-789c-4570-91a9-685e225d0996" />

# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS:

## AND GATE:
<img width="679" height="134" alt="Screenshot 2026-01-30 105256" src="https://github.com/user-attachments/assets/0cb7a363-2096-443e-9c63-5899b4d235ae" />

## OR GATE:
<img width="673" height="209" alt="Screenshot 2026-01-30 105322" src="https://github.com/user-attachments/assets/07c66130-781e-476c-918c-575d7753f99a" />

## NOT GATE:
<img width="656" height="136" alt="Screenshot 2026-01-30 105351" src="https://github.com/user-attachments/assets/7d0d308a-c63b-4a14-a45e-1e0df92c2d3a" />

## NAND GATE:
<img width="646" height="135" alt="Screenshot 2026-01-30 105413" src="https://github.com/user-attachments/assets/c3fe69b7-d1a2-423c-8b2a-27057bd15420" />
<img width="649" height="134" alt="Screenshot 2026-01-30 105429" src="https://github.com/user-attachments/assets/0f3d4383-0f44-4706-b571-82031deb0475" />

## NOR GATE:
<img width="666" height="130" alt="Screenshot 2026-01-30 105446" src="https://github.com/user-attachments/assets/390d7ad2-8897-4518-b3be-4ad904ebbedd" />
<img width="637" height="128" alt="Screenshot 2026-01-30 105458" src="https://github.com/user-attachments/assets/ed0db245-a9e2-49f2-8f33-45379aea4578" />

## XOR GATE:
<img width="657" height="230" alt="Screenshot 2026-01-30 105511" src="https://github.com/user-attachments/assets/a2a27697-b343-4f54-82a4-29a6aafa186c" />


## DEVICE MONITOR TABLE:

<img width="1919" height="1079" alt="Screenshot 2026-01-30 104856" src="https://github.com/user-attachments/assets/bfa6737a-b76c-419b-a682-353939cfa1ab" />

<img width="1919" height="1079" alt="Screenshot 2026-01-30 103856" src="https://github.com/user-attachments/assets/3587e76c-2d54-4d9c-a382-3fe589e5efe7" />

<img width="1919" height="1079" alt="Screenshot 2026-01-30 105028" src="https://github.com/user-attachments/assets/2c326b5a-c974-4e34-b0c0-db4bbec3079d" />

<img width="1919" height="1079" alt="Screenshot 2026-01-30 105234" src="https://github.com/user-attachments/assets/5277e530-d922-4f24-adae-8a0bf0997d90" />




# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
