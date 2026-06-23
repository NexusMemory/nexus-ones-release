<p align="center">
  <img src="./assets/hero-banner.png" alt="Nexus Ones Hero Banner" width="100%">
</p>

<br>

<p align="center">
  <img src="./assets/logo.png" alt="Nexus Ones Logo" width="96">
</p>

<h1 align="center">Nexus Ones</h1>

<p align="center">
  <strong>个人办公中枢系统</strong>
</p>

<p align="center">
  将日历、待办、提醒、备忘、项目、课程与插件统一到一个个人工作台。
</p>

<p align="center">
  <img src="https://img.shields.io/badge/macOS-Supported-black?style=flat-square">
  <img src="https://img.shields.io/badge/Windows-Supported-blue?style=flat-square">
  <img src="https://img.shields.io/badge/v0.2.4--beta.1-success?style=flat-square">
  <img src="https://img.shields.io/badge/World_Cup_2026-Beta-gold?style=flat-square">
</p>

<br>

---

# 快速入口

<br>

<div align="center">

| | | |
|:-:|:-:|:-:|
| <a href="https://github.com/NexusMemory/nexus-ones-release/releases/latest"><img src="./assets/download.png" width="190" alt="下载中心"></a> | <a href="https://github.com/NexusMemory/nexus-ones-release/blob/main/docs/Nexus_Ones_Plugin_Developer_Guide_v1.0.docx"><img src="./assets/plugin.png" width="190" alt="插件开发手册"></a> | <a href="https://github.com/NexusMemory/nexus-ones-release/blob/main/docs/Nexus_Ones_Plugin_Developer_Guide_v1.0.docx"><img src="./assets/document.png" width="190" alt="文档中心"></a> |
| **下载中心** | **插件开发手册** | **文档中心** |
| 获取最新版 macOS / Windows 安装包 | 查看 Nexus Ones 插件开发规范 | 官方开发文档与技术说明 |

</div>

<br>

<div align="center">

| | |
|:-:|:-:|
| <a href="https://github.com/NexusMemory/nexus-ones-release/issues"><img src="./assets/feedback.png" width="190" alt="反馈中心"></a> | <a href="mailto:LeungKinWah@outlook.com"><img src="./assets/contact.png" width="190" alt="联系我们"></a> |
| **反馈中心** | **联系我们** |
| 提交问题与功能建议 | 联系 Nexus Lab |

</div>

<br>

---

# 产品简介

Nexus Ones 是一套面向个人用户的工作与生活秩序系统。

它不是单一的日历、待办或备忘录工具，而是一个 Personal Operating Hub，用于把分散的信息、任务、项目、课程与插件能力统一到一个稳定、轻量、可扩展的个人工作台中。

---

# 核心能力

## Today Dashboard

统一查看：

- 今日状态
- 待办事项
- 提醒事项
- 日历事项
- 项目进度
- 倒计时
- 四象限任务

---

## Calendar

支持：

- 年视图
- 月视图
- 周视图
- 日视图
- 中国节假日
- 农历显示
- 日程管理

---

## Tasks & Reminders

统一管理：

- 待办
- 提醒
- 备忘
- 项目事项
- 日程事项

| 等级 | 含义 |
|------|------|
| P1 | 非常重要 |
| P2 | 重要 |
| P3 | 普通 |
| P4 | 不重要 |

---

## Four Quadrants

根据任务优先级与时间紧迫性自动判断：

- 重要且紧急
- 重要不紧急
- 不重要但紧急
- 不重要不紧急

---

## Plugin Runtime

v0.2.4 开始实装：

- Plugin Runtime
- Runtime Sandbox
- Plugin Storage
- Plugin Messaging
- HTML Plugin
- JavaScript Plugin

示例插件：

```text
hello.nexus
```

插件开发手册：

[Nexus Ones Plugin Developer Guide v1.0](https://github.com/NexusMemory/nexus-ones-release/blob/main/docs/Nexus_Ones_Plugin_Developer_Guide_v1.0.docx)

---

## Snapshot & Restore

内置快照系统：

- 创建快照
- 恢复快照
- 数据回滚
- 历史版本保护

---

# 数据安全

Nexus Ones 用户数据独立于应用本体。

推荐数据目录：

```text
Nexus Ones Data
├── production
├── sandbox
├── plugins
├── backups
└── config
```

支持：

- 覆盖安装不丢数据
- 卸载重装自动恢复
- 插件数据独立存储
- iCloud 跨设备同步

---

# 跨设备工作流

推荐：

```text
iCloud Drive
└── Nexus Ones Data
```

典型工作流：

```text
Mac mini
    ↓
 iCloud
    ↓
MacBook Air
```

---

# 当前版本

## Nexus Ones v0.2.4 Beta

### World Cup 2026 Edition

本轮测试重点：

- Plugin Runtime
- Update Center
- Snapshot & Restore
- Status Light
- Data Root
- Cross Device Sync
- Windows Installer

---

# 下载

最新版：

[下载 Nexus Ones](https://github.com/NexusMemory/nexus-ones-release/releases/latest)

全部版本：

[查看 Releases](https://github.com/NexusMemory/nexus-ones-release/releases)

---

# 开发者中心

官方开发文档：

[Nexus Ones Plugin Developer Guide v1.0](https://github.com/NexusMemory/nexus-ones-release/blob/main/docs/Nexus_Ones_Plugin_Developer_Guide_v1.0.docx)

包含：

- Plugin SDK
- Plugin Runtime
- API Reference
- Marketplace
- Design System
- Best Practices

---

# 路线图

## v0.3

- Plugin Marketplace
- Desktop Widgets
- Health Center
- Plugin SDK

---

## v0.4

- AI Workspace
- Knowledge Hub
- Cross Device Sync Enhancement

---

## v1.0

- Stable Release
- Complete Plugin Ecosystem
- Nexus Ones Public Launch

---

# 技术架构

## Frontend

```text
React
TypeScript
Vite
```

## Backend

```text
Tauri 2
Rust
SQLite
```

## Platforms

```text
macOS
Windows
```

---

# Nexus Lab

Designed and developed by Nexus Lab.

Building software for productivity, education and personal operating systems.

---

# License

Copyright © Nexus Lab

All Rights Reserved.
