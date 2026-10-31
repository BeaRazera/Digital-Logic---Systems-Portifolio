[ Português ](README.pt-BR.md) | **English**

# Digital Logic & Systems Portfolio

A collection of digital logic and computer engineering projects developed using the **Falstad Circuit Simulator**, focusing on sequential counters and combinational decoders.

![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![Category](https://img.shields.io/badge/Category-Digital%20Electronics-blue?style=flat-square)

---

## Projects Overview

### 1. Sequential Counters (Falstad)
* **Description:** Implementation and simulation of digital sequential circuits using flip-flops.
* **Key Features:**
  - **Asynchronous Counter (3 to 10):** Built using four T flip-flops to sequence numbers from 3 to 10 and loop back.
  - **Synchronous Counter (3-bit):** Custom sequence (`7 -> 5 -> 2 -> 0 -> 1 -> 3 -> 4 -> 6 -> 7`) designed using JK flip-flops, excitation tables, and Karnaugh map simplifications.
  - **Ring Counter (Traffic Light Controller):** 15-state ring counter driven by a 10Hz clock ($T = 0.1s$) managing car and pedestrian traffic lights (Green: 0.8s, Yellow: 0.3s, Red: 0.4s).
* **Simulations:** [Asynchronous Counter](https://www.falstad.com/s.php?s=Xoo5gX) | [Synchronous Counter](https://www.falstad.com/s.php?s=4xMk7I) | [Ring Counter Traffic Light](https://www.falstad.com/s.php?s=WMHPkW)

### 2. Grade Concept Seven-Segment Decoder (Falstad)
* **Description:** Combinational logic circuit that reads a 4-bit binary input representing academic grades (0 to 15) and decodes them into conceptual letter grades on a 7-segment display.
* **Key Features:**
  - **Letter Mapping:** Decodes inputs into lowercase `d` (grades 0–3), uppercase `E` (4–5), uppercase `C` (6–7), lowercase `b` (8), uppercase `A` (9–10), and `I` for invalid inputs (11–15).
  - **Boolean Optimization:** Derived truth tables and minimized expressions using Karnaugh maps for all 7 display segments (`a` through `g`).
  - **Implementation:** Built using NOT, AND, and OR gates with active-high logic.
* **Simulation:** [Decoder Circuit](https://www.falstad.com/s.py?s=VoYGE5)

---

## Repository Structure

```text
.
├── README.md               # English documentation
└── README.pt-BR.md         # Portuguese documentation
