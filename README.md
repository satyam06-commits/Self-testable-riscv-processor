# Self-Testable RISC-V Processor Using Custom Test Instructions

A research project focused on improving processor reliability by enabling a RISC-V processor to perform self-testing before executing critical operations through the use of custom test instructions.

> **Note:** The RTL implementation is currently private as the project is under active research.

---

## Motivation

Modern processors are expected to operate reliably in safety-critical and mission-critical environments. Conventional testing techniques are primarily performed during manufacturing or require external test infrastructure, making periodic in-field validation challenging.

This project explores a mechanism that allows a processor to verify its own functionality before executing critical tasks by introducing dedicated self-test instructions into the RISC-V ISA.

---

## Project Overview

The proposed architecture extends a 32-bit single-cycle RISC-V processor with custom test instructions and supporting hardware that enable the processor to execute built-in diagnostic routines.

Instead of relying solely on external testing, the processor can initiate self-test operations, analyze the generated responses, and determine whether the execution pipeline is functioning correctly before continuing with normal program execution.

The objective is to provide a lightweight self-test mechanism with minimal architectural overhead while improving processor trustworthiness in applications where reliability is critical.

---

## Key Contributions

- Designed a self-testable 32-bit RISC-V processor using custom ISA extensions.
- Proposed a mechanism for in-field processor self-testing before critical execution.
- Integrated dedicated test logic with the processor datapath while minimizing hardware overhead.
- Presented the proposed architecture at **IEEE International Test Conference (ITC) India 2026**.

---

## Research Poster

The research poster presented at IEEE ITC India 2026 is available in this repository.

- **IEEE_ITC_India_2026_Poster.pdf**

---

## Repository Contents

```
├── final_itc_poster.pdf
└── README.md
└── ITC_India_2026_paper.pdf

```

---

## Project Status

This repository is intended to showcase the research concept and presentation material.

The complete RTL implementation is not publicly available as the project is currently under active development.
