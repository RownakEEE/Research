# InTuiT: Architecture-Aware AI Workload Mapper

**InTuiT** is an architecture-aware mapping, scheduling, and performance evaluation framework for neural-network workloads targeting spatial AI accelerators. The framework translates workload characteristics and hardware constraints into executable mapping strategies for efficient utilization of accelerator resources.

The research spans **workload decomposition, convolution mapping, spatial and temporal scheduling, memory-aware execution, analytical performance modeling, and systematic profiling** of AI accelerator architectures.

---

## Research Highlights

- **Architecture-Aware Mapping** — Maps neural-network workloads according to configurable accelerator dimensions, compute resources, and architectural constraints.
- **Convolution Mapping** — Specialized mapping strategies for pointwise, depthwise, and standard convolution operations.
- **Mapping & Scheduling** — Spatial and temporal workload organization for efficient execution and resource utilization.
- **Memory-Aware Execution** — Models data placement, reuse, movement, and memory constraints during workload execution.
- **Performance Profiling** — Analytical evaluation of utilization, execution cycles, communication, data movement, and hardware-resource requirements.
- **Design-Space Analysis** — Supports sensitivity and scalability studies across workload and accelerator configurations.

---

## Tools & Technologies

`Python` `NumPy` `AI Workload Mapping` `CNN Inference`  
`Performance Modeling` `Mapping & Scheduling` `Memory Modeling`  
`Design-Space Exploration` `Hardware–Software Co-design`

---

## Publications

| # | Publication | Link |
|:--:|---|:--:|
| **1** | **Hardware-Aware Data and Instruction Mapping for AI Tasks: Balancing Parallelism, I/O and Memory Tradeoffs** | [Paper ↗](https://arxiv.org/abs/2509.03846) |
| **2** | **Demystifying the 7-D Convolution Loop Nest for Data and Instruction Streaming in Reconfigurable AI Accelerators** | [Paper ↗](https://arxiv.org/abs/2507.20420) |
| **3** | **InTuiT: A Novel Algorithmic Approach for Neural Network Mapping onto a Data and Instruction Streamable AI Accelerator** | *In Progress* |
| **4** | **Memory-Aware Scheduling of AI Workloads on a Messaging-Based Vector Processing Unit** | *Under Review* |

---

## Code

The mapping algorithms, workload models, profiling tools, and evaluation framework are organized into two primary workload-mapping components.

| Component | Description |
|---|---|
| **InTuiT GEMM** | Architecture-aware mapping and performance evaluation for GEMM workloads. |
| **InTuiT CNN** | Architecture-aware mapping and performance evaluation for convolutional neural-network workloads. |

[**InTuiT Mapper (Private) →**](https://github.com/RownakEEE/MAVeC-Code)

---

## Keywords

`Computer Architecture` `AI Accelerators` `Neural Network Mapping`  
`Mapping & Scheduling` `CNN Inference` `Memory-Aware Computing`  
`Performance Modeling` `Design-Space Exploration` `Hardware–Software Co-design`
