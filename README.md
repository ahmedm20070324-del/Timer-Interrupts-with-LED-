# Timer Interrupts with LED

A microcontroller project demonstrating how to use **Hardware Timer Interrupts** to toggle an LED at precise intervals without using blocking delay functions (like `delay()`).

---

## 📌 Project Overview

In embedded systems, using blocking delays pauses the CPU and prevents it from executing other tasks. This project demonstrates how to configure **Timer Interrupts** and write an **Interrupt Service Routine (ISR)** to handle LED toggling periodically while keeping the main loop free for execution.

---

## ✨ Features

* **Non-blocking Execution:** Frees up the main program loop (`void loop()`) for parallel tasks.
* **Precise Timing:** Uses hardware timers for exact timing intervals.
* **Low Power & Efficient:** Efficient resource utilization suitable for real-time systems.
