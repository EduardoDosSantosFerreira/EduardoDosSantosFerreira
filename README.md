<div align="center">

<img src="https://cleancrow.vercel.app/src/assets/img/profile_icons/crowico.png" width="110">

# CleanCrow

### Windows Maintenance & Automation

A modular Windows utility for system maintenance, diagnostics, cleanup,
package management, and automation.

<p>
  <a href="https://cleancrow.vercel.app/">Website</a> •
  <a href="https://github.com/EduardoDosSantosFerreira/cleancrow-legacy">Repository</a>
</p>

</div>

---

## Overview

CleanCrow was built around a simple operational problem:

> Windows maintenance often requires multiple commands, utilities, and
> manual procedures that are difficult to centralize and execute consistently.

CleanCrow turns these operations into a controlled desktop workflow while
keeping individual maintenance routines separated into independent modules.

The project is intentionally built around **native Windows functionality**
where possible, using tools such as `cleanmgr`, `DISM`, `winget`, Windows APIs,
and native command execution.

---

## Problem → Solution

### Problem

Routine Windows maintenance can involve:

- Temporary files spread across multiple locations
- Browser and application caches
- Windows Update leftovers
- GPU shader caches
- Error reports and logs
- Recycle Bin contents
- Native Windows maintenance commands
- Application updates
- Administrative operations

Handling these tasks manually means repeatedly opening different tools,
running commands, checking permissions, and verifying results.

### Solution

CleanCrow provides a single desktop interface that orchestrates these
operations through a modular execution engine.

```text
User
 │
 ▼
Desktop Interface
 │
 ▼
Execution Engine
 │
 ├── Temp Cleaner
 ├── Browser Cleaner
 ├── Cache Cleaners
 ├── Windows Update Cleaner
 ├── GPU Cache Cleaners
 ├── System Cleaner
 ├── DNS Cleaner
 └── Component Store Cleaner
 │
 ▼
Windows APIs / Native Tools
 │
 ▼
System
