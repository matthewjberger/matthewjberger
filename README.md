# Matthew Berger

Senior Staff Rust Software Engineer. I have written production Rust at every layer of the stack, from bare-metal firmware to cloud infrastructure. Founding software engineer at Hyphen Robotics, where I built a food assembly robotics controls suite from zero to production in **22 months**, underpinning **$35M+** raised from Chipotle and Cava.

**Working with Rust since 2016**, with 5 years in production robotics at Hyphen Robotics and earlier production Rust at Sierra Nevada Corporation (aerospace imaging). Background also includes medical robotics at Hamilton Company.

[matthewberger.dev](https://matthewberger.dev) · [LinkedIn](https://linkedin.com/in/matthewjberger)

## Notable work

- [Nightshade](https://github.com/matthewjberger/nightshade): data-oriented Rust game engine built from plugin crates over its own archetype ECS. A glTF-first PBR renderer with the full KHR extension set and a custom render graph, on wgpu (DX12/Metal/Vulkan natively, WebGPU in-browser) and on a second Vulkan 1.3 backend for mesh shaders and ray tracing. Includes rapier3d physics, kira audio, animation, navmesh, particles, sprites, voxels, OpenXR VR, and Steam integration. [Live demo](https://matthewberger.dev/nightshade).
- [Frost](https://github.com/matthewjberger/frost): a data-oriented systems language with Odin-style syntax that is memory-safe with no garbage collector and no lifetimes, using linear resources and generational handles. The compiler is written in Frost, emits x86-64 objects directly with C as a second target, and reproduces its own output byte for byte through both. [Site](https://matthewberger.dev/frost/).
- [ennui](https://github.com/matthewjberger/ennui): retained UI framework in data-oriented Rust with a scene editor that Claude can drive. Screens are plain-text scene files: you edit them with the mouse while Claude edits the same scene live through a local socket, and the app fills the resources they bind to and answers the asks their buttons send. Runs on Windows, macOS, Linux, and in-browser via WebGPU. [Live demo](https://matthewberger.dev/ennui/).
- [freecs](https://github.com/matthewjberger/freecs): archetype-based ECS in Rust with zero unsafe code, Rayon-parallel execution, sparse-set tags, and compile-time generation; Nightshade was built on it before moving to its own in-tree ECS. **48k+ downloads** on crates.io. Design documented in a [3-part article series](https://matthewberger.dev/articles).
- [Nightshade Viewer](https://github.com/matthewjberger/nightshade-viewer): a glTF/GLB model viewer that runs the Nightshade engine in a web worker via WebGPU, rendering off-thread to an OffscreenCanvas while a Leptos UI (viewport, scene tree, inspector, toolbar, asset browser) stays responsive on the main thread. Supports drag-and-drop, scene picking, and object selection, with optional MCP control by tools like Claude Code. Runs in-browser and as a native webview desktop app. [Live demo](https://matthewberger.dev/nightshade-viewer).
- [enum2 derive macro family](https://github.com/matthewjberger?tab=repositories&q=enum2): **230k+ combined downloads** on crates.io for enum-driven design patterns; several (including enum2contract and enum2str) used in production Rust at Hyphen Robotics.
- [wgpu-example](https://github.com/matthewjberger/wgpu-example): cross-platform Rust + wgpu + egui template running on native, web, Android, Steam Deck, and OpenXR VR.
- [bamboo](https://github.com/matthewjberger/bamboo): fast Rust static site generator that powers matthewberger.dev. [Live demo](https://matthewberger.dev/bamboo/).

## Other projects

- [hearsay](https://github.com/matthewjberger/hearsay): topic-based pub/sub for Rust built on tokio; an in-process broker with TCP and WebSocket peers, typed enum contracts, broker bridging, message batching, and supervised child processes
- [cameras](https://github.com/matthewjberger/cameras): cross-platform Rust camera library with data-oriented design
- [stateless](https://github.com/matthewjberger/stateless): state machine library with a DSL separating structure from behavior
 
Also: [dragonglass](https://github.com/matthewjberger/dragonglass) (PBR Vulkan engine), [dhcplease](https://github.com/matthewjberger/dhcplease) (DHCP server), [clippr](https://github.com/matthewjberger/clippr) (MP4 to GIF tool), and [charter](https://github.com/matthewjberger/charter) (Rust codebase context generator for LLMs). See [crates.io/users/matthewjberger](https://crates.io/users/matthewjberger) for the full list of published Rust crates.

## Go projects

- [indigo](https://github.com/matthewjberger/indigo): early data-oriented Go game engine with an archetype ECS, a wgpu-backed render graph, dual-world simulation/render separation, and free-function systems on a named schedule; native (GLFW) and web (WebAssembly) targets
- [freecs-go](https://github.com/matthewjberger/freecs-go): archetype ECS for Go, port of the freecs Rust library
- [wgpu-example-go](https://github.com/matthewjberger/wgpu-example-go): Go port of wgpu-example with a spinning RGB triangle on native desktop (GLFW) and WebGPU (WASM)
- [stateless-go](https://github.com/matthewjberger/stateless-go): state machine code generator for Go that decouples data from behavior
