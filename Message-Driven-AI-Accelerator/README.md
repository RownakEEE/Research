# MAVeC: Message-Driven AI Accelerator

**MAVeC (Messaging-based Adaptive Vector Computing)** is a programmable accelerator architecture designed for AI and data-intensive workloads. Instead of relying on centralized scheduling or rigid dataflows, MAVeC uses distributed compute elements and self-propagating messages that carry both data and control information, enabling computation, communication, and routing to be orchestrated directly within the hardware fabric.

The research spans **accelerator architecture, message-driven execution, workload mapping, hierarchical memory organization, data orchestration, and hardware-aware performance modeling** for matrix operations, convolutional neural networks, and data-intensive workloads.

---

## Research Highlights

- **Message-Driven Architecture** — Distributed execution model where messages encode operands, operations, and destinations for runtime-programmable computation.
- **AI Workload Execution** — Mapping and execution strategies for matrix operations and convolution using spatial data movement, reuse, and pipelined execution.
- **Memory & Data Orchestration** — Hierarchical memory organization and data orchestration for improving locality, reuse, and parallelism.
- **Performance Modeling** — Analytical modeling of utilization, latency, throughput, data movement, and hardware-resource scaling.
- **Hardware Evaluation** — RTL simulation and ASIC-oriented evaluation of the architecture.
- **Applications** — Evaluation across matrix operations, CNN workloads, and PageRank-based protein-network analysis.

---

## Tools & Technologies

`Python` `Verilog` `RTL Design` `Xilinx Vivado` `Cadence EDA`  
`ASIC Design` `TSMC 28 nm` `Performance Modeling` `AI Workload Mapping`

---

## Publications

| # | Publication | Link |
|:--:|---|:--:|
| **1** | **Messaging-based Adaptive Vector Computing (MAVeC) Accelerator for AI Workloads** | [Paper ↗](https://arxiv.org/pdf/2410.09961) |
| **2** | **Implications of Memory Embedding and Hierarchy on the Performance of MAVeC AI Accelerators** | [Paper ↗](https://doi.org/10.1016/j.memori.2025.100131) |
| **3** | **Accelerating PageRank Algorithmic Tasks with a New Programmable Hardware Architecture** | [Paper ↗](https://doi.org/10.1109/ICRC64395.2024.10937012) |

---

## Code

The MAVeC research implementation is organized into separate hardware-design, workload-mapping, and evaluation components.

| Component | Description |
|---|---|
| **RTL** | RTL implementation and simulation of the MAVeC architecture. |
| **ASIC** | ASIC synthesis, implementation, and hardware evaluation flow. |
| **InTuiT GEMM** | Architecture-aware mapping and performance analysis for GEMM workloads. |
| **InTuiT CNN** | Mapping, scheduling, and evaluation framework for convolutional workloads. |

[**MAVeC Code Repository (Private) →**](https://github.com/RownakEEE/MAVeC-Code)

---

## Keywords

`Computer Architecture` `AI Accelerators` `Message-Driven Computing`  
`Reconfigurable Computing` `Hardware–Software Co-design` `Dataflow Architecture`  
`Mapping & Scheduling` `Memory Hierarchy` `Performance Modeling` `FPGA/ASIC`
