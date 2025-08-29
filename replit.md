# Android Mod Menu Template

## Overview

This project is a comprehensive template for creating floating mod menus for Android games, specifically targeting native games and il2cpp Unity games. It provides a framework for experienced modders to implement custom modification interfaces that overlay on top of target applications. The template supports multiple Android versions (4.4.x to Android S Preview) and architectures (ARMv7, ARM64, and x86), making it versatile for various mobile gaming environments.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Core Architecture
- **Native Library Framework**: Built using C/C++ with JNI (Java Native Interface) for Android integration
- **Cross-Architecture Support**: Supports ARMv7, ARM64, and x86 architectures with focus on ARM variants
- **Overlay UI System**: Implements floating overlay menus that can be displayed on top of target applications
- **Hook Integration**: Utilizes And64InlineHook library for ARM64 inline hooking capabilities

### Development Environment
- **Android Studio Integration**: Designed to work with Android Studio 4+ with NDK support
- **Mobile Development Option**: Alternative setup using modded AIDE apps for on-device development
- **Build System**: Uses standard Android build tools with native library compilation support

### UI Architecture
- **Java-based Layout**: UI components implemented in Java with XML layout definitions
- **Floating Window System**: Leverages Android's overlay permission system for floating interfaces
- **Cross-Platform Compatibility**: Designed to work across different Android versions and screen sizes

### Hook System
- **And64InlineHook Library**: Lightweight ARM64 inline hooking for function interception
- **Multi-Architecture Support**: Separate implementations for different processor architectures
- **Memory Manipulation**: Direct memory access and modification capabilities for game patching

## External Dependencies

### Development Tools
- **Android Studio**: Primary IDE with NDK support for native development
- **Apktool**: APK decompilation and recompilation tool for target game modification
- **APK Easy Tool**: GUI wrapper for APK manipulation tasks

### Mobile Development Dependencies
- **Modded AIDE Apps**: Alternative IDEs for mobile-only development workflows
- **NDK Packages**: Architecture-specific Native Development Kit packages
- **File Management Apps**: X-plore or MT Manager for file system operations

### Runtime Dependencies
- **Android Overlay Permissions**: System-level permissions for floating UI display
- **Native Library Loading**: Android's native library loading mechanism
- **JNI Bridge**: Java Native Interface for communication between Java UI and C++ core

### Target Integration
- **Game Process Injection**: Capability to inject into target application processes
- **Memory Access**: Direct memory read/write operations on target applications
- **Function Hooking**: Runtime interception and modification of game functions