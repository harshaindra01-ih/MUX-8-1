# MUX-8-1
 writing a verilog code for mux of 8 : 1 using edaplayground 
# 8-to-1 Multiplexer using Verilog HDL

## 📌 Project Description
This project implements an **8-to-1 Multiplexer (MUX)** using Verilog HDL.

A multiplexer is a combinational logic circuit that selects one input from multiple inputs and forwards it to a single output based on the select lines.

## ⚙️ Specifications
- **Number of Inputs:** 8
- **Number of Select Lines:** 3
- **Number of Outputs:** 1
- **Design Type:** Behavioural Modelling
- **HDL:** Verilog

## 🔧 Working Principle
An 8-to-1 MUX has eight data inputs (a[7:0]), three select lines (s[2:0]), and one output (y).

The select lines determine which input is connected to the output.

| Select Lines | Selected Input |
|---|---|
| 000 | a[0] |
| 001 | a[1] |
| 010 | a[2] |
| 011 | a[3] |
| 100 | a[4] |
| 101 | a[5] |
| 110 | a[6] |
| 111 | a[7] |

## 💻 Design Implementation
The design is implemented using:
- `always @(*)` block
- `case` statement
- Behavioural modelling

## 🧪 Testbench
A Verilog testbench is used to verify the functionality of the multiplexer.

**Input Data:** `8'b01010110`

All eight select-line combinations are tested to verify the output.

## 📊 Expected Simulation Results

| Select | Output |
|---|---|
| 000 | 0 |
| 001 | 1 |
| 010 | 1 |
| 011 | 0 |
| 100 | 1 |
| 101 | 0 |
| 110 | 1 |
| 111 | 0 |

## 🛠️ Tools Used
- Verilog HDL
- EDA Playground
- Icarus Verilog 12.0

## 🎯 Learning Outcomes
- Understanding the working of an 8-to-1 multiplexer.
- Learning behavioural modelling in Verilog.
- Using `case` statements in combinational circuits.
- Writing and verifying a testbench.
- Understanding simulation results.

## 👨‍💻 Author
**Harsha**

Electronics and Communication Engineering (ECE)

## Conclusion
Successfully designed and simulated an 8-to-1 Multiplexer using Verilog HDL and verified its functionality through a testbench.
