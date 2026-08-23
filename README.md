<div align="center">
  <img src="https://github.com/EduardoDosSantosFerreira/EduardoDosSantosFerreira/blob/main/img/TheCrowWallpaperGif.gif" width="520" />
</div>

<h1 align="center">Eduardo dos Santos Ferreira</h1>

<p align="center">
  <strong>Software Engineer focused on desktop software, Windows automation, and local-first applications.</strong>
</p>

<p align="center">
  I build desktop software, Windows automation tools, and local-first applications focused on practical operational problems.
</p>

<p align="center">
  <a href="https://github.com/EduardoDosSantosFerreira">GitHub</a> •
  <a href="https://www.linkedin.com/in/eduardodossantosferreira/">LinkedIn</a> •
  <a href="mailto:eduardo.dsf.dev@gmail.com">Email</a>
</p>

---

# Featured Projects

## <img src="https://cleancrow.vercel.app/src/assets/img/profile_icons/crowico.png" width="32" height="32" align="center"> CleanCrow — Windows Maintenance & Automation

**CleanCrow** is a modular Windows maintenance utility built to centralize system cleanup, diagnostics, package management, and operational logging.

The project was created around a practical problem: routine Windows maintenance often involves repetitive commands, scattered tools, and inconsistent execution.

CleanCrow brings these operations into a single desktop workflow while keeping the underlying system operations modular.

### What it does

* Temporary and system file cleanup
* Browser and shader cache management
* Windows Update cache cleanup
* Recycle Bin and thumbnail cache management
* DISM and `cleanmgr` integration
* Winget package updates
* Administrative privilege handling
* Real-time progress and operation logs
* Multiple cleaning modes
* Parallel execution of independent operations

### Architecture

```text id="0q3h2x"
Interface
    ↓
Execution Engine
    ↓
Modular Cleaners
    ↓
Windows APIs / Native Tools
    ↓
System Operations
```

The project separates the interface, execution engine, individual cleaners, Windows API integration, and logging system.

### Engineering Focus

`Python` `PyQt5` `Windows API` `Winget` `ThreadPoolExecutor` `PyInstaller`

**Repository:**
[https://github.com/EduardoDosSantosFerreira/cleancrow-legacy](https://github.com/EduardoDosSantosFerreira/cleancrow-legacy)

---

## <img src="https://eduardodossantosferreira.github.io/kairus/icon.png" width="32" height="32" align="center"> Kairus — Encrypted Offline Notes

**Kairus** is a desktop notes application built around local ownership, encrypted persistence, and offline operation.

The project intentionally avoids requiring cloud synchronization, keeping application data under the user's local control.

### Highlights

* Encrypted local storage
* Password-protected folders
* Auto-save and recovery handling
* Offline-first architecture
* PDF and TXT export
* Local persistence without mandatory external services

### Engineering Focus

* Desktop application architecture
* Local data persistence
* Encryption workflows
* Recovery handling
* Maintainable local-first design

**Stack:** `Python` `PySide` `cryptography`

**Repository:**
[https://github.com/EduardoDosSantosFerreira/kairus](https://github.com/EduardoDosSantosFerreira/kairus)

---

## <img src="https://eduardodossantosferreira.github.io/ravenizer/ravenizer.png" width="32" height="32" align="center"> Ravenizer — Windows Update Automation

**Ravenizer** is a desktop utility for automating Windows and application updates through package management tools.

It combines a graphical workflow with Winget and Chocolatey to reduce repetitive update operations.

### Highlights

* `winget upgrade --all`
* Chocolatey package updates
* Operation logging
* Progress tracking
* Desktop interface
* One-click update workflow

**Stack:** `Python` `PySide6` `Winget` `Chocolatey`

**Repository:**
[https://github.com/EduardoDosSantosFerreira/ravenizer](https://github.com/EduardoDosSantosFerreira/ravenizer)

---

## <img src="https://crowvert.vercel.app/src/assets/img/profile_icons/crowvert.png" width="32" height="32" align="center"> Crowvert — Desktop File Conversion

**Crowvert** is a local desktop utility for converting and processing files without requiring online services.

### Highlights

* TXT → DOCX
* DOCX → PDF
* PDF → DOCX
* SVG → PNG
* 7Z → ZIP
* Conversion history
* Batch-oriented workflows
* Modular application structure

**Stack:** `Python` `Tkinter`

**Repository:**
[https://github.com/EduardoDosSantosFerreira/crowvert](https://github.com/EduardoDosSantosFerreira/crowvert)

---

# Other Projects

### <img src="https://eduardodossantosferreira.github.io/darkfeather/src/assets/img/profile_icons/darkfeather.png" width="28" height="28" align="center"> DarkFeather

Windows wireless diagnostics utility for inspecting local network profiles, parsing wireless configuration data, and interacting with native Windows networking functionality.

`Python` `Tkinter` `WMI` `Windows Networking`

**Repository:**
[https://github.com/EduardoDosSantosFerreira/darkfeather](https://github.com/EduardoDosSantosFerreira/darkfeather)

### <img src="https://eduardodossantosferreira.github.io/rook/img/logo/logo.png" width="28" height="28" align="center"> Rook

Windows performance optimization utility focused on system configuration, performance settings, restore point creation, and automated maintenance routines.

`Python` `PySide6` `Windows`

**Repository:**
[https://github.com/EduardoDosSantosFerreira/rook](https://github.com/EduardoDosSantosFerreira/rook)

---

# Noctra Systems

## Founder & Independent Software Developer

**Noctra Systems** is my independent software development and technology services operation, focused on building practical software for real-world technical and operational problems.

My work includes:

* Desktop application development
* Windows automation
* System maintenance and diagnostics
* Internal tools and operational utilities
* Local-first applications
* File processing and conversion systems
* Process automation
* Windows-native integrations
* Custom software solutions

The goal is simple: **turn repetitive, technical, or operational problems into practical software solutions.**

---

# Technical Focus

My strongest focus is **Python desktop development and Windows system integration**.

### Core

`Python` `PySide6` `PyQt5` `Tkinter`

### Windows & Automation

`Windows API` `WMI` `PowerShell` `CMD` `Winget` `PyInstaller`

---

# Engineering Principles

* **Practicality** — solve the actual problem before adding complexity.
* **Maintainability** — keep systems understandable and extensible.
* **Automation** — eliminate repetitive operational work.
* **Reliability** — design for predictable behavior and failure handling.
* **Local ownership** — use local-first approaches when cloud services are unnecessary.
* **Modularity** — separate responsibilities so systems can evolve over time.

---

<div align="center">

### Build useful things. Automate what repeats. Keep the system understandable.

</div>
