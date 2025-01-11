# Rotary Encoder Finite-State Machine (FSM) Design

This repository contains the design, implementation, and testing of a Mealy type Finite-State Machine (FSM) for detecting clockwise rotations of a rotary encoder and incrementing a counter.

## Overview

The project involves designing an FSM to process input signals from a rotary encoder and producing an output that increments a counter for each clockwise rotation. The design is implemented using `Digital` simulation software, and the repository includes all necessary files to understand, simulate and verify the FSM functionality.

## Features

- **Mealy FSM Design**: Detects clockwise rotations based on rotary encoder signals.
- **State Machine Implementation**: Implements a simplified state transition model.
- **Test Bench**: Includes a test setup for validating the FSM behavior.
- **Demonstration Video**: Showcases the expected behavior of the design.

## Files

- `rotarytest.dig`: Test bench for verifying the FSM design.
- `statemachine.dig`: Implementation of the FSM for the rotary encoder.
- `upcounter.dig`: Counter module connected to the FSM for demonstration.
- `demo.mp4`: Video demonstrating the expected behavior of the FSM.

## Steps to Reproduce

1. **Open the Files**:
   - Use the `Digital` simulation tool to open the `.dig` files provided in the repository.

2. **Load the Test Bench**:
   - Open `rotarytest.dig` to load the test bench setup.
   - Place `statemachine.dig` as the FSM module within the test bench.

3. **Simulate**:
   - Run the simulation in `Digital` and observe the behavior of the FSM when processing rotary encoder signals.

4. **Verify the Counter**:
   - Connect `upcounter.dig` to verify that the counter increments correctly with each clockwise rotation.

## FSM Design Details

### State Diagram
The state diagram models the transitions based on the input signals from the rotary encoder. Each state is defined based on the encoder's waveform pattern and the output indicates a clockwise rotation.

### State Transition Table
A detailed state transition table is constructed to define the behavior of the FSM.

### Simplification
The FSM logic is simplified using Karnaugh Maps (K-maps) to minimize the number of required logic gates.

## Requirements

- **Software**: `Digital` simulation tool.
- **Input**: Rotary encoder signals (A, B).
- **Output**: Incremented counter value for clockwise rotations.

## Usage

1. Download all files in the repository.
2. Open `.dig` files in `Digital`.