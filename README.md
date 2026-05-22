# Matthew Berger

> Actively looking for Senior Staff or Principal Rust roles.

Senior Staff Rust Software Engineer. I have written production Rust at every layer of the stack, from bare-metal firmware to cloud infrastructure. Founding software engineer at Hyphen Robotics, where I built a food assembly robotics controls suite from zero to production in **22 months**, underpinning **$35M+** raised from Chipotle and Cava.

**Working with Rust since 2016**, with 5 years in production robotics at Hyphen Robotics and earlier production Rust at Sierra Nevada Corporation (aerospace imaging). Background also includes medical robotics at Hamilton Company.

[matthewberger.dev](https://matthewberger.dev) (portfolio and articles) · [matthewberger.dev/nightshade](https://matthewberger.dev/nightshade) (Nightshade live demo) · [LinkedIn](https://linkedin.com/in/matthewjberger)

## Notable work

- [Nightshade](https://github.com/matthewjberger/nightshade): data-oriented Rust game engine (200k+ LOC) with an advanced PBR renderer and custom render graph, built-in editor, rapier3d physics, kira audio, gltf asset loading, scene graph, object picking, and Steam integration. Runs natively on DX12/Metal/Vulkan and in-browser via WebGPU. [Live demo](https://matthewberger.dev/nightshade).
- [freecs](https://github.com/matthewjberger/freecs): archetype-based ECS in Rust with zero unsafe code, Rayon-parallel execution, sparse-set tags, and compile-time generation; the foundation of Nightshade. **48k+ downloads** on crates.io. Design documented in a [3-part article series](https://matthewberger.dev/articles).
- [enum2 derive macro family](https://github.com/matthewjberger?tab=repositories&q=enum2): **230k+ combined downloads** on crates.io for enum-driven design patterns; several (including enum2contract and enum2str) used in production Rust at Hyphen Robotics.
- [wgpu-example](https://github.com/matthewjberger/wgpu-example): cross-platform Rust + wgpu + egui template running on native, web, Android, Steam Deck, and OpenXR VR.
- [bamboo](https://github.com/matthewjberger/bamboo): fast Rust static site generator that powers matthewberger.dev. [Live demo](https://matthewberger.dev/bamboo/).

## Other projects

- [cameras](https://github.com/matthewjberger/cameras): cross-platform Rust camera library with data-oriented design
- [stateless](https://github.com/matthewjberger/stateless): state machine library with a DSL separating structure from behavior
- [frost](https://github.com/matthewjberger/frost): statically-typed programming language with Rust-inspired ownership and a dual backend (bytecode VM + Cranelift JIT)

Also: [dragonglass](https://github.com/matthewjberger/dragonglass) (PBR Vulkan engine), [dhcplease](https://github.com/matthewjberger/dhcplease) (DHCP server), [clippr](https://github.com/matthewjberger/clippr) (MP4 to GIF tool), and [charter](https://github.com/matthewjberger/charter) (Rust codebase context generator for LLMs). See [crates.io/users/matthewjberger](https://crates.io/users/matthewjberger) for the full list of published Rust crates.

## Go projects

- [indigo](https://github.com/matthewjberger/indigo): early data-oriented Go game engine with an archetype ECS, a wgpu-backed render graph, dual-world simulation/render separation, and free-function systems on a named schedule; native (GLFW) and web (WebAssembly) targets
- [freecs-go](https://github.com/matthewjberger/freecs-go): archetype ECS for Go, port of the freecs Rust library
- [wgpu-example-go](https://github.com/matthewjberger/wgpu-example-go): Go port of wgpu-example with a spinning RGB triangle on native desktop (GLFW) and WebGPU (WASM)
- [stateless-go](https://github.com/matthewjberger/stateless-go): state machine code generator for Go that decouples data from behavior
- [pubsub-go](https://github.com/matthewjberger/pubsub-go): small JSON-over-TCP pub/sub broker and client in Go, data-oriented design
- [terminal-go](https://github.com/matthewjberger/terminal-go): tiny data-oriented Go text adventure (Zork-style) with SoA room/item tables, bitset tags, free-function verbs, and one-call gob save/load
