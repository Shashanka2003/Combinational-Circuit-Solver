# boolean-calculator
# Boolean Algebra Calculator

## Overview
This project involves designing a digital Boolean algebra calculator capable of performing various Boolean operations such as AND, OR, NOT, XOR, NAND, and NOR using Cadence software. The calculator accepts two binary inputs and a control signal to select the operation, and it outputs the corresponding result.

## Problem Statement
The Boolean algebra calculator supports the following operations: 
- **AND**
- **OR**
- **NOT**
- **XOR**
- **NAND**
- **NOR**
- **HALF ADDER**
- **FULL ADDER**
- **HALF SUBSTRACTOR**
- **FULL SUBSTRACTOR**
- **COMPARATOR**
- **Binary to Gray Code Converter**
- **Gray to Binary Code Converter**
- **Binary to BCD Converter**
- **Parity Checkers**


The calculator takes two 1-bit binary inputs (A and B) and a control signal to determine the operation to perform. The output is the result of the selected Boolean operation.

## Design Methodology

1. **Specification and Requirements Analysis**:
   - Defined the supported operations and input/output configurations.
   - Established a control signal system to select the desired Boolean operation.

2. **High-Level Design**:
   - Structured the calculator into modular components, where each module corresponds to a Boolean operation.
   - Designed control logic to select the appropriate operation based on the input control signal.

3. **Implementation**:
   - Developed the Boolean calculator using Cadence software, focusing on digital logic gates and their interconnections to create the necessary operations.
   - Ensured efficient design and minimized delays using optimized gate-level architecture.

4. **Simulation and Testing**:
   - Simulated the Boolean calculator using Cadence tools to validate the correct functionality of each Boolean operation.
   - Tested the calculator with various input combinations to ensure it operates accurately.

5. **Optimization**:
   - Implemented strategies to optimize gate usage, reducing the propagation delay and enhancing performance.
   - Adjusted the design based on testing results to achieve efficient computation.

## Features
- **Modular Design**: Each Boolean operation is implemented as a separate module for clarity and maintainability.
- **Optimized Logic Path**: Enhanced performance by reducing the number of gates and optimizing signal paths.
- **Comprehensive Testing**: Validated the functionality and efficiency of the calculator through simulation.

## Tools and Technologies Used
- **EDA Tool**: Cadence Design Systems
- **Digital Logic Design**: Boolean algebra concepts and gate-level design

## Results and Discussions
- The Boolean calculator successfully performed all specified operations accurately with optimized timing and resource utilization.
- Simulation results verified the correctness and efficiency of each Boolean operation under various conditions.

## Learning Outcomes
1. Gained a comprehensive understanding of digital design concepts, including Boolean algebra and logic gates.
2. Developed skills in using Cadence software for digital logic implementation and simulation.
3. Practiced simulation techniques to verify the functionality and optimize the design for performance.

## How to Use the Calculator
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/Boolean-Algebra-Calculator.git
