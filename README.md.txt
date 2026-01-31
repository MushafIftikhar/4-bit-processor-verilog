# 4-bit Simple Processor in Verilog

This project implements a simple 4-bit processor designed in Verilog and simulated using Xilinx Vivado. The processor includes:

- ALU (ADD, SUB, AND, OR operations)
- RAM module with 16 registers
- 4-bit Program Counter
- Clock module
- Testbench for simulation

## Files
- `src/` : All source Verilog files (Processor, ALU, RAM, etc.)
- `tb/` : Testbench for simulation

## How to Run
1. Open the project in Xilinx Vivado.
2. Add all source files.
3. Run the simulation using `SimpleProcessor_tb.v`.
4. Observe outputs: `alu_result`, `led_out`, `pc_out`.

## Author
Mushaf Iftikhar
