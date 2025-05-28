---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: e19-4yp-RISC-V-Based-ASIP-for-Accelerating-DNA-Sequence-Alignment-on-Embedded-Systems
title: Designing a RISC-V Based ASIP for Accelerating Third-Generation DNA Sequence Alignment on Embedded Systems
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# Designing a RISC-V Based ASIP for Accelerating Third-Generation DNA Sequence Alignment on Embedded Systems

#### Team

- E/19/057, Chamath Colombage, [email](mailto:e19057@eng.pdn.ac.lk)
- E/19/453, Akash Withanaarachchi, [email](mailto:e19453@eng.pdn.ac.lk)
- E/17/083, Mahela Ekanayake, [email](mailto:e17083@eng.pdn.ac.lk)

#### Supervisors

- Prof. Roshan Ragel, [email](mailto:roshanr@eng.pdn.ac.lk)
- Dr. Isuru Nawinne, [email](mailto:isurunawinne@eng.pdn.ac.lk)

#### Table of content

1. [Abstract](#abstract)
2. [Related works](#related-works)
3. [Methodology](#methodology)
4. [Experiment Setup and Implementation](#experiment-setup-and-implementation)
5. [Results and Analysis](#results-and-analysis)
6. [Conclusion](#conclusion)
7. [Publications](#publications)
8. [Links](#links)

---

<!-- 
DELETE THIS SAMPLE before publishing to GitHub Pages !!!
This is a sample image, to show how to add images to your page. To learn more options, please refer [this](https://projects.ce.pdn.ac.lk/docs/faq/how-to-add-an-image/)
![Sample Image](./images/sample.png) 
-->


## Abstract

This project explores the design and implementation of a RISC-V-based Application-Specific Instruction-set Processor (ASIP) to accelerate DNA sequence alignment for embedded systems. By focusing on the computationally intensive chaining stage of Minimap2, the project aims to achieve real-time, energy-efficient processing for third-generation DNA sequencing technologies.

---

## Related works

The project builds upon existing research in DNA sequence alignment, hardware acceleration, and RISC-V-based processor design. Key references include:

- Minimap2: A widely used tool for long-read DNA sequence alignment.
- Studies on hardware acceleration for genomics using FPGA and ASIC platforms.
- Open-source RISC-V ISA and its applications in custom processor design.

---

## Methodology

1. **Performance Analysis**: Profiling Minimap2 to identify bottlenecks in the chaining stage.
2. **ASIP Design**: Developing a custom co-processor using the RISC-V Rocket Chip platform and RoCC interface.
3. **Simulation and Testing**: Verifying the ASIP design using simulation tools and benchmarking its performance.
4. **Integration**: Incorporating the ASIP into an embedded system for real-world testing.

---

## Experiment Setup and Implementation

- **Hardware**: RISC-V Rocket Chip platform with RoCC interface.
- **Software**: Minimap2, Verilog/Chisel for hardware design, and Linux for embedded system testing.
- **Tools**: Simulation tools for performance evaluation and FPGA for prototyping.

---

## Results and Analysis

- **Performance Gains**: Preliminary results indicate significant speedup in the chaining stage of Minimap2.
- **Energy Efficiency**: The ASIP design demonstrates reduced power consumption compared to traditional processors.
- **Scalability**: The approach is scalable to other stages of DNA sequence alignment.

---

## Conclusion

The project successfully demonstrates the feasibility of using a RISC-V-based ASIP to accelerate DNA sequence alignment on embedded systems. Future work includes extending the design to other stages of Minimap2 and deploying the solution on FPGA for real-world applications.

---

## Publications
[//]: # "Note: Uncomment each once you uploaded the files to the repository"

<!-- 1. [Semester 7 report](./) -->
<!-- 2. [Semester 7 slides](./) -->
<!-- 3. [Semester 8 report](./) -->
<!-- 4. [Semester 8 slides](./) -->
<!-- 5. Author 1, Author 2 and Author 3 "Research paper title" (2021). [PDF](./). -->


## Links

[//]: # ( NOTE: EDIT THIS LINKS WITH YOUR REPO DETAILS )

- [Project Repository](https://github.com/cepdnaclk/e19-4yp-RISC-V-Based-ASIP-for-Accelerating-DNA-Sequence-Alignment-on-Embedded-Systems)
- [Project Page](https://cepdnaclk.github.io/e19-4yp-RISC-V-Based-ASIP-for-Accelerating-DNA-Sequence-Alignment-on-Embedded-Systems/)
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)

[//]: # "Please refer this to learn more about Markdown syntax"
[//]: # "https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet"
