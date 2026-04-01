# 2D custome engine
C++20, GLFW | [GitHub Repo](https://github.com/Mikail-Kahya/custom-engine) | [Portfolio](https://mikailkahya.netlify.app/engine)

![tron-card-m](https://github.com/user-attachments/assets/b76e3ec9-8b18-4a8d-91bf-6e5aa0c75c14)


## Overview
Custom game engine built from scratch to explore **low-level game programming**. Features an **engine library** that links into any project via CMake, plus core engine systems for input, commands, and resource loading. Test demo loads a test project of Tron battle tanks using keyboard/XInput controllers.\
\
**Core goal:** Learn programming patterns while maintaining clean engine architecture that supports multiple game projects.

## Design Philosophy
- **Engine neutrality** - No hardcoded game logic
- **Game Programming Patterns** applied throughout
- This proves I can handle low-level engine programming with clean, extensible architecture.

## Tech Stack
- C++20
- GLFW (window/input)
- CMake
- Git

## Architecture

[Game Project]\
↑ (CMake)\
[Core Engine]

**Key design decisions:**
- **Engine as separate library** - Link via CMake (reduceds recompiles)
- **Abstraction layers**
- **No game-specific code** - Engine supports any project type

## Features

### Graphics Pipeline
- 2D image loading support

### Input & Controls
- WASD - Movement
- Mouse - Camera look
- XInput controllers - Full support (not used in demo)

### Development
- **Command pattern** - Undo/redo, unit selection (RTS-friendly)
- Text-based UI - Screen size, debug info
- **Custom 2D collision**
- Resource management (textures, fonts)

## Build
I built it through MSVC but any way of compiling a CMake project will work. The launching of the project can be found in the Out folder.    

## References
- [Game Programming Patterns](https://gameprogrammingpatterns.com)
