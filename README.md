## Sheheryar

Software engineer in the UAE building systems-level projects end to end — from programming languages and microkernels to robotics, AI, and game engines. I like ambitious ideas, from-scratch engineering, and software you can clone and run.

### Torque — my programming language

**[Torque](https://github.com/hexa3/torque)** is a real-time robotics control language designed around the things robots actually need:

- Physical units and coordinate frames as first-class types
- Control loops that declare deadlines and report overruns
- Built-in typed pub/sub
- The same source running against simulation or real hardware
- Functions that export themselves as LLM tool schemas
- Zero runtime dependencies beyond Node.js

Torque is interpreted from `.tq` source, with 35 tests covering the language, deterministic loop behavior, dimensional analysis, simulation, serial control, live tuning, and tool export.

### Redoubt OS

**[Redoubt OS](https://github.com/hexa3/redoubt-os)** — a capability-safe Rust microkernel for hardened appliances. It boots a ring-3 service architecture with capability-based isolation, verified program storage, signed A/B updates with rollback, encrypted persistence, supervision, and a working QEMU operator shell.

### Systems programming

Rust is my primary systems language: kernels, runtimes, real-time control, cryptography, developer tools, and software that has to be correct at the boundaries. I also build with Python, C++, TypeScript, and JavaScript when the problem calls for them.

### Flagship projects

- **[torque](https://github.com/hexa3/torque)** — the Torque language and runtime for real-time robotics control
- **[chessforge](https://github.com/hexa3/chessforge)** — from-scratch Python chess engine: bitboards, legal move generation, alpha-beta search with modern pruning, reproducible benchmarks; plays on Lichess as [@ChessForge_Bot](https://lichess.org/@/ChessForge_Bot)
- **[memex](https://github.com/hexa3/memex)** — local-first persistent memory for LLMs in a single SQLite file; semantic search, auto-learning, zero external services; published to [PyPI](https://pypi.org/project/memex-ai/) and [npm](https://www.npmjs.com/package/memex-ai)
- **[helios](https://github.com/hexa3/helios)** — 6-DOF robot arm simulator: forward kinematics, damped least-squares IK, Newton-Euler dynamics, impedance control, live dashboard
- **[block_craftz](https://github.com/hexa3/block_craftz)** — browser voxel engine with deterministic world generation, greedy meshing, ECS, and voxel physics
- **[lumina_learn](https://github.com/hexa3/lumina_learn)** — local-first AI study assistant: screen vision, OCR, PyTorch activity recognition, RAG tutoring

### What I keep coming back to

Systems that earn trust: clear languages, capability boundaries, deterministic behavior, transparent algorithms, local-first software, and tools that make difficult ideas easier to understand.

Robotics & simulation: [torque](https://github.com/hexa3/torque) · [helios](https://github.com/hexa3/helios) · [drag_sim](https://github.com/hexa3/drag_sim)

Web: [sheheryar.xyz](https://sheheryar.xyz)