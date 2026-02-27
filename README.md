# SpacetimeDB++

The C++ Module SDK for [SpacetimeDB](https://spacetimedb.com) — write SpacetimeDB server modules in C++20.

> **Note:** This is a fork of [clockworklabs/SpacetimeDB](https://github.com/clockworklabs/SpacetimeDB), restructured to contain the C++ Module SDK.

## Repository Structure

```
SpacetimeDB/
├── SpacetimeDB++/           # The SDK — C++ bindings for writing SpacetimeDB modules
├── Tests/                   # Test modules and integration tests
│   ├── module-test-cpp/
│   ├── sdk-test-cpp/
│   ├── sdk-test-connect-disconnect-cpp/
│   ├── sdk-test-procedure-cpp/
│   └── sdk-test-view-cpp/
└── Examples/                # Example projects and starter templates
    ├── basic-cpp/           # Starter template for a new C++ module
    └── benchmarks-cpp/      # Benchmark modules
```

## SpacetimeDB++

The **C++ Module SDK** (`SpacetimeDB++/`) lets you write SpacetimeDB server modules in C++20 that compile to WebAssembly using Emscripten.

### Prerequisites

- [Emscripten SDK (emsdk)](https://emscripten.org/docs/getting_started/downloads.html) — for compiling to WebAssembly
- CMake 3.15+
- C++20 compatible compiler

### Quick Start

See [`SpacetimeDB++/QUICKSTART.md`](SpacetimeDB++/QUICKSTART.md) for a step-by-step guide.

For full API documentation see [`SpacetimeDB++/REFERENCE.md`](SpacetimeDB++/REFERENCE.md).

## License

[BSL 1.1](LICENSE.txt)
