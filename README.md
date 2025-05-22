# 🚦 PulseLAN

**PulseLAN** is a lightweight, zero-config messaging and file-sharing tool for local networks. Think of it as Airdrop for the LAN — cross-platform, terminal-friendly, and open-source.

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=flat&logo=python)
![License](https://img.shields.io/badge/License-GPLv3-blue.svg)
![Status](https://img.shields.io/badge/Status-Alpha-red)

---

## 🌐 What It Does

- 🔍 **Auto-discovers peers** on your LAN using UDP broadcasts
- 💬 **Real-time messaging** between any two LAN devices
- 🛠️ Built in **Python** with minimal dependencies

---

## ✨ Features

✅ Zero configuration (just run it!)

✅ Real-time chat with any discovered peer

✅ Peer discovery via LAN broadcast

---

## 🔜 Planned Features (Coming Soon)

🗂️ **File Sharing:** Send any file to another peer on the LAN  
📥 **Drag & Drop UI (If I get round to doing it):** Simple GUI for file transfers  
📦 **Portable Build:** Bundled app for Windows/macOS/Linux  
🔐 **Encrypted Mode:** Opt-in E2E message encryption  
📡 **Multicast Upgrade:** Improve discovery reliability  
📜 **Message History:** Per-peer chat logs

---

## 🚀 Getting Started

```bash
git clone https://github.com/Eternal-Monke/PulseLAN.git
cd pulselan
python3 -m venv appenv
./sendsoc
```

## 💻 Usage

```bash
Enter your name: Sakuta
Broadcasted: 'Sakuta @ 192.168.1.23'

-- Type the number of a peer to message, or enter 'list' or 'l' to see peers --
> list
1) Mai @ 192.168.1.45

> 1
Enter message: I saw a bunny girl today
Message Sent!
```

## 🤝 Contributing

Want to help build the file sharing engine or GUI?
Feel free to fork, open an issue, or make a pull request!

## 📜 License

This project is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html) © 2025 [Eternal-Monke](http://github.com/Eternal-Monke)
