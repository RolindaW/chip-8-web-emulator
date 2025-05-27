# Chip 8 Web Emulator

Introduction - TODO

# Features

## Chip 8 Emulator

- Chip 8 ISA
- Rendering
- Sound
- Keyboard input handling
- ROM loading
- Execution: run, reset

### Advanced

- Chip 8 ISA variants
- On-screen virtual HEX keyboard input handling (mouse/touch compatibility)
- Profiler: CPU status (PC, SP, register file, timers), memory (main and stack)
- Debugger: run/resume, pause, step, reset

## User

- ROM selection: default ROM register
- CPU frequency setup

### Advanced

- ROM selection: custom ROM register + session (optional; if available)
- Chip 8 ISA variant setup
- Per-user managament:
  - Login
  - ROM management: create (upload), list, remove
- Per-ROM management:
  - Setup: CPU frequency, ISA variants
  - Session: save, list, remove

# Stack

## Frontend

- Vanilla HTML, CSS, JS (JavaScript)
- Libraries (TBD): Bootstrap, jQuery
- Framework: none

## Backend

- Programming language: JavaScript
- Runtime: Node.js
- Package manager: NPM

### Web Server

- Framework: Express
- Protocol: HTTP (non-secure)

### Application

- Framework: none
- Test: Jest

### Data Persistance

- (TBD) File system + PostgreSQL vs. MongoDB

## Other

### Version Control System

- Git
- Hosting: GitHub
- Integration: Continuous Integration
- Release (TBD): (Healthy) Mainline to production with tags vs. Release branch vs. Hybrid (tags by default; release branch when required e.g. hotfix specific version)

### Tool version manager

- Mise-en-place

### Architecture

- Hexagonal (a.k.a. Ports and Adapters)
- Framework: none

### Documentation

- MD (Markdown)
- Site generator (TBD): MkDocs vs. Material for MkDocs
- Hosting (TBD): Read the Docs vs. GitHub Pages + GitHub Actions

# Version

TODO

# License

This project is licensed under the terms of the MIT license.
