# Implement-and-Analyze-different-types-of-64-bit-adders

The purpose of this project is to implement, optimize and analyze performance of 4 different implementations of 64-bit adders: 

(1) Ripple-Carry-Adder (RCA), 

(2) Carry-Look-Ahead (CLA- 2L) with 4-bit groups and 2-level P-G generator, 

(3) Carry Selected Adder (CSA-EQG) with 4- bit groups and,

(4) Carry Selected Adder (CSA-UEQG) with unequal-bit groups for highest speedup.

## Overview of Adders

* Each adder will take 1 clock to complete the calculation. Analysis is performed in details for timing and area.

* Circuit Interface: The exact interface ports of all adder circuits must be as below: 
1. op1[63:0]
2. op2[63:0]
3. sum [63:0]
4. crout 
5. clock 
6. reset
