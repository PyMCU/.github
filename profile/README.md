# PyMCU Project 🐍⚡

> **🚧 STATUS UPDATE (March 2026): Active & In Stealth Mode**
> The PyMCU organization might look quiet, but heavy development is happening behind closed doors. We are currently heads-down building the core infrastructure, finalizing the first Alpha release, and polishing the PyMCU standard library. **Big news and code drops are coming very soon. Stay tuned.**

**PyMCU** is an **open-source, experimental AOT compiler** that translates a safe subset of Python directly into **pure Assembly (ASM)** for microcontrollers — aiming for deterministic, bare-metal execution.

- **Deterministic by design:** no OS, no Garbage Collector.
- **Ecosystem-ready:** Built-in standard library tailored for embedded constraints.
- **MIT-licensed.**

## 🗺️ Roadmap & Current Scope
To ensure a highly optimized and stable Alpha release, our current development is laser-focused on a single, robust target.

- **Phase 1 (Current Focus): AVR 8-bit Architecture**
  - **Targets:** ATmega328p (Arduino Uno, Nano, Mega).
  - **Toolchain:** The compiler output is strictly pure ASM, designed to be assembled using `avra`.
  - **Core Standard Library:** Launching alongside the Alpha.

> *Once the AVR core is stable, we will evaluate expanding to other architectures (such as ARM Cortex-M, ESP32, or PIC) based on community adoption, contributor feedback, and potential hardware sponsorships.*

## 🤝 Get Involved (Soon)
Follow the organization to be notified when the repositories go public. Once we launch, we will be actively looking for feedback via issues, as well as contributions to code, docs, and tests.

## ☕ Support
PyMCU is free, independent, and community-driven. If you believe in the vision and wish to support the development leading up to the Alpha release, you can donate via **Ko-fi** (see the Sponsor button at the top).

📧 **contact@pymcu.org**
