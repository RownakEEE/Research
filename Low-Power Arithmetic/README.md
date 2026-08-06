# Low-Power Arithmetic

This project explores energy-efficient arithmetic architectures for low-precision vector computing and AI accelerators. The work focuses on reducing the area and power overhead of arithmetic units while maintaining predictable and scalable hardware execution.

A precompute–reuse nibble multiplier is developed using compact shift-and-add logic to reuse structured partial computations. The architecture provides an efficient design point between highly sequential multipliers and hardware-intensive single-cycle multiplier structures.

## Research Highlights

- **Logic-Reuse Arithmetic:** Nibble-level precompute and reuse for efficient low-precision multiplication.
- **Vector Computing:** Architecture designed for replicated vector-scalar multiplier datapaths.
- **Low-Power Design:** Reduced switching and hardware complexity using localized shift-and-add computation.
- **Architecture Comparison:** Evaluation against shift-add, Booth, Wallace-tree, and LUT-based array multipliers.
- **RTL & ASIC Evaluation:** Synthesizable RTL implementation and standard-cell synthesis in TSMC 28 nm.
- **Scalable Design:** Evaluation across 4-, 8-, and 16-operand vector configurations.

## Tools & Technologies

`Verilog` `RTL Design` `Digital Arithmetic` `ASIC Design` `Cadence EDA`
`TSMC 28 nm` `Logic Synthesis` `Low-Power Design` `Vector Computing`

## Publications

| | Publication | Link |
|---|---|---|
| **Paper 1** | A Logic-Reuse Approach to Nibble-based Multiplier Design for Low Power Vector Computing | [**Paper ↗**](https://arxiv.org/pdf/2602.19007) |

## Code

RTL implementations, verification testbenches, synthesis scripts, and hardware evaluation resources are maintained in the project repository.

[**View Code →**](CODE-LINK)

## Keywords

`Digital Arithmetic` `Multiplier Architecture` `Low-Power Computing`
`Vector Processing` `AI Accelerators` `RTL Design`
`ASIC Design` `Logic Reuse` `Low-Precision Computing`
