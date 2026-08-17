# Half Adder

A Half Adder is a combinational circuit that adds two 1-bit binary inputs.
It produces two outputs: **Sum** and **Carry**.

## Inputs

* A
* B

## Outputs

* Sum
* Carry

## Logic

* Sum = A XOR B
* Carry = A AND B

## Truth Table

| A | B | Sum | Carry |
| - | - | --- | ----- |
| 0 | 0 | 0   | 0     |
| 0 | 1 | 1   | 0     |
| 1 | 0 | 1   | 0     |
| 1 | 1 | 0   | 1     |

## Files

* `half_adder.v` - Verilog code for Half Adder
* `half_adder_tb.v` - Testbench
* `expected_output.txt` - Expected simulation output

## Tools

* Verilog
* Icarus Verilog / Vivado / ModelSim
