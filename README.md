# 4x4 DRAM Design Project

A comprehensive VLSI design project focusing on the implementation, simulation, and analysis of a *4x4 Dynamic Random-Access Memory (DRAM)* system. 

## 📂 Project Structure

* *Circuits/* - Contains all LTspice schematic (.asc) and symbol (.asy) files for the system blocks.
* *Circuits.zip* - Compressed archive containing a snapshot of all circuit components.
* *VLSI_DESIGN_PROJECT.docx / .pdf* - Detailed engineering reports, design specifications, and simulation analysis.

## 🛠️ System Components Included

The repository tracks the structural design of the following core VLSI components:
* *4x4 DRAM Core Array* - The main memory storage cell matrices.
* *DRAM Controller & Controls* - Timing logic and control circuitry for read/write routing.
* *Sense Amplifiers* - Circuitry for signal amplification during data retrieval.
* *D-Flip Flops (DFF with Controls)* - Control logic memory registers.
* *Mod5 Counter* - Sequential logic counter utilized for addressing steps.
* *Multiplexers (4x1 MUX / 2x1 MUX)* - Data selection networks.

## 🚀 How to Run the Simulations

1. Clone this repository to your local machine.
2. Ensure you have *LTspice* installed.
3. Open any .asc schematic file located inside the Circuits/ subdirectories.
4. Run the simulation directly inside LTspice (simulation log outputs like .raw and .log are automatically ignored to keep the workspace clean).
