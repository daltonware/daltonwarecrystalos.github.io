# Welcome to CrystalOS 💎

**CrystalOS** is a custom, from-scratch operating system developed as a deep dive into low-level architecture, kernel design, and hybrid programming environments.

This documentation serves as the central hub for the project's architecture, build instructions, and development roadmap.

---

## 🏗️ Architecture & Tech Stack

CrystalOS is built using a robust hybrid architecture, combining the bare-metal control of traditional systems languages with the potential of modern frameworks.

*   **Bootloader:** GRUB2 (Multiboot2 compliant)
*   **Initialization & Low-Level:** Assembly (NASM)
*   **Kernel Core:** C and C++ (Memory management, Framebuffer, Drivers)
*   **High-Level Modules:** C# (NativeAOT integration planned)

### Boot Process
The system utilizes GRUB to transition the CPU into protected mode and initialize a graphical Framebuffer environment right from the start, bypassing the legacy VGA text mode to display a custom graphical boot screen.

---

## 🚀 Getting Started

If you want to compile and test CrystalOS on your own machine, follow the steps below.

### Prerequisites
You will need a Linux environment (or WSL) with the following tools installed:
*   `x86_64-elf-gcc` (Cross-compiler)
*   `nasm`
*   `xorriso` and `grub-pc-bin` (For ISO generation)
*   `qemu-system-x86_64` (For testing)

Coming Soon, stay tuned.
