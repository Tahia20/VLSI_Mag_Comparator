# 2-Bit Magnitude Comparator using Cadence Virtuoso

This repository presents the design and analysis of a **2-bit magnitude comparator**, implemented using both logic-level and transistor-level approaches. The project follows a complete VLSI design flow, from functional verification to physical layout and post-layout simulation.

## Overview

The comparator takes two 2-bit inputs (A and B) and produces three outputs:

* **A > B**
* **A = B**
* **A < B**

The design is validated to ensure correct logical behavior and efficient performance.

##  Tools Used

* **Logisim Evolution** – Logic design and truth table verification
* **Cadence Virtuoso** – Schematic and layout design
* **Spectre Simulator** – Circuit simulation and analysis

##  Key Work

* Designed and verified logic circuit using basic gates
* Implemented CMOS-based transistor-level schematic
* Developed full custom layout following design rules
* Performed **DRC** and **LVS** checks (zero errors)
* Conducted parasitic extraction and post-layout simulation

## Results

* Correct functionality across all input combinations
* Post-layout delay affected by parasitic elements (expected)
* Average power consumption:

  * Schematic: ~14.41 µW
  * Post-layout: ~13.73 µW
* Close agreement between schematic and extracted simulations

##  Learning Outcomes

* Digital logic and comparator design
* CMOS circuit implementation
* End-to-end VLSI workflow
* Performance analysis (delay, power, waveform behavior)

##  Author

**Tahia Tun Tuba**
CUET, Bangladesh

---

This project serves as a practical introduction to VLSI design, demonstrating how a simple digital circuit can be developed and analyzed at both logical and physical levels.
