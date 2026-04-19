# NAND-to-Computer: A First-Principle Computer Build
   
  This project implements the hardware layers of a computer, following the Nand2Tetris(https://www.nand2tetris.org/) course. Starting from a single NAND gate, each chapter builds on the last — culminating in
     a fully functional computer.
   
  All hardware is written in HDL (a simplified Verilog).
   
  ## Project Structure
   
   ### 01 — Boolean Logic
  
   Elementary logic gates, all built from the primitive NAND gate.

   Chips:
   
  Not, And, Or, Xor, Mux, DMux, Not16, And16, Or16, Or8Way, Mux16, Mux4Way16, Mux8Way16, DMux4Way, DMux8Way

  
   ### 02 — Boolean Arithmetic
  
 Adders and the ALU, built from the gates in chapter 01.

 Chips:

 HalfAdder, FullAdder, Add16, Inc16, ALU
  

  
   ### 03 — Memory
  
   Memory elements, from a single bit up to 16K RAM.

   Chips:
   
  Bit, Register, RAM8, RAM64, RAM512, RAM4K, RAM16K, PC
   
  
   ### 04 — Machine Language
  
  Assembly.
  
   
  
   ### 05 — Computer Architecture
  
   The complete computer, assembled from all previous chapters.

   Chips:
   
   CPU, Memory, Computer
  
   
  
   ## How to Run
  
   Load any `.hdl` file (or `.asm` for chapter 04) into the [Nand2Tetris Hardware Simulator](https://www.nand2tetri
     s.org/software) and run the corresponding `.tst` test script.
