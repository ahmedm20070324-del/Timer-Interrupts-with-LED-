# Timer Interrupts with LED ⏱️💡

A microcontroller project demonstrating how to configure **Hardware Timer Interrupts** to toggle two LEDs at precise intervals without blocking delay functions (`delay()`). It features flexible dynamic control modes to interchange and adjust LED timing intervals using either a single pushbutton or a set of five pushbuttons.

## 📌 Project Overview

In embedded systems, using blocking delays pauses the CPU, preventing it from executing other tasks or responding to user inputs. This project configures hardware timers and writes **Interrupt Service Routines (ISRs)** to handle multi-LED toggling periodically in the background while keeping the main loop completely free for parallel execution.

## ✨ Key Features

* **Non-Blocking Execution:** Frees up the main program loop (`void loop()`) for parallel background tasks.
* **Precise Hardware Timing:** Uses hardware timer registers for accurate, jitter-free intervals.
* **Dual-LED Timing Control:** Interchanges timing intervals between two independent LEDs seamlessly.
* **Flexible Pushbutton Modes:**
  * **1-Pushbutton Mode:** Swap/interchange timing parameters between the two LEDs instantly with a single button press.
  * **5-Pushbutton Mode:**Swap/interchange timing parameters between the two LEDs instantly with a five button press each time.
* **Power & Resource Efficient:** Built specifically for real-time systems and event-driven architecture.
