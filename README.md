# Self-Testable RISC-V Processor Using Custom Test Instructions

A research project focused on improving processor reliability by enabling a RISC-V processor to perform self-testing before executing critical operations through the use of custom test instructions.

> **Note:** The RTL implementation is currently kept private as the research work is under active development. This repository provides the project overview, research publication, poster, and acceptance information.

---

## Motivation

Modern processors are expected to operate reliably in safety-critical and mission-critical environments. Conventional testing techniques are primarily performed during manufacturing or require external test infrastructure, making periodic in-field validation challenging.

This project explores a mechanism that allows a processor to verify its own functionality before executing critical tasks by introducing dedicated self-test instructions into the RISC-V ISA.

---

## Project Overview

The proposed architecture extends a 32-bit single-cycle RISC-V processor with custom test instructions and supporting hardware to enable processor-level self-testing.

The self-test mechanism allows the processor to initiate diagnostic operations, evaluate the generated responses, and determine whether the processor's functional units are operating correctly before proceeding with normal execution.

The overall objective is to develop a lightweight self-test mechanism with minimal architectural overhead while improving processor reliability and trustworthiness for applications where dependable operation is critical.

---

## Key Contributions

- Designed a self-testable 32-bit RISC-V processor using custom ISA extensions.
- Proposed a mechanism for processor-level self-testing before critical execution.
- Integrated dedicated test hardware with the processor datapath.
- Developed a test mechanism for functional validation of processor components.
- Investigated the use of hardware-assisted self-testing for in-field processor reliability.
- Research work accepted for poster presentation at **IEEE International Test Conference (ITC) India 2026**.

---

## Research Publication

The research work has been accepted for poster presentation at **IEEE International Test Conference (ITC) India 2026**.

### Paper

**Self-Testable RISC-V Processor Using Custom Test Instructions**

[View Research Paper](./ITC_India_2026_paper.pdf)

---

## Conference Poster

The research poster prepared for IEEE ITC India 2026 is available below.

[View Conference Poster](./final_itc_poster.pdf)

---

## Research Acceptance

The acceptance of the research work is documented through the conference submission platform and official email communication.

### EasyChair Acceptance

The EasyChair acceptance confirmation is included in this repository as supporting evidence.

[View EasyChair Acceptance](./docs/ITC_2026_Easychair.png)

### Official Email Confirmation

The official acceptance email is also included for reference.

[View Email Confirmation](./docs/ITC2026_Acceptance.png)

---

## Repository Contents

```text
Self-testable-riscv-processor/
│
├── README.md
├── ITC_India_2026_paper.pdf
├── final_itc_poster.pdf
│
└── docs/
    ├── EasyChair_Acceptance.png
    └── ITC_Acceptance_Email.png
