# Geometric Sequence Generator in Mano Assembly

Developed for the **Computer Architecture** course, this repository contains a low-level Assembly program written for the **Mano 16-bit Basic Computer Simulator**. The program computes and stores the first 10 elements of a geometric sequence in memory.

---

## Algorithmic Highlights

* **Software-Emulated Multiplication:** Because the baseline Mano CPU instruction set lacks a native hardware multiplication instruction (`MUL`), multiplication is implemented at the algorithmic level using nested iterative addition loops and two's-complement counter tracking.
* **Memory & Pointer Management:** Utilizes indirect addressing and dedicated memory pointers to sequentially store each computed term of the geometric progression in RAM.
* **Flow Control:** Uses conditional branching (`BSA`, `ISZ`, `BUN`, `SPA`/`SNA`) to manage loop termination and accumulator state.

---

## Repository Contents
* **Assembly Source Code (`.asm`):** Fully commented Mano Assembly implementation.
* **Software Documentation:** Detailed breakdown of the memory map, flowchart, register allocation, and simulator trace results.

---

## Authors
* **Noam Hayu**
* **Sharbel Marshi**
