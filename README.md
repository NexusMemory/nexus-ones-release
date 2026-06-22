<p align="center">
  <img src="./assets/hero-banner.png" alt="Nexus Ones" width="100%">
</p>

<h1 align="center">Nexus Ones</h1>

<p align="center">
  Personal Operating Hub
</p>

<p align="center">
  Unify Calendar, Tasks, Notes, Projects and Plugins into a single personal operating hub.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/macOS-Supported-black?style=for-the-badge">
  <img src="https://img.shields.io/badge/Windows-Supported-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Tauri-2.x-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge">
  <img src="https://img.shields.io/badge/Version-v0.2.4--beta.1-success?style=for-the-badge">
</p>

---

## Overview

Nexus Ones is a personal operating hub designed to unify planning, execution, review and extension into a single workspace.

Instead of switching between multiple productivity tools, Nexus Ones centralizes daily work, project management, reminders, scheduling, plugin extensions and data snapshots into one application.

---

## Core Modules

### Today Dashboard

- Today Status
- Four Quadrants
- Calendar
- Reminders
- Tasks
- Projects
- Countdown

### Productivity Center

- Course Center
- Project Library
- Memo
- Reminders
- Calendar
- Status Light

### Plugin System

- Plugin Center
- Runtime Sandbox
- Plugin Storage
- Plugin API
- .nexus Package Format

### System Center

- Snapshot & Restore
- Update Center
- Storage Root
- Production / Sandbox
- Backup Management

---

## Screenshots

### Home

<p align="center">
  <img src="./assets/home.png" width="95%">
</p>

---

### Calendar

<p align="center">
  <img src="./assets/calendar.png" width="95%">
</p>

---

### Plugin Center

<p align="center">
  <img src="./assets/plugin-center.png" width="95%">
</p>

---

### Update Center

<p align="center">
  <img src="./assets/update-center.png" width="95%">
</p>

---

### Course Center

<p align="center">
  <img src="./assets/course-center.png" width="95%">
</p>

---

## Features

### Status Light

Real-time visual status monitoring.

- Green
- Yellow
- Red

Supports:

- Breathing Animation
- Pulse Animation
- Priority Awareness
- Deadline Awareness

---

### Priority System

Unified priority model:

| Level | Meaning |
|---------|---------|
| P1 | Critical |
| P2 | Important |
| P3 | Normal |
| P4 | Low Priority |

Four Quadrants are automatically calculated using:

- Priority
- Deadline
- Time Urgency

---

### Snapshot & Restore

Built-in protection system.

Supports:

- Manual Snapshot
- Restore Point
- Recovery Validation
- Rollback

---

### Plugin Runtime

Supports:

- HTML Plugins
- JavaScript Plugins
- Local Plugin Storage
- Runtime Sandbox
- Plugin Messaging

Example:

```text
hello.nexus
```

---

## Data Safety

Nexus Ones separates all runtime data from the application bundle.

```text
Nexus Ones Data
├── production
├── sandbox
├── plugins
├── backups
└── config
```

Advantages:

- Safe Updates
- Reinstallation Friendly
- Cross Device Synchronization
- Backup Friendly

---

## Cross Device Workflow

Recommended storage root:

```text
iCloud Drive
└── Nexus Ones Data
```

Supported workflow:

```text
Mac mini
      ↓
iCloud Sync
      ↓
MacBook Air
```

Use the same data root on both devices.

---

## Plugin Ecosystem

Package format:

```text
.nexus
```

Runtime APIs:

```javascript
nexus:getAppInfo
nexus:getPluginInfo
nexus:savePluginData
nexus:loadPluginData
```

---

## Roadmap

### v0.3

- Plugin Marketplace
- Desktop Widgets
- Health Center

### v0.4

- AI Workspace
- Knowledge Hub
- Cross Device Sync Enhancement

### v1.0

- Stable Public Release
- Complete Plugin SDK
- Ecosystem Expansion

---

## Installation

### macOS

Download:

```text
Nexus Ones.dmg
```

### Windows

Download:

```text
Nexus Ones Setup.exe
```

---

## Development

```bash
pnpm install

pnpm tauri dev
```

Build:

```bash
pnpm tauri build
```

---

## Nexus Lab

Designed and developed by Nexus Lab.

Focused on building practical software for productivity, education and personal operating systems.

---

## License

Copyright © Nexus Lab

All Rights Reserved.
