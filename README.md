# Hi there 👋

I build open-source tools for the Linux desktop, mostly around Wayland, Hyprland, and Omarchy. By day I'm a web developer working in .NET and JavaScript.

Most of my projects started as fixes for things that bugged me in my own workflow, so they tend to be local-first and keyboard-friendly. My main project atm is [Wayscriber](https://wayscriber.com), a ZoomIt-style screen annotation tool for Linux and Wayland.

<!-- TODO: a short GIF of Wayscriber or the Window Switcher in action would do more here than any badge -->

[![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)](https://isocpp.org/)
[![.NET](https://img.shields.io/badge/-.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Shell](https://img.shields.io/badge/-Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Wayland](https://img.shields.io/badge/-Wayland-FFBC00?style=flat-square&logo=wayland&logoColor=black)](https://wayland.freedesktop.org/)
[![Arch Linux](https://img.shields.io/badge/-Arch_Linux-1793D1?style=flat-square&logo=archlinux&logoColor=white)](https://archlinux.org/)

## Start here

| | |
| --- | --- |
| ✍️ **[Wayscriber](https://github.com/devmobasa/wayscriber)**<br>Real-time screen annotation for Linux and Wayland, inspired by ZoomIt. Draw over any app, zoom into details, keep persistent boards. [Website & docs →](https://wayscriber.com) | 🎥 **[Omarec](https://github.com/devmobasa/omarec)**<br>Screen recording for Omarchy and Hyprland, built on GPU Screen Recorder. Adds session recovery, menus, and bar integration. |
| 🧭 **[Omarchy Nexus](https://github.com/devmobasa/omarchy-nexus)**<br>A keyboard-driven cockpit for Omarchy: media controls, system metrics, quick settings, clipboard history, and notes. | 🧹 **[dotnet-anti-slop](https://github.com/devmobasa/dotnet-anti-slop)**<br>Roslyn analyzers that catch real reliability and performance mistakes in C#, ASP.NET Core, and EF Core code. |

## Linux desktop & Wayland

- 🖊️ **[Omascribe](https://github.com/devmobasa/omascribe)**: a small C++23/Qt 6 overlay for drawing live annotations on the Omarchy and Hyprland desktop.
- 🖍️ **[SharpMarker](https://github.com/devmobasa/SharpMarker)**: a .NET 11 and SkiaSharp screen annotation tool for Linux and Wayland, with drawing tools, boards, capture, zoom, and persistent sessions.
- ⌨️ **[Keyway](https://github.com/devmobasa/keyway)**: a small Rust/GTK4 keystroke visualizer for Wayland, handy for demos and screen recordings.
- 🗣️ **[SpeechToText](https://github.com/devmobasa/SpeechToText)**: local push-to-talk transcription for Linux, with GPU acceleration and Wayland/X11 output.

## Developer workflow & automation

- 🎬 **[Wayscriber Video Toolkit](https://github.com/devmobasa/wayscriber-video-toolkit)**: the Wayland capture and FFmpeg pipeline I use to produce Wayscriber videos, posters, and contact sheets.
- 🔥 **[ff](https://github.com/devmobasa/ff)**: fire-and-forget launchers that run commands as detached systemd jobs or in hidden Hyprland terminals.
- 🌳 **[Treeist](https://github.com/devmobasa/treeist)**: a Git worktree helper with a compact `wt` CLI, interactive pickers, and cleanup workflows.
- 🤖 **[Yummy](https://github.com/devmobasa/yummy)**: a Mattermost bridge for the `pi` and `codex` coding-agent CLIs, with resumable sessions and progress updates.
- 🔐 **[QuickOTP](https://github.com/devmobasa/QuickOTP)**: a cross-platform TOTP manager with a terminal UI, QR support, and 2FAS backup import/export. The popup is built for hotkey use: I summon it with Super+Shift+A, type a few letters, hit Enter, and the code is on my clipboard.

## Omarchy plugins

Plugins and add-ons I've built for the Omarchy bar and desktop.

**At a glance**

- ✍️ **[Wayscriber Deck](https://github.com/devmobasa/omarchy-wayscriber-deck)**: Wayscriber controls in the Omarchy bar, with live status, capture and presentation actions, plus quick access to boards and recent sessions.
- 📅 **[Calendar Agenda](https://github.com/devmobasa/omarchy-calendar-agenda)**: upcoming-event countdowns and a two-week agenda from ICS or CalDAV export URLs.
- 📥 **[Dev Inbox](https://github.com/devmobasa/omarchy-dev-inbox)**: GitHub notifications, review requests, assigned issues, and failed CI in one bar badge.
- 🧼 **[Git Hygiene](https://github.com/devmobasa/omarchy-git-hygiene)**: a bar badge that finds dirty and unpushed repositories across your project roots.
- 🍅 **[Pomodoro](https://github.com/devmobasa/omarchy-pomodoro)**: a restart-proof focus timer with work/break cycles and automatic Do Not Disturb.
- 🔴 **[Privacy Dots](https://github.com/devmobasa/omarchy-privacy-dots)**: dots in the bar that show which app is using your microphone or screen.
- ⏱️ **[Screen Time](https://github.com/devmobasa/omarchy-screen-time)**: local per-app focus tracking with a daily breakdown and a week-at-a-glance chart.
- 🩺 **[systemd Health](https://github.com/devmobasa/omarchy-systemd-health)**: a quiet status chip that only appears when system or user units fail.

**Windows & workspaces**

- 🪟 **[Window Switcher](https://github.com/devmobasa/omarchy-window-switcher)**: a keyboard-first Quickshell switcher with MRU ordering, search, and live window previews.
- 🔭 **[Window Overview](https://github.com/devmobasa/omarchy-window-overview)**: a Mission Control-style overview with live thumbnails and drag-to-move workspace organization.
- 📦 **[Minimizer Tray](https://github.com/devmobasa/omarchy-minimizer-tray)**: shows how many windows you've stashed on the minimized workspace and brings them back.
- 🗂️ **[Scratchpad Deck](https://github.com/devmobasa/omarchy-scratchpad-deck)**: named drop-down scratchpads that spawn their app if it isn't running yet.

**System control**

- 💾 **[Drive Bay](https://github.com/devmobasa/omarchy-drive-bay)**: mount, unmount, and check free space on removable drives through UDisks2.
- 🎮 **[Game Mode](https://github.com/devmobasa/omarchy-game-mode)**: a one-click bar toggle that strips compositor effects for gaming, then puts your exact Hyprland config back.
- 🖥️ **[Monitor Layout](https://github.com/devmobasa/omarchy-monitor-layout)**: drag-to-arrange displays with mode, scale, rotation, and VRR, remembered per monitor.
- 🛡️ **[Permission Center](https://github.com/devmobasa/omarchy-permission-center)**: a UI for Hyprland's permission rules that keeps them enforced across restarts.
- 🔒 **[VPN Manager](https://github.com/devmobasa/omarchy-vpn-manager)**: tunnel state, routing-leak visibility, and control of NetworkManager and systemd VPNs.
- 🖼️ **[Wallpaper Hub](https://github.com/devmobasa/omarchy-wallpaper-hub)**: a native wallpaper library with Wallhaven search, download, and Omarchy theme integration.

**Automation & screencasting**

- ⚡ **[Context Rules](https://github.com/devmobasa/omarchy-context-rules)**: automates your desktop based on live context like screen sharing, the focused app, time, and battery.
- ⌨️ **[Keycast](https://github.com/devmobasa/omarchy-keycast)**: an on-screen keystroke HUD for screencasts, powered by Hyprland's event bus.

## How I build

- **Native where it matters.** I reach for Rust, C++, QML, or .NET when a tool needs to feel fast and fit the platform.
- **Local first.** Private data and everyday workflows should stay on the machine whenever possible.
- **Keyboard friendly.** Fast paths for the things you do all day, without hiding how anything works.
- **Built from real needs.** Every tool here started as a fix for something that kept getting in my way.
