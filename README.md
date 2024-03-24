# Doctoral Dissertation: Design of Networks-on-Chip (NoCs) on FPGAs

This repository contains the doctoral dissertation PDF that explores the design of networks-on-chip (NoCs) on field-programmable gate arrays (FPGAs), specifically focusing on the development and implications of the RingNet architecture and communication protocol.

## Abstract

In the dissertation, the problems related to the design of networks-on-chip (NoCs) on field-programmable gate arrays (FPGAs) are considered in the context of typical features of FPGAs manufactured by leading vendors. As a result of these considerations, the RingNet architecture and communication protocol are proposed with the aim to exploit the specific potential of FPGA devices as much as possible. Although a few FPGA-oriented NoCs have been proposed so far, the RingNet design is likely the most determinedly adapted to typical FPGA resources and their architectures. The specific features of RingNet include: communication exclusively through system memory (large SDRAM or block RAM), control over traffic load executed by the processing elements, FPGA-optimized 3-port switches organized into the tree-of-rings topology, distributed memory (LUTRAM) used as small buffers in the switches, and virtual cut-through switching. In the dissertation, it is demonstrated that RingNet offers guaranteed throughput, predictable latency, and fair network access. The synthesis results demonstrate that RingNet implementations are efficient in terms of maximum clock frequency and resource consumption for flagship FPGA devices from major manufacturers. As compared to the widely-accepted state-of-the-art interconnection architecture AXI4 Interconnect, RingNet implementations demonstrate higher maximum clock frequency and lower resource consumption. Therefore, the author believes that the RingNet NoC architecture and protocol may be widely adopted in FPGA-based SoC designs, especially in high-volume data processing applications, such as video processing.

## Presentation

The dissertation was presented in December 2019.

## Reviewers

1. **Prof. Dr. Hab. Inż. Edward Hrynkiewicz**, Electronics, and Computer Science, Silesian University of Technology;
2. **Prof. Dr. Diana Goehringer**, Technische Universität Dresden, Chair of Adaptive Dynamic Systems.

## Supervisor

The dissertation was supervised by **Prof. Dr. Hab. Inż. Marek Domański**.

## Distinction

The dissertation was defended with distinction.
