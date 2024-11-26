# Verilog Code for Logic Gates and Multiplexers

## Overview

This repository contains Verilog code that implements various digital circuits including logic gates, multiplexers, and full adders. The modules cover both basic and advanced components, focusing on the use of multiple bit-width inputs and logic operations. The code also includes examples of logic gates with delays and the implementation of full adders using nonblocking assignments.

## Modules Implemented

- **Logic Gates using 2 4-bit Numbers**  
  Implements common logic gates (AND, OR, XOR, etc.) using two 4-bit input numbers.

- **8-bit AND Gate**  
  Performs a bitwise AND operation on a single 8-bit input.

- **2:1 Multiplexer (MUX) for Two 4-bit Inputs**  
  A 2-to-1 multiplexer that selects between two 4-bit inputs based on a control signal.

- **4:1 Multiplexer (MUX) for Four 4-bit Inputs**  
  A 4-to-1 multiplexer that selects between four 4-bit inputs based on two control signals.

- **Full Adder**  
  Implements a Full Adder for adding two 1-bit inputs along with a carry-in, producing a sum and carry-out.

- **N-bit Multiplexers**  
  Implements multiplexers that can handle N-bit inputs, adaptable for different bit-width configurations.

- **N-bit AND Gate**  
  A bitwise AND gate for N-bit input values, useful for larger bit-width operations.

- **Full Adder Using Nonblocking Assignments**  
  Implements the Full Adder using nonblocking assignments, enabling more efficient simulation and synthesis.

- **Logic Gates with Delay**  
  Implements AND, OR, and NOT gates with configurable delays, useful for simulating real-world timing behavior.
