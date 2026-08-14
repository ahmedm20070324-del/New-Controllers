# Working of Controllers
## 1.TM1637 Quad Seven-Segment Display Controller

A bare-metal C++ implementation and Wokwi simulation for controlling a 4-digit 7-segment display driven by the **TM1637** chip.

---

### 🚀 Overview

This project implements low-level hardware control and timing logic for a 4-digit TM1637 display counter without relying on bulky external libraries. The source folder includes a full **Wokwi circuit configuration** (`diagram.json`) alongside the application code for immediate simulation.

#### ✨ Highlights
* **4-Digit Counter Logic:** Custom bit-banging protocol for clock (`CLK`) and data (`DIO`) lines.
* **Embedded Wokwi Configuration:** `diagram.json` is located directly inside the code directory for seamless running on Wokwi or VS Code.
