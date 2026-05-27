<div align="center">
  <img src="https://github.com/EduardoDosSantosFerreira/EduardoDosSantosFerreira/blob/main/img/TheCrowWallpaperGif.gif" width="570" />
</div>

<h1 align="center">Eduardo dos Santos Ferreira</h1>

<p align="center">
  Software Engineer focused on desktop systems, Windows automation, and internal tooling.
</p>

<p align="center">
  Building reliable local-first applications, operational utilities, and automation systems designed for real production workflows.
</p>

---

# Core Engineering Areas

- Desktop application architecture
- Windows-native automation and tooling
- Internal systems and operational workflows
- Offline-first software design
- Local encrypted storage systems
- Maintenance and diagnostics utilities
- Process automation and execution management
- Modular software architecture

---

# Featured Systems

## 🜂 KAIRUS — Secure Offline Notes Platform

Encrypted local-first note management system designed for environments where privacy, local ownership, and reliability are critical.

### Key Engineering Decisions

- Cloud synchronization intentionally avoided to preserve local control over sensitive data
- Recovery handling implemented to reduce risks of data loss during unexpected interruptions
- Encryption workflow designed around isolated local persistence instead of external services

### Core Features

- AES-256-CBC encryption
- PBKDF2 key derivation (100k iterations)
- Password-protected folders
- Auto-save and recovery handling
- Offline-first architecture
- Encrypted local storage
- PDF and TXT export support

### Engineering Focus

- Secure local persistence
- Encryption workflow implementation
- Recovery and fallback handling
- Desktop application maintainability
- Reliability-focused local architecture

### Technical Stack

`Python` • `PySide` • `Cryptography` • `Local Storage Systems`

### Repository

```bash
github.com/EduardoDosSantosFerreira/kairus
```

---

## 🐦‍⬛ CleanCrow — Windows Maintenance & Automation Suite

Windows maintenance and operational cleanup utility focused on automation, execution reliability, and native system integration.

### Problem

Manual maintenance routines across Windows environments were repetitive, inconsistent, and difficult to centralize.

### Solution

Developed a modular desktop utility capable of automating cleanup operations, package management, and execution logging through native Windows tooling.

### Core Features

- Temporary file cleanup
- Native Windows command execution
- Winget integration
- Real-time operation logs
- Progress tracking
- Administrative privilege elevation
- Modular execution structure

### Architecture

```text
Interface Layer
    ↓
Execution Layer
    ↓
Windows System Operations
```

### Engineering Focus

- Windows systems integration
- Execution flow management
- Automation of operational routines
- Maintainable modular structure
- Reliability in maintenance workflows

### Technical Stack

`Python` • `PyQt5` • `Windows API` • `Winget` • `PyInstaller`

### Current Limitations

- Windows-only support
- No rollback mechanism
- Dependency on native Windows utilities

### Repository

```bash
github.com/EduardoDosSantosFerreira/cleancrow-legacy
```

---

## ⚡ DarkFeather — Wireless Diagnostics Utility

Wireless profile inspection and diagnostics utility developed for operational support and local network analysis in Windows environments.

### Purpose

Built to simplify inspection and recovery of locally stored wireless configuration data used in support and maintenance workflows.

### Core Features

- Wi-Fi profile extraction
- XML profile parsing
- Adapter and GUID identification
- Local password visualization
- Administrative privilege handling
- Native Windows integration

### Engineering Focus

- Windows networking integration
- Local diagnostics tooling
- Native command interaction
- Operational utility development
- Desktop workflow optimization

### Technical Stack

`Python` • `Tkinter` • `WMI` • `Windows Networking`

### Repository

```bash
github.com/EduardoDosSantosFerreira/darkfeather
```

---

# Technical Focus

Primary focus on Python-based desktop systems, Windows automation, and operational tooling.

Additional experience includes development of supporting interfaces and API integrations using JavaScript, TypeScript, React, Vue, and Node.js where required by operational workflows.

---

# Professional Experience

## Noctra Systems — Founder / Software Developer

Development of internal systems, automation tools, and desktop applications focused on operational reliability and workflow optimization.

Work includes:

- Desktop application architecture
- Automation of repetitive operational processes
- Systems diagnostics and maintenance tooling
- Integration with Windows-native utilities
- Refactoring and maintainability improvements
- Development of local-first operational systems

---

## Technical Degree in Systems Development — ETEC

Technical education focused on:

- Software development
- Systems architecture fundamentals
- Application structure
- Infrastructure and support
- Programming logic
- Technical problem solving

---

# Current Engineering Direction

- Improving maintainability of desktop systems
- Expanding modular internal tooling
- Reducing operational complexity through automation
- Improving reliability in local applications
- Refactoring legacy structures for long-term maintainability
- Building more resilient local-first systems

---

# Development Approach

- Prefer practical solutions over unnecessary complexity
- Build systems focused on long-term maintainability
- Prioritize reliability and predictable behavior
- Design software around real operational constraints
- Use automation to reduce repetitive workflows
- Keep systems functional, maintainable, and operationally simple

---

<div align="center">

### No cloud. No unnecessary complexity. Just functional systems.

</div>
