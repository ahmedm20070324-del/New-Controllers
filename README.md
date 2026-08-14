# Working of Controllers

A collection of bare-metal and C++ implementations for controlling display drivers, hardware modules, and microcontrollers.

---

## 🚀 Projects Included

### 1. TM1637 Quad Seven-Segment Display

A low-level, bare-metal C++ implementation to interface with and control a 4-digit 7-segment display driven by the **TM1637** chip.

#### 📌 Overview
This module demonstrates low-level hardware control without relying on bulky external libraries. Key highlights include:
* **Bit-Banging Protocol:** Custom timing sequences for `CLK` (Clock) and `DIO` (Data Input/Output) lines.
* **Register Manipulation:** Efficient signal toggling for precise display refresh rates.
* **Counter Implementation:** 4-digit numerical counting logic with digit decoding and display control.
