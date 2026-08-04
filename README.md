# 🚀 AetherSSH

AetherSSH is a modern, high-performance, and visually stunning SSH & Server Management client built with **Wails**, **Go**, **React**, and **TailwindCSS**. It provides a premium, all-in-one workspace for developers and sysadmins to manage remote infrastructure effortlessly.

---

## ✨ Features

- 🖥️ **Integrated Terminal Multiplexer:** Built-in xterm.js terminal with multi-tab support. Run and manage multiple concurrent SSH sessions effortlessly in a sleek tabbed interface.
- 🔑 **Smart SSH Keychain:** Centralized secure vault for identities, passwords, and private keys. 
  - **Auto-Discovery:** Automatically scans `~/.ssh/` and parses `~/.ssh/config` to discover and import your existing keys.
  - Supports encrypted private keys (RSA, Ed25519, ECDSA) and password authentication.
- 📁 **Visual SFTP File Browser:** A beautiful graphical file explorer for remote servers. Upload, download, delete, and inspect file permissions without touching the CLI.
- 🌐 **Port Forwarding & Tunneling:** Visually configure Local (`-L`) and Remote (`-R`) port forwarding rules. Monitor tunnel status (Running/Stopped/Error) at a glance.
- 📜 **Command Snippets Library:** Build a personal library of reusable shell scripts, Docker macros, or network diagnostics. Execute them with 1-click on any active terminal session.
- 📊 **Real-time Server Monitoring:** Keep an eye on your remote nodes with real-time visualizations of CPU, RAM, Disk, and Network usage directly within the app.
- 🎨 **Premium Cyberpunk UI:** Designed with a deeply curated dark mode aesthetic, smooth micro-animations, glassmorphism, and responsive flexbox layouts using TailwindCSS and Lucide Icons.

---

## 🛠️ Tech Stack

- **Backend:** Go (Golang) + Wails v2
- **Frontend:** React, TypeScript, Vite
- **Styling:** TailwindCSS
- **Terminal:** xterm.js + xterm-addon-fit
- **Icons:** Lucide React

---

## 📦 Download & Installation

Visit the [Releases](https://github.com/hongsonvu0622-stack/aetherssh-tool/releases) page to download the latest compiled version for macOS. 

*Note: The current releases provide Universal macOS binaries (`darwin/universal`) supporting both Intel and Apple Silicon (M1/M2/M3) Macs.*

---

## 🚀 Building from Source

To build AetherSSH locally, ensure you have Go (1.20+) and Node.js (18+) installed.

1. **Install Wails CLI:**
   ```bash
   go install github.com/wailsapp/wails/v2/cmd/wails@latest
   ```

2. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd aetherssh/ssh-mgmt-go
   ```

3. **Install Frontend Dependencies:**
   ```bash
   cd frontend
   npm install
   cd ..
   ```

4. **Run in Development Mode:**
   ```bash
   wails dev
   ```

5. **Build for Production (macOS Universal):**
   ```bash
   wails build -platform darwin/universal
   ```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

---

## 📝 License

This project is licensed under the MIT License.
