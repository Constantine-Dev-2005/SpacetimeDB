# SpacetimeDB C++ SDK

This repository contains the C++ Module SDK and C++ Client SDK (Unreal Engine) for [SpacetimeDB](https://spacetimedb.com).

> **Note:** This is a fork of [clockworklabs/SpacetimeDB](https://github.com/clockworklabs/SpacetimeDB), restructured to contain only the C++ Module and Client SDKs.

## Repository Structure

```
SpacetimeDB/
├── crates/bindings-cpp/     # C++ Module SDK — write SpacetimeDB modules in C++
├── sdks/unreal/             # C++ Client SDK — Unreal Engine plugin for SpacetimeDB clients
├── modules/                 # Example and test C++ modules
│   ├── benchmarks-cpp/
│   ├── module-test-cpp/
│   ├── sdk-test-cpp/
│   ├── sdk-test-connect-disconnect-cpp/
│   ├── sdk-test-procedure-cpp/
│   └── sdk-test-view-cpp/
└── templates/basic-cpp/     # Starter template for a C++ SpacetimeDB module
```

## C++ Module SDK

The **C++ Module SDK** (`crates/bindings-cpp/`) lets you write SpacetimeDB server modules in C++20 that compile to WebAssembly using Emscripten.

### Prerequisites

- [Emscripten SDK (emsdk)](https://emscripten.org/docs/getting_started/downloads.html) — for compiling to WebAssembly
- CMake 3.16+
- C++20 compatible compiler

### Quick Start

See [`crates/bindings-cpp/QUICKSTART.md`](crates/bindings-cpp/QUICKSTART.md) for a step-by-step guide.

For full API documentation see [`crates/bindings-cpp/REFERENCE.md`](crates/bindings-cpp/REFERENCE.md).

## C++ Client SDK (Unreal Engine)

The **Unreal Engine C++ Client SDK** (`sdks/unreal/`) provides an Unreal Engine plugin that lets your game connect to a SpacetimeDB server, call reducers, and maintain a synchronized table cache.

### Getting Started

See [`sdks/unreal/README.md`](sdks/unreal/README.md) and [`sdks/unreal/DEVELOP.md`](sdks/unreal/DEVELOP.md) for setup instructions.

## License

[BSL 1.1](LICENSE.txt)
