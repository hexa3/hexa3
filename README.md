## Sheheryar

Software engineer in the UAE building systems-level projects end to end — from programming languages and microkernels to robotics, AI, and game engines. I like ambitious ideas, from-scratch engineering, and software you can clone and run.

At the start of every year I write down the projects I want to build that year, then work through the list one at a time, giving each one up to two months. That's why the projects below go deep: each one gets enough time to be designed, built, tested, and documented properly instead of being a weekend prototype.

### ⭐ [Khatam-V](https://github.com/hexa3/khatam-v) · [writeup](https://sheheryar.xyz/khatam-v/)

A game console on a single Tiny Tapeout chip (4x2 tiles on GF180). An RV32E + Zmmul RISC-V CPU runs C straight from SPI flash with PSRAM over the same four QSPI wires, and a framebuffer-less GPU computes every 640x480 VGA pixel in one clock — four Islamic eight-pointed-star (khatam) patterns, shape and bitmap sprites, and hardware collision detection. A three-voice sound chip drives a single PWM pin, and the launch game, Starfall, runs in Verilog simulation and on an FPGA.

### ⭐ [Tumble](https://github.com/hexa3/tumble) · [writeup](https://sheheryar.xyz/tumble/)

The sequel to tinydie: a die whose pips behave like real little discs — tilt it and they roll, shake it and they bounce off the walls, then they settle into a random face with a haptic thud. Three stacked 50x50 mm boards (an 11x11 LED face on an IS31FL3733B, an STM32G041 core with accelerometer, haptics, and an avalanche-noise entropy source, and a USB-C battery base), with d4 through d100. Randomness is verifiable over USB serial: SP 800-90B health tests feed a BLAKE2s pool into ChaCha20.

### [Cartpole18](https://github.com/hexa3/cartpole18) · [live demo](https://cartpole18.netlify.app)

An 18-link inverted pendulum balanced on a cart by a single linear motor, written in Rust and running in the browser via WebAssembly. A 1 kHz LQR controller designed in double-double (~32-digit) precision keeps the whole chain upright and recovers from pushes on any link.

### [Redoubt OS](https://github.com/hexa3/redoubt-os)

Redoubt OS is a capability-safe Rust microkernel for hardened appliances. It explores ring-3 service isolation, verified program storage, signed A/B updates with rollback, encrypted persistence, supervision, and a working QEMU operator shell.

### Other projects

[Astra](https://github.com/hexa3/astra) · [Torque](https://github.com/hexa3/torque) · [tinydie silicon](https://github.com/hexa3/ttgf-tinydie) · [tinydie](https://github.com/hexa3/tinydie) · [PrognosAI](https://github.com/hexa3/prognosai) · [Tempo](https://github.com/hexa3/tempo) · [Night Sky for TRMNL](https://github.com/hexa3/trmnl-night-sky) · [Starwise](https://github.com/hexa3/starwise) · [Focus Buddy](https://github.com/hexa3/focus-buddy) · [chipper](https://github.com/hexa3/chipper) · [One More Game](https://github.com/hexa3/one-more-game) · [The Mannequin in the Dead Mall](https://github.com/hexa3/the-mannequin-in-the-dead-mall) · [Bounce Box](https://github.com/hexa3/bounce-box) · [Smart Trash Sorter](https://github.com/hexa3/smart-trash-sorter) · [minamilist](https://github.com/hexa3/minamilist) · [ChessForge](https://github.com/hexa3/chessforge) · [Memex](https://github.com/hexa3/memex) · [Helios](https://github.com/hexa3/helios) · [Block Craftz](https://github.com/hexa3/block_craftz) · [Lumina Learn](https://github.com/hexa3/lumina_learn) · [Drag Sim](https://github.com/hexa3/drag_sim) · [Wayfinder](https://github.com/hexa3/wayfinder-reveriehacks-2026) · [Lucid](https://github.com/hexa3/lucid) · [FlappyLearn](https://github.com/hexa3/FlappyLearn) · [Trend Sight](https://github.com/hexa3/trend_sight) · [MoneyMind AI](https://github.com/hexa3/Money-Mind-AI) · [Compass](https://github.com/hexa3/compass) · [CodeForces](https://github.com/hexa3/CodeForces-1)

I keep coming back to clear languages, capability boundaries, deterministic behavior, transparent algorithms, local-first software, and tools that make difficult ideas easier to understand.

Web: [sheheryar.xyz](https://sheheryar.xyz)
