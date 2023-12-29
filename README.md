# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
 


## Procedure:
1.Create a New Project:
Open Quartus and create a new project by selecting "File" > "New Project Wizard." Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA).

2.Create a New Design File:
*Once the project is created, right-click on the project name in the Project Navigator and select "Add New File." *Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description language.

3.Write the Combinational Logic Code:
*Open the newly created Verilog or VHDL file and write the code for your combinational logic.

4.Compile the Project:

*To compile the project, click on "Processing" > "Start Compilation" in the menu. *Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device.

5.Analyze and Fix Errors:

*If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window.

*Review and fix any issues in your code if necessary. *View the RTL diagram.

6.Verification:

*Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF".

*Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On "List" > Select All.

*Give the Input Combinations according to the Truth Table and then simulate the Output Waveform
## Program:

Developed by: Dharshini K

RegisterNumber: 23010696

### Code:

![Screenshot 2023-12-29 033132](https://github.com/dharshini-29/Experiment--02-Implementation-of-combinational-logic-/assets/147474632/e34a0b8e-af4e-4197-b364-4c6a0323179b)

## Output:
### Truthtable:

![image](https://github.com/dharshini-29/Experiment--02-Implementation-of-combinational-logic-/assets/147474632/995795ad-38e0-42fb-aa5a-61934f87c3fd)

## RTL:

![Screenshot 2023-12-01 083517](https://github.com/dharshini-29/Experiment--02-Implementation-of-combinational-logic-/assets/147474632/e942e17d-c85b-4ac0-975d-6a9d5bd8acdb)

## Timing Diagram:

![Screenshot 2023-12-01 083758](https://github.com/dharshini-29/Experiment--02-Implementation-of-combinational-logic-/assets/147474632/00449ca8-a3c0-4dba-ab8c-24a49ecf48a4)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
