---
title: 'Building Systems from Scratch: Low-Level Programming Projects'
description: 'From Assembly calculators to database engines - exploring computer science fundamentals'
pubDate: 'Jan 10 2025'
---

## Why I Love Low-Level Programming

While many developers rely on high-level abstractions, I've found immense value in understanding how computers work at the fundamental level. Here's a showcase of projects where I built systems from scratch.

## Assembly Typing Game

One of my favorite projects is a **retro-style typing game built entirely in x86 Assembly Language**. Think ZType, but written without any high-level language abstractions.

### Technical Deep Dive

- Implemented with the Irvine Library
- Dynamic word generation system
- Real-time input handling at the hardware level
- Custom graphics rendering without modern frameworks
- Memory management done manually

This project taught me about:
- Hardware-level programming concepts
- Direct memory manipulation
- Real-time input processing
- Graphics rendering fundamentals

## C++ Graphing Calculator

I built a graphing calculator that parses mathematical expressions and renders plots in real-time.

### Architecture Highlights

- **Custom data structures**: Built Stack and Queue from scratch using linked lists
- **Shunting Yard algorithm**: Converts infix to Reverse Polish Notation (RPN)
- **SFML graphics**: Real-time function visualization
- No reliance on high-level parsing libraries

## Record Tables: A Database Engine from Scratch

This might be my most ambitious project - a lightweight database engine with SQL-like query capabilities.

### What Makes It Special

**Complete Query Pipeline:**
1. Tokenizer breaks down user input
2. Shunting-yard parser converts to RPN
3. RPN evaluator executes queries

**Performance Features:**
- B+ tree indexing for logarithmic-time lookups
- Binary file storage
- Custom implementations of core data structures (no STL for engine core)
- Built with modern C++ best practices

**Testing & Build System:**
- CMake build configuration
- GoogleTest integration
- Comprehensive test coverage

## Assembly Calculator

Before tackling complex projects, I started with fundamentals: a calculator in pure Assembly.

### Learning Outcomes

- Number format conversions (ASCII ↔ BCD)
- Bit-level arithmetic operations
- Direct memory management
- Hardware-software interface understanding

---

## Why These Projects Matter

These projects aren't just academic exercises. They demonstrate:

- **Deep systems knowledge** - Understanding how computers work at the lowest level
- **Performance optimization** - Knowing where bottlenecks occur
- **Debugging skills** - Finding issues without high-level debugging tools
- **Algorithmic thinking** - Implementing efficient algorithms from scratch

*Tech Stack: x86 Assembly, C++, SFML, Irvine Library, CMake, GoogleTest, B+ Trees, Binary I/O*