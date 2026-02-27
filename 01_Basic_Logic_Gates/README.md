Objective: The objective of this project is to understand and implement basic digital logic gates using PLC ladder logic. These gates form the foundation of industrial automation programming.

📘 Software Used:

RSLogix Micro starter Lite w/o RSlinx EN(8.30.00)

RSLogix Emulate 500 6.00.00

RSLinx Classic Lite for MicroLogic

📘 Logic Gates 

1️⃣ NOT Gate

Boolean Expression: Y = A'

Description:
The NOT gate inverts the input signal.
If input is ON (1), output becomes OFF (0).
If input is OFF (0), output becomes ON (1).

2️⃣ AND Gate

Boolean Expression: Y = A • B

Description:
Output turns ON only when both inputs are ON.
If any one input is OFF, output remains OFF.

3️⃣ OR Gate

Boolean Expression: Y = A + B

Description:
Output turns ON if at least one input is ON.
Both inputs do not need to be ON.

4️⃣ NAND Gate

Boolean Expression: Y = (A • B)'

Description:
Output is OFF only when both inputs are ON.
In all other conditions, output remains ON.

5️⃣ NOR Gate

Boolean Expression: Y = (A + B)'

Description:
Output turns ON only when both inputs are OFF.
If any input becomes ON, output turns OFF.

![Basic Logic Gates](https://github.com/Merchetan-17/PLC-Industrial-Automation-Projects/blob/main/01_Basic_Logic_Gates/Basic%20Logic%20gates.png?raw=true)

🔷XOR Gate 

Boolean Expression: Y = A'B + AB'

Description:
Output turns ON only when inputs are different.
If both inputs are same (both ON or both OFF), output is OFF.

🔷XNOR Gate


Boolean Expression: Y = AB + A'B'

Description:
The XNOR gate produces output HIGH when both inputs are equal. 
It is also known as the Equivalence Gate.


 ![XNOR & XOR GATE](https://github.com/Merchetan-17/PLC-Industrial-Automation-Projects/blob/main/01_Basic_Logic_Gates/XNOR%20&%20XOR%20GATE.png?raw=true)

<img width="1291" height="327" alt="Image" src="https://github.com/user-attachments/assets/ee7a24af-e24c-433d-a3e5-4d509a45652e" />

All Gates Truth Table :
 ![gates truth table](https://github.com/Merchetan-17/PLC-Industrial-Automation-Projects/blob/main/01_Basic_Logic_Gates/gates%20truth%20table.png?raw=true)
