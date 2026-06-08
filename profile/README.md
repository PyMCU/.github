# PyMCU Project 🐍⚡

> **🚀 STATUS UPDATE (June 2026): Alpha Release 1 is LIVE!**
> The wait is over. The compiler core (`PyMcuC`), the embedded standard library, and the AVR toolchain are now public for our **first Alpha release**. Repositories are open, early builds are available, and we are ready for your feedback. Jump in and start compiling!

**PyMCU** is an **open-source, experimental AOT compiler** that translates a safe subset of Python directly into **pure, highly optimized Assembly (ASM)** for microcontrollers — aiming for deterministic, bare-metal execution with **Zero-Cost Abstractions (ZCA)**.

- **Deterministic by design:** No OS, no Garbage Collector.
- **Transparent & Educational:** No black boxes. See exactly what your Python code turns into at the assembly level, making it perfect for both learning and high-performance embedded systems.
- **Ecosystem-ready:** Built-in standard library tailored for embedded constraints.
- **MIT-licensed.**

## 🗺️ Roadmap & Current Scope

### ⚙️ Phase 1 — AVR Alpha *(Released)*
To ensure a highly optimized and stable foundation, our first milestone was laser-focused on a single, robust target. The core foundation is now live.

| Area | Status |
|---|---|
| Compiler core (`PyMcuC` Python → AVR ASM) | ✅ Alpha Released |
| Target: ATmega328p (Arduino Uno / Nano / Mega) | ✅ Alpha Released |
| Toolchain integration (`avra` assembler) | ✅ Alpha Released |
| Core standard library for embedded constraints | ✅ Alpha Released |
| Public repositories & issue trackers | ✅ Open |

> *With the AVR core now in its Alpha stage, we are actively fixing bugs, accepting community contributions, and preparing the ground for broader architectural support.*

### 🔮 Phase 2 — Stability, ARM Backend & Sustainable Development
With the foundation laid out, Phase 2 is about scaling the architecture and stabilizing the core based on real-world usage.

- **Community-Driven Polish:** As early adopters test the Alpha, our immediate priority is resolving bugs, edge cases, and refining the AVR core based on your feedback.
- **Beyond AVR (Experimental):** Development on the **ARM Cortex-M backend** is already underway. We currently have minimal, proof-of-concept support for the **RP2040** (successfully compiling Blink and UART). This proves our architecture effectively scales beyond 8-bit systems.
- **Project Sustainability:** This concept lived as an idea for 5 years before advanced AI tooling helped dramatically accelerate its development into a reality. To maintain access to these resources, PyMCU is gently transitioning to a community-funded model with a goal of **$300 USD/month** to cover operational and tooling costs. As we navigate this transition, the pace of active development will naturally slow down for now. Contributions are completely optional but deeply appreciated, as they directly fuel the project's momentum.

## 🤝 Get Involved
The Alpha is here, and this is the best time to participate in shaping the future of PyMCU:

- 🐛 **Early testers** — grab the Alpha builds, compile your first scripts, and open issues with your feedback, bugs, and ideas.
- 🛠️ **Contributors** — code, docs, tests, and examples are all welcome. See [`CONTRIBUTING.md`](../CONTRIBUTING.md) for guidelines.
- ⭐ **Star the repositories** — if you like what we are building, leaving a star helps us gain visibility within the embedded and Python communities.
- 💬 **Spread the word** — share your compiled projects with other embedded-Python enthusiasts!

## ☕ Support
PyMCU is free, independent, and community-driven. If you believe in the vision and wish to support ongoing development to help us reach our monthly goal, you can donate via **Ko-fi** (see the Sponsor button at the top).

📧 **contact@pymcu.org**
