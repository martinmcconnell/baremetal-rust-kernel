# Baremetal Rust Kernel

## Overview

Prototype kernel in Rust/ To be used in an embedded AI prototype application and device. Details to follow.

## Objectives and Requirements

Goals and functionalities, ideally on ARM architecture. With a MicroKernel design as opposed to a monolith.

- [ ] Create a bootloader
- [ ] Assemble entry point
  - (may not be necessary on raspberry pi, but will on the ORIN platform, should that go ahead)
- [ ] Essential Data Structures
  - Interrupt descriptor table
  - Global descriptor table
  - basic interrupt handling routines
- [ ] Memory Management
  - physical and virtual
  - page tables
  - memory allocation mechanisms
- [ ] Interrupt handling
  - manage system calls
  - exceptions
  - proritising interrupts
- [ ] Basic I/P
  - keyboard
  - console
  - Audio I/O
- [ ] Device Drivers
  - list essential hardware components
- [ ] System Calls
  - how much user-space access will be necessary?
  - process scheduling
  - file systems
  - etc.

todo:
1: - [ ] boot on raspberry pi
2: - [ ] Get GPIO access
3: - [ ] Figure out whether this can go any further
