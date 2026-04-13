# Traffic Light Controller (Digital Logic Design)

## Overview
A digital logic circuit that simulates a traffic light intersection. The system cycles between two directions, ensuring safe transitions between green, yellow, and red states without conflicting signals.

## Features
- Alternating traffic flow between two directions
- Sequential light transitions: Green → Yellow → Red
- Prevents unsafe states (no simultaneous green lights)
- Continuous looping behavior
- Manual state progression using push-button inputs

## Design Concepts
- Logic gates (AND, OR, NOT)
- State-based sequencing
- Timing control using combinational logic
- LED outputs to represent traffic signals

## How It Works
The circuit controls two traffic light systems:

- When one direction is green, the other remains red  
- Each direction transitions through yellow before switching  
- Logic ensures no overlap of conflicting signals  
- The system continuously cycles through predefined traffic states  

## State Progression
The system uses a counter controlled by push buttons to cycle through traffic light states.

- Each count represents a specific stage in the traffic light sequence  
- The counter progresses from 0 to F (hexadecimal), triggering different light outputs  
- As the count increases, the circuit transitions through green, yellow, and red states for each direction  
- A reset button allows the system to return to the initial state (0)  

This design allows manual observation of each transition stage, making it easier to verify correct sequencing and safety constraints.

## Inputs and Controls
- Push buttons used to increment the counter and simulate state transitions  
- Reset button returns the system to the initial state  
- LEDs display the active traffic light signals for each direction  

## Demo
<p align="center">
  <img src="https://github.com/user-attachments/assets/e3824fa1-83eb-42a7-97e3-ac98de1086f8" width="80%" />
</p>
