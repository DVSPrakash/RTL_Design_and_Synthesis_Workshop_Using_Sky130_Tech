# RTL Design and Synthesis Workshop Using SKY130

The agenda of this workshop is to understand the RTL Design and Synthesis process in VLSI using various open-source tools. This process is where we provide the synthesis netlist to the Physical Design team. By the end of this workshop, we will be able to understand how logic conversion takes place from a simple verilog code written for any level of logic.

## Table of Contents

- [About This Workshop](#about-this-workshop)
- [Prerequisites](#prerequisites)
- [Workshop Structure](#workshop-structure)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## About This Workshop

This workshop is intended for students, hobbyists, and engineers who want to learn about:

- Verilog RTL design and simulation
- Using Icarus Verilog and GTKWave for simulation and waveform analysis
- Logic synthesis using Yosys and the SKY130 open-source PDK
- Key digital design concepts: testbenches, timing libraries, D flip-flop coding styles, and optimization techniques

---

## Prerequisites

- Basic understanding of digital logic (gates, flip-flops, multiplexers, etc.)
- Familiarity with Linux shell commands
- A Linux environment (or WSL on Windows/macOS)
- Tools: `git`, `iverilog`, `gtkwave`, `yosys`, and a text editor
- 
## DAY 1: Introduction to Verilog RTL design and Synthesis
    L1 - Learn about open-source simulator "iverilog"
    L2 - Start with Yosys and Sky130 PDKs


## DAY 2: Timing libs, hierarchical vs flat synthesis and efficient flop coding styles
    L1 - Understanding timing .libs
    L2 - Hierarchical vs Flat Synthesis
    L3 - Various Flop Coding Styles and Optimization


## DAY 3: Combinational and sequential optimizations
    L1 - Introduction to optimizations
    L2 - Combinational logic optimizations
    L3 - Sequential logic optimizations
    L4 - Sequential optimizations for unused outputs


## DAY 4: GLS, blocking vs non-blocking and Synthesis-Simulation mismatch
    L1 - GLS blocking vs non-blocking and Synthesis-Simulation mismatch statements


## DAY 5: Optimization in synthesis
    - If Case constructs
    - Incomplete If Case constructs
    - Incomplete Overlapping Case constructs
    - For loop and for generate
