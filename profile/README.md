# PyMCU Project 🐍⚡

> **🚀 STATUS UPDATE (April 2026): Active Development — Alpha Release Incoming**
> Development is in full swing. The compiler core, standard library, and toolchain are being finalised ahead of the **first public Alpha release**. Expect repository access, early builds, and announcements very soon. Watch the organisation to get notified the moment we ship.

**PyMCU** is an **open-source, experimental AOT compiler** that translates a safe subset of Python directly into **pure Assembly (ASM)** for microcontrollers — aiming for deterministic, bare-metal execution.

- **Deterministic by design:** no OS, no Garbage Collector.
- **Ecosystem-ready:** Built-in standard library tailored for embedded constraints.
- **MIT-licensed.**

## 🗺️ Roadmap & Current Scope

### ⚙️ Phase 1 — AVR Alpha *(in progress)*
To ensure a highly optimised and stable first release, development is laser-focused on a single, robust target.

| Area | Status |
|---|---|
| Compiler core (Python → AVR ASM) | 🔨 In progress |
| Target: ATmega328p (Arduino Uno / Nano / Mega) | 🔨 In progress |
| Toolchain integration (`avra` assembler) | 🔨 In progress |
| Core standard library for embedded constraints | 🔨 In progress |
| Alpha release & public repositories | 🔜 Coming soon |

> *Once the AVR core is stable, we will evaluate expanding to other architectures (ARM Cortex-M, ESP32, PIC) based on community adoption, contributor feedback, and potential hardware sponsorships.*

### 🔮 Phase 2 — Beyond AVR *(planned)*
Additional architecture targets and a broader standard library will follow the Alpha, guided by community feedback.

## 🤝 Get Involved
The first Alpha release is around the corner. Here is how you can participate:

- ⭐ **Watch / Star** this organisation to get notified the moment repositories go public.
- 🐛 **Early testers** — once the Alpha drops, open issues with your feedback, bugs, and ideas.
- 🛠️ **Contributors** — code, docs, tests, and examples are all welcome. See [`CONTRIBUTING.md`](../CONTRIBUTING.md) for guidelines.
- 💬 **Spread the word** — if PyMCU sounds interesting to you, share it with other embedded-Python enthusiasts.

## ☕ Support
PyMCU is free, independent, and community-driven. If you believe in the vision and wish to support ongoing development, you can donate via **Ko-fi** (see the Sponsor button at the top).

📧 **contact@pymcu.org**
