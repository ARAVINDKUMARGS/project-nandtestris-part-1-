# project-nandtestris-part-1-
project 1to 6

# 🖥️ Nand2Tetris — Projects 1 to 6

### *Complete Overview + README Description*

This repository contains my solutions for **Projects 1 to 6** from the **Nand2Tetris Course (The Elements of Computing Systems)**.
Each project builds a different layer of a modern computer — from logic gates to machine code execution.

---

## 📁 Project Overview

### **🧩 Project 1 — Boolean Logic**

Build basic logic gates purely using NAND gates.

**Includes:**

* `And.hdl`
* `Or.hdl`
* `Not.hdl`
* `Xor.hdl`
* `Mux.hdl`
* `DMux.hdl`
* Truth tables and test scripts

**Goal:** Understand the fundamental building blocks of all hardware.

---

### **⚡ Project 2 — Boolean Arithmetic**

Construct adders and ALU components.

**Includes:**

* `HalfAdder.hdl`
* `FullAdder.hdl`
* `Add16.hdl`
* `Inc16.hdl`
* `ALU.hdl`

**Goal:** Build the full 16-bit ALU for arithmetic and logical operations.

---

### **🧮 Project 3 — Sequential Logic**

Design memory elements using flip-flops.

**Includes:**

* `Bit.hdl`
* `Register.hdl`
* `RAM8.hdl`
* `RAM64.hdl`
* `PC.hdl`

**Goal:** Build registers, RAM units, and the program counter.

---

### **💾 Project 4 — Machine Language Programming (Hack ASM)**

Write low-level assembly programs for the Hack architecture.

**Includes:**

* `mult.asm` (multiplication program)
* `fill.asm` (screen fill program)

**Goal:** Learn instruction-level programming and CPU flow control.

---

### **⚙️ Project 5 — Computer Architecture**

Build the CPU, Memory, and the complete Hack Computer.

**Includes:**

* `CPU.hdl`
* `Memory.hdl`
* `Computer.hdl`

**Goal:** Construct a fully functioning computer capable of executing the programs from Project 4.

---

### **🕹️ Project 6 — Assembler**

Build an assembler that converts `.asm` programs to `.hack` machine code.

**Includes:**

* `Add.hack`
* `Max.hack`
* `Rect.hack`
* `Pong.hack`
* `Add.asm`, `Max.asm`, etc.
* `Project6.py` / `assembler.c` (depends on implementation)

**Goal:** Convert assembly instructions to binary machine code according to the Hack instruction set.

---

## 📦 Files Included

```
Project01/
Project02/
Project03/
Project04/
Project05/
Project06/
README.md
LICENSE

## 🚀 How to Use

1. Clone the repository

   ```
   git clone https://github.com/ARAVINDKUMARGS/nand2tetris-projects.git
   ```
2. Open the **Hardware Simulator** / **VM Emulator** / **CPU Emulator** from Nand2Tetris tools.
3. Load `.hdl`, `.asm`, or `.hack` files to test and run programs.

## 📜 License

MIT License — feel free to use for learning purposes.
