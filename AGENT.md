# AGENTS.md

You are implementing QLogX.

## Mission

Build a production-ready logging framework for Qt.

The framework must be reusable by multiple libraries and applications.

Target platforms:

- Windows
- Linux
- Embedded Linux
- Android

Qt Version:

- Qt 5.12 minimum

Language

- C++11
- C API

Dependencies

QtCore only.

No Boost.

No spdlog.

No log4cpp.

No external dependency.

Design Principles

- SOLID
- RAII
- Thread Safe
- Zero Memory Leak
- Low Latency
- Async Logging

Never use

- Singleton except LoggerManager
- Exceptions
- RTTI
- QObject unless required

Coding Style

- One class per file
- Function < 80 lines
- Class < 500 lines
- Use std::unique_ptr
- enum class
- constexpr
- camelCase()

Always generate complete code.

Never generate pseudo code.

Never leave TODO.

All code must compile.

Every feature must include an example.

Every public class requires documentation.
