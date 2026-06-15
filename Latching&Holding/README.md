# PLC Latching and Holding Circuit

## Objective

To understand and implement a latching (seal-in) circuit using PLC ladder logic.

## Software Used

- RSLogix Micro Starter Lite
- RSLogix Emulate 500
- RSLinx Classic Lite

## Inputs

| Address | Description |
|----------|------------|
| I:0/0 | Start Push Button |
| I:0/1 | Stop Push Button |

## Outputs

| Address | Description |
|----------|------------|
| O:0/0 | Motor |

## Logic Description

When the Start push button is pressed, the motor turns ON.

The output contact creates a holding path that keeps the motor ON even after the Start button is released.

When the Stop push button is pressed, the circuit opens and the motor turns OFF.

## Ladder Logic

![Latching Holding Circuit](latching_holding_circuit.png)

## Industrial Applications

- Motor Starter Circuits
- Conveyor Systems
- Pump Control Systems
- Industrial Machine Control

## Learning Outcome

- Understanding Latching Logic
- Holding Contact Implementation
- Start-Stop Motor Control
- PLC Programming Fundamentals

## Files Included

- Latching_Holding_Circuit.rss
- latching_holding_circuit.png
- README.md
