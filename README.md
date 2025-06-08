# Synchronous FIFO in Verilog

This project implements a parameterized synchronous FIFO (First-In First-Out) memory in Verilog, along with a comprehensive testbench covering all edge cases.

## 🔧 Features
- Parameterizable `DEPTH` and `WIDTH`
- Synchronous read and write with single clock
- Flags for `full`, `empty`
- Handles wrap-around logic correctly
- Detects and handles overflow & underflow conditions
- Includes reset functionality

## 📁 File Structure
- `fifo.v` – RTL design of the FIFO
- `tb_fifo.v` – Testbench with tasks for:
  - Write operation
  - Read operation
  - Full & Empty conditions
  - Wrap-around
  - Simultaneous read-write
  - Overflow & Underflow
  - Reset behavior

