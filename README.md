# ⚡ PrixMS (Minecraft Server Implementation in Rust)

> **PrixMS** is a custom Minecraft server implementation built from the ground up using **Rust**. It is designed for ultra-low memory footprints, high-performance multi-threading, and a modern architecture powered by **Bevy ECS**.

---

## 🚀 Core Features & Architecture

- **Ultra-Efficient ECS Memory:** Driven by **Bevy ECS** for lockless, multi-threaded entity, player, and block management with an idle memory target of < 20MB RAM.
- **Async World Generation:** Decouples world generation, lighting engine, and network I/O from the main 20 TPS tick loop.
- **Native Crossplay Ready:** Internal network pipeline structured to support both Java TCP and Bedrock UDP streams.
- **Universal Plugin Runtime:** Multi-language plugin architecture with sandboxed **WASM (Wasmtime)** and **Lua (mlua)** execution.
- **Legacy V5 Protocol Target:** Initial release target tailored for **Minecraft Java Edition 1.7.10** (Protocol Version 5).

---

## 👥 AI Collaboration & Workflow Architecture

PrixMS is architected independently by **Wildan** (*Architect & Lead Developer*) supported by an AI-assisted development workflow:

- **Gemini:** *System Architecture, Technical Design & Conceptual Roadmap*
- **ChatGPT:** *Core Code Generation*
- **DeepSeek:** *Refactoring, Optimization & Error Debugging*

---

## 🛠️ Getting Started

### Prerequisites
- [Rust Toolchain](https://rustup.rs/) (Edition 2021 or newer)
- `cargo` package manager

### Build & Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/USERNAME/PrixMS.git](https://github.com/USERNAME/PrixMS.git)
   cd PrixMS
