# HSU Example2

HSU Repository Portability Framework - Approach 2 (Multi-Language)

This is a demonstration repository showing how to structure a single-repository, multi-language project using the HSU (Highly Structured Universal) Repository Portability Framework.

## Features

- gRPC-based Echo service implementation in both Go and Python
- Cross-platform build system with HSU Universal Makefile
- Repository-portable code structure
- Automated protobuf generation for both languages
- Language-specific CLI and server implementations
- Nuitka binary compilation support for Python

## Quick Start

### Go Components
```bash
# Build Go components
make go-build

# Run Go server
make go-run-srv

# Run Go client
make go-run-cli
```

### Python Components
```bash
# Install Python dependencies
make py-install

# Build Python components
make py-build

# Run Python server
make py-run-srv

# Run Python client
make py-run-cli

# Build Python binary with Nuitka
make py-nuitka-build
```

## Documentation

For comprehensive documentation, setup guides, and framework details, see:
https://github.com/Core-Tools/docs/blob/main/README.md

## Repository Structure

This repository demonstrates **Approach 2**: Single-Repository + Multi-Language (Go + Python), showing how HSU framework enables seamless coordination between different programming languages within a single repository structure.