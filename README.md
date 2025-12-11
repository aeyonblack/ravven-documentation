# RAVVEN Engineering Data Package (EDP)

![Project Status](https://img.shields.io/badge/Status-Design%20Phase-orange)
![Version](https://img.shields.io/badge/EDP%20Version-v0.1--alpha-blue)
![License](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey)

> **🚧 Building in Public:**
> Follow the engineering log and join the course waitlist at **[blog.ravven.dev](https://blog.ravven.dev)**.
> *Subscribe to get the latest EDP updates sent directly to your inbox.*

---

This repository contains the official **Engineering Data Package (EDP)** for Project RAVVEN (**R**ust-based **A**utonomous **V**ehicle for **V**irtual **E**nvironment **N**avigation).

Unlike traditional hobbyist guides, RAVVEN documentation is structured as a professional systems engineering suite. These documents define the architecture, communication protocols, and hardware specifications required to build and program the digital twin robot.

## 📂 Document Index

The documentation is split into four distinct specifications.

| Document ID | Title | Status | Description |
| :--- | :--- | :--- | :--- |
| **DOC-A** | **System Architecture Specification (SAS)** | ✅ **Released** | The high-level design document. Defines the "Puppet" architecture, the 3-node topology (Motor, Nav, Twin), and functional requirements. **Start here.** |
| **DOC-B** | **Interface Control Document (ICD)** | ✅ **Released** | The technical reference for communication. Defines the UART packet structure, State Machine logic, and Command Library hex codes. |
| **DOC-C** | **Integration & Assembly Manual** | 🚧 *In Progress* | Step-by-step hardware build guide, BOM (Bill of Materials), and 3D print specifications. |
| **DOC-D** | **Hardware Reference Manual** | 🚧 *In Progress* | Electrical datasheets, PCB pinouts, and expansion board specifications. |

## 🚀 Getting Started

If you are new to the project, please read the documents in the following order:

1.  **Read the SAS (System Architecture Specification):** This explains *why* we use dual ESP32s and how the "Digital Twin" synchronization works.
2.  **Read the ICD (Interface Control Document):** Essential for writing your firmware drivers. It contains the exact byte-level protocols you need to implement.
3.  **Check the Releases:** Download the latest stable PDFs from the [Releases Page](../../releases).

## 🛠 Project Context

RAVVEN is an educational platform designed to teach **Embedded Systems Engineering with Rust**.

* **Firmware:** Built on `no_std` Rust using `esp-hal`.
* **Hardware:** Custom dual-ESP32 architecture (Motor Subsystem + Navigation Subsystem).
* **Simulation:** Real-time browser-based Digital Twin (Virtual Maze).

## 📦 Download

You can download the compiled PDF versions of these documents from the **[Latest Release](../../releases)** section of this repository.

## 📄 License

The documentation in this repository is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

---
*Maintained by Tanya Masvita. Visit [blog.ravven.dev](https://blog.ravven.dev) to follow the engineering log.*
