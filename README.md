# 8-bit-ALU_Verilog

Simple 8 bit ALU implementation using Verilog.
Created and tested on Intel FPGA ModelSim

A working testbench module is also added.

Basic operations are: 

|ALU_Sel|   ALU Operation

| 0000  |   ALU_Out = A + B;

| 0001  |   ALU_Out = A - B;

| 0010  |   ALU_Out = A * B;

| 0011  |   ALU_Out = A / B;

| 0100  |   ALU_Out = A << 1;

| 0101  |   ALU_Out = A >> 1;

| 0110  |   ALU_Out = A rotated left by 1;

| 0111  |   ALU_Out = A rotated right by 1;

| 1000  |   ALU_Out = A and B;

| 1001  |   ALU_Out = A or B;

| 1010  |   ALU_Out = A xor B;

| 1011  |   ALU_Out = A nor B;

| 1100  |   ALU_Out = A nand B;

| 1101  |   ALU_Out = A xnor B;

| 1110  |   ALU_Out = 1 if A>B else 0;
| 1111  |   ALU_Out = 1 if A=B else 0;
