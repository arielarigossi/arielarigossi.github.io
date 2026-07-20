# Projects

## linux-wtmpreport

<div class="project-card" markdown>

**Linux Log Analysis & Reporting Tool**

A Python tool for analyzing `wtmp` and `secure` system logs. Parses authentication events into a SQLite database and generates detailed HTML/PDF reports with matplotlib visualizations.

:material-tag: `Python` `SQLite` `Matplotlib` `WeasyPrint`

[:fontawesome-brands-github: Source Code](https://github.com/arielarigossi/linux-wtmpreport){ .md-button .md-button--primary }

</div>

**Key features:**

- Parses binary `wtmp` files and text `secure` logs (including `.gz` rotated files)
- Extracts login sessions, authentication attempts, and sudo commands
- Generates charts: login activity, auth results, sudo frequency, timelines
- Produces HTML and PDF monthly and summary reports
- Modular, maintainable package structure with proper error handling

---

## pcap-reportgenerator

<div class="project-card" markdown>

**Network Packet Capture Analyzer**

A PyQt5 GUI application for analyzing PCAP/PCAPNG network captures and generating interactive HTML reports with charts and statistics.

:material-tag: `Python` `PyQt5` `Scapy` `Matplotlib`

[:fontawesome-brands-github: Source Code](https://github.com/arielarigossi/pcap-reportgenerator){ .md-button .md-button--primary }

</div>

**Key features:**

- Parses PCAP files using Scapy to extract network statistics
- Generates styled HTML reports with Bootstrap 5 and interactive DataTables.js
- Protocol distribution charts, top talkers, port analysis, conversation maps
- HTTP, DNS, and SMTP packet queries
- Multilingual UI (English/Spanish) with threaded background analysis
- CSV export and client-side filtering in reports

---

## httpd-fancyreport

<div class="project-card" markdown>

**Apache Log Report Generator**

Processes Apache HTTP server log files (access + error) and produces detailed HTML and PDF reports with visualizations.

:material-tag: `Python` `Matplotlib` `WeasyPrint`

[:fontawesome-brands-github: Source Code](https://github.com/arielarigossi/httpd-fancyreport){ .md-button .md-button--primary }

</div>

**Key features:**

- Parses access logs for IPs, URLs, methods, status codes, user agents
- Analyzes error logs for error levels and frequencies
- Summary statistics: total requests, unique visitors, top URLs
- Charts: request frequency, HTTP status distribution, top IPs, error levels
- Per-month HTML and PDF reports with linked summaries

---

## docker-compose

<div class="project-card" markdown>

**Self-Hosted Services Collection**

A collection of ready-to-use `docker-compose.yml` files for deploying 21 self-hosted services with no port conflicts.

:material-tag: `Docker` `YAML` `Self-Hosted`

[:fontawesome-brands-github: Source Code](https://github.com/arielarigossi/docker-compose){ .md-button .md-button--primary }

</div>

**Key features:**

- 21 services covering: low-code platforms, databases, home automation, media management, monitoring, forensics, backups, diagramming, BI tools
- Includes: Appsmith, Home Assistant, Metabase, Ollama WebUI, Pi-hole, Uptime Kuma, and more
- All compose files designed to work together without port conflicts
- Placeholder credentials for easy testing and deployment

---

## tuxtuner

<div class="project-card" markdown>

**Linux Server Performance Tuning**

An interactive Bash script for tuning Linux server performance with real-time verification of applied settings.

:material-tag: `Bash` `Linux` `Performance`

[:fontawesome-brands-github: Source Code](https://github.com/arielarigossi/tuxtuner){ .md-button .md-button--primary }

</div>

**Key features:**

- Memory tuning: swappiness, cache pressure, dirty ratios
- Network optimizations: TCP buffers, socket reuse, backlog, slow-start
- File descriptor limits for high-I/O workloads
- Auto-detects SSD vs HDD and suggests appropriate I/O scheduler
- CPU governor control with persistence hints
- Real-time verification that applied settings match expected values

---

## MusicNamer

<div class="project-card" markdown>

**Batch Music File Renamer**

A PyQt5 desktop application for batch renaming audio files using music fingerprinting and metadata lookup services.

:material-tag: `Python` `PyQt5` `MusicBrainz` `AcoustID`

[:fontawesome-brands-github: Source Code](https://github.com/arielarigossi/MusicNamer){ .md-button .md-button--primary }

</div>

**Key features:**

- AcoustID audio fingerprinting for song identification
- MusicBrainz fuzzy metadata search
- Embedded tag reading from audio files
- Filename guessing with guessit
- Batch rename with preview and title case formatting
- Modular package structure with proper entry points

---

## AppReflejo

<div class="project-card" markdown>

**Android Forensic Report Tool**

A PyQt5 desktop application for capturing Android device screenshots and generating forensic HTML reports with SHA256 hashing.

:material-tag: `Python` `PyQt5` `ADB` `Forensics`

[:fontawesome-brands-github: Source Code](https://github.com/arielarigossi/AppReflejo){ .md-button .md-button--primary }

</div>

**Key features:**

- Device info retrieval via ADB
- Screenshot capture with SHA256 integrity hashing
- HTML report generation with metadata and evidence tables
- scrcpy integration for screen mirroring
- Designed for digital forensic documentation workflows

---

## tmux-manager

<div class="project-card" markdown>

**tmux Session Manager GUI**

A PyQt5 desktop application for managing tmux sessions with real-time CPU/memory monitoring and system tray integration.

:material-tag: `Python` `PyQt5` `tmux` `Linux`

[:fontawesome-brands-github: Source Code](https://github.com/arielarigossi/tmux-manager){ .md-button .md-button--primary }

</div>

**Key features:**

- Create, attach, detach, and kill tmux sessions from a GUI
- Real-time per-session CPU and memory monitoring via psutil
- Event logging with CSV/JSON/text export
- System tray icon with notifications
- Configurable terminal emulator, shell, and refresh intervals
- External QSS theme for customizable styling
