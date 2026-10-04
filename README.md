# 🖥️ Aero Linux Native Applications Suite

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0b0e,100:00f2fe&height=200&section=header&text=Aero%20Apps%20Suite&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=45%20Native%20Zero-Terminal%20GTK3%20%2F%20GJS%20Developer%20Applications&descAlignY=62&descAlign=50" width="100%"/>

<br/>

[![Apps Count](https://img.shields.io/badge/Applications-45_Native_GTK3-0891b2?style=for-the-badge&logo=gnome&logoColor=white)](https://github.com/aero-linux/apps)
[![Aero Linux Main](https://img.shields.io/badge/Core_OS-aero--linux%2Faero--linux-3178C6?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/aero-linux/aero-linux)
[![License: MIT](https://img.shields.io/badge/License-MIT-4EAA25?style=for-the-badge)](LICENSE)

</div>

---

### 🚀 Overview
The standalone repository for the **45 zero-terminal GTK3 developer applications** powering **Aero Linux**. Built from first principles to give software engineers instant visual control over low-level Linux workflows without sacrificing terminal speed or RAM.

### 📦 Applications Directory & Classification

#### 🛠️ Developer & Engineering Workflows
- `aero-ai-gui` — Hardware-accelerated local LLM runner (Ollama/Llama.cpp switchboard).
- `aero-api-gui` — Zero-dependency desktop REST API tester and endpoint inspector.
- `aero-docker-gui` — Real-time container visualizer, image prune, and log stream viewer.
- `aero-git-gui` — Instant visual branch graph, staged diffs, and conflict resolver.
- `aero-diff-gui` — Visual two-way file and folder diff comparator.
- `aero-markdown-gui` — Instant real-time live preview editor for Markdown and GitHub math.
- `aero-sandbox-gui` — 1-click ephemeral Bubblewrap / Firejail isolation runner.
- `aero-qr-gui` — WiFi and text payload QR code generator / scanner.

#### 🌐 Network, Ports & Security
- `aero-ports-gui` — Real-time listening sockets, process PID mappings, and kill triggers.
- `aero-firewall-gui` — Visual UFW firewall rules manager and connection blocker.
- `aero-tunnel-gui` — Local reverse tunnel and port forwarder manager (Cloudflare / SSH).
- `aero-ssl-gui` — Local self-signed SSL / TLS certificate builder and inspector.
- `aero-connect-gui` — Cross-device local network file drop and transfer hub.
- `aero-wifi` & `aero-bluetooth` — Lightweight network and peripheral connection panels.

#### ⚡ Performance, Diagnostics & Hardware
- `aero-benchmark-gui` — Multi-threaded CPU, RAM, and NVMe disk benchmark suite.
- `aero-cleaner-gui` — Package cache cleaner, thumbnail purge, and orphaned dependency remover.
- `aero-disk-gui` — Visual filesystem disk usage analyzer and largest file finder.
- `aero-logs-gui` — Real-time `journalctl` and `dmesg` kernel log analyzer.
- `aero-services-gui` — Systemd service controller (start, stop, disable, restart).
- `aero-snapshots-gui` — Btrfs / Timeshift system restore point manager.

#### 🎨 Workspace & Desktop Ergonomics
- `aero-quick-settings` — Top-bar quick control center for audio, brightness, and power modes.
- `aero-nightlight-gui` — Blue light filter scheduler with gamma adjustment.
- `aero-color-gui` — Pixel-level screen color picker and hex palette copier.
- `aero-recorder-gui` — Low-latency screen recorder and audio capture utility.
- `aero-gamehub` — Proton-GE and WinePrefix runner for gaming and Windows emulation.
- `aero-notes-gui` — Persistent scratchpad and quick code snippet buffer.

---

### 💻 Running Standalone

To run any application standalone on any Debian/Ubuntu/Mint environment:

```bash
# Ensure GTK3 Python bindings are installed
sudo apt install python3-gi python3-gi-cairo gir1.2-gtk-3.0

# Execute any app directly
./bin/aero-api-gui
./bin/aero-ports-gui
./bin/aero-docker-gui
```

---

<div align="center">
  <p>Maintained by the <b><a href="https://github.com/aero-linux">Aero Linux Project</a></b> & <b><a href="https://github.com/ronitgupta138">@ronitgupta138</a></b></p>
</div>
