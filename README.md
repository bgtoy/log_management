# QLogX

## Goal

Build a production-ready logging framework for Qt.

## Platform

- Qt 5.12+
- Android
- Linux
- Embedded Linux
- Windows

## Language

- C++11
- C API

## Requirements

- Thread Safe
- Async Logger
- Multiple Sink
- File Rotation
- Daily Rotation
- Console Sink
- Android Logcat
- Hex Dump
- Runtime Configuration
- Transaction Context
- Session Context
- Scope Timer
- Zero external dependency

## API

LOG_INFO(...)
LOG_WARN(...)
LOG_ERROR(...)
LOG_FATAL(...)

LOG_HEX(...)

LOG_SERIAL(...)

LOG_APDU(...)

LOG_HTTP(...)

LOG_SQL(...)