# Timer Interrupts with LED ⏱️💡

A microcontroller project demonstrating how to configure **Hardware Timer Interrupts** to toggle an LED at precise intervals without using blocking delay functions (like `delay()`), as well as dynamically adjusting timing intervals using 5 pushbuttons.

---

## 📌 Project Overview

In embedded systems, using blocking delays pauses the CPU, preventing it from executing other tasks or responding to user input. This project demonstrates how to configure hardware timers and write an **Interrupt Service Routine (ISR)** to handle LED toggling periodically in the background while keeping the main loop completely free for execution.

---

## ✨ Features

* **Non-Blocking Execution:** Frees up the main program loop (`void loop()`) for parallel tasks.
* **Precise Hardware Timing:** Uses hardware timer registers for accurate, jitter-free intervals.
* **Dynamic Frequency Control:** Adjust toggle timing intervals on the fly using **5 pushbuttons**.
* **Power & Resource Efficient:** Ideal for real-time systems and event-driven architecture.
