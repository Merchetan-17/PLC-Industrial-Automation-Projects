# PLC Timer Instructions (TON, TOF, and RTO)

## Objective

The objective of this project is to understand and implement the three most commonly used PLC timer instructions:

* TON (Timer ON Delay)
* TOF (Timer OFF Delay)
* RTO (Retentive Timer ON)

using Allen-Bradley PLC ladder logic.

## Software Used

* RSLogix Micro Starter Lite
* RSLogix Emulate 500
* RSLinx Classic Lite

## Timer Instructions Covered

### 1. TON (Timer ON Delay)

The TON instruction delays turning ON an output after the input becomes true.

### 2. TOF (Timer OFF Delay)

The TOF instruction delays turning OFF an output after the input becomes false.

### 3. RTO (Retentive Timer ON)

The RTO instruction accumulates elapsed time and retains its value even when the rung becomes false until it is reset.

## Logic Description

This project demonstrates the operation of TON, TOF, and RTO timers using ladder logic. Each timer is programmed and tested individually to understand its EN, TT, and DN status bits and timing behavior.

## Ladder Logic

### TON Timer

![Latching Holding Circuit]()

### TOF Timer

![Latching Holding Circuit]()

### RTO Timer

![Latching Holding Circuit]()

## Industrial Applications

* Motor Start Delay
* Motor Stop Delay
* Conveyor Control Systems
* Pump Control Systems
* Machine Sequencing
* Process Automation

## Learning Outcome

* Understanding PLC Timer Instructions
* Timer Configuration and Preset Values
* EN, TT, and DN Bit Operation
* PLC Simulation and Testing
* Industrial Automation Programming

## Files Included

* TON_Timer.rss
* TOF_Timer.rss
* RTO_Timer.rss
* TON_Timer.png
* TOF_Timer.png
* RTO_Timer.png
* README.md
