# Accelerating Minimap2 on Embedded Systems Using RISC-V Based ASIP

This repository accompanies the literature review and ongoing research into optimizing **Minimap2**, a widely used DNA sequence alignment tool, for **embedded systems** through the use of **RISC-V-based Application-Specific Instruction-set Processors (ASIPs)**. The project explores hardware acceleration of Minimap2's **chaining stage** using a custom co-processor integrated into the **Rocket Chip platform** via the **RoCC (Rocket Custom Coprocessor) interface**.

---

## 🧬 Motivation

Third-generation DNA sequencing technologies, such as **Oxford Nanopore MinION**, enable portable real-time sequencing of long reads. While these technologies offer advantages in genome completeness and accuracy, they also pose serious **computational challenges**, particularly for **real-time and on-site processing**.

Minimap2 is considered the gold-standard tool for long-read alignment but is computationally demanding—especially its **chaining stage**. Most optimization efforts so far have targeted **HPC systems**. There's a lack of research into accelerating Minimap2 on **embedded platforms** where **energy-efficiency and hardware constraints** are critical.

This project aims to fill that gap.

---

## 🎯 Objectives

- Review computational challenges in long-read DNA sequence alignment.
- Identify performance bottlenecks in Minimap2, particularly in the chaining stage.
- Explore hardware acceleration strategies for embedded systems using RISC-V.
- Design and simulate an ASIP via the RoCC interface to accelerate chaining.
- Evaluate performance improvements and resource utilization.

---

## 🛠️ Technologies Used

| Technology         | Description                                                 |
|--------------------|-------------------------------------------------------------|
| **Minimap2**       | Long-read sequence aligner (baseline software)              |
| **RISC-V**         | Open ISA used for designing a custom ASIP                   |
| **Rocket Chip**    | RISC-V SoC generator with RoCC interface                    |
| **RoCC**           | Custom co-processor interface in Rocket Chip                |
| **Verilog / Chisel** | HDL/DSL used for ASIP design                              |
| **FPGA / Simulation** | Optional future implementation for prototyping           |
| **Linux / Ubuntu** | Target OS for embedded simulation and profiling             |

---

## 🗂️ Repository Structure

```bash

├── docs/                  # Literature review, architecture diagrams, and references
├── minimap2/              # Original or modified Minimap2 source code
├── hardware/              # Custom ASIP implementation (Verilog/Chisel)
│   ├── rocc_accelerator/  # RoCC-based co-processor code
│   └── testbenches/       # Simulation and verification files
├── results/               # Benchmarking, profiling, and performance graphs
├── scripts/               # Scripts for simulation, compilation, and data generation
├── LICENSE
└── README.md

---

## 📌 Current Status

- ✅ Literature review completed  
- ✅ Performance bottleneck identified: chaining stage in Minimap2  
- ⚙️ ASIP design under development  
- 🔄 Integration with Rocket Chip via RoCC pending  
- 📊 Benchmarking and validation planned  

---

## 📈 Future Work

- Integrate ASIP with Rocket Chip SoC  
- Profile energy and latency on embedded simulations  
- Port to FPGA for real-world prototyping  
- Extend support to more stages in Minimap2 (seeding, alignment)  
- Publish findings in a peer-reviewed venue  

---

## 📚 References

- [Minimap2: Pairwise alignment for long DNA sequences](https://doi.org/10.1093/bioinformatics/bty191)
- [Oxford Nanopore Technologies](https://nanoporetech.com/)
- [Rocket Chip Generator](https://github.com/chipsalliance/rocket-chip)
- Literature cited in the `docs/` folder

---

## 🤝 Contributing

If you're interested in computational genomics, RISC-V hardware design, or embedded bioinformatics applications, feel free to contribute!

---

## 🧠 Acknowledgments

This research is conducted as part of ongoing academic efforts in **computational bioengineering** and **hardware-software co-design for genomics**.
