<div align="center">

# 🚀 NmapX

### Simple • Fast • Automated Nmap Scanning with Bash

<p align="center">

![Bash](https://img.shields.io/badge/Bash-Scripting-121011?style=for-the-badge\&logo=gnubash\&logoColor=white)

![Nmap](https://img.shields.io/badge/Nmap-Network%20Scanner-red?style=for-the-badge)

![Linux](https://img.shields.io/badge/Linux-Kali_Linux-blue?style=for-the-badge\&logo=linux\&logoColor=white)

![Version](https://img.shields.io/badge/Version-v1.0-orange?style=for-the-badge)

![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

</p>

<p align="center">

![Stars](https://img.shields.io/github/stars/maahi-coder/NmapX?style=for-the-badge)

![Forks](https://img.shields.io/github/forks/maahi-coder/NmapX?style=for-the-badge)

![Issues](https://img.shields.io/github/issues/maahi-coder/NmapX?style=for-the-badge)

</p>

</div>

---

## 📖 About

NmapX is a Bash-based Nmap automation tool created as part of my cybersecurity learning journey.

While practicing network reconnaissance, I found myself repeatedly typing the same Nmap commands. To improve my Bash scripting skills and automate repetitive tasks, I built NmapX.

The tool provides a simple interface, colorful output, automatic report generation, and multiple scan types without requiring users to remember complex commands.

---

## ✨ Features

* 🎨 Custom ASCII Banner
* ⚡ Fast Nmap Automation
* 📂 Automatic Folder Creation
* 💾 Automatic Scan Result Saving
* 🌐 Normal Nmap Scan
* 🔍 Service Version Detection
* 🛠 NSE Script Scan
* 🐧 Linux Friendly
* 📖 Beginner Friendly

---

## 🔍 Available Scans

### Normal Scan

```bash
nmap <target>
```

Discovers open ports and basic network information.

### Service Version Detection

```bash
nmap -sV <target>
```

Detects versions of running services.

### NSE Script Scan

```bash
nmap -sC <target>
```

Runs Nmap's default NSE scripts.

---

## 📂 Output Structure

After scanning a target, NmapX automatically creates a folder and stores reports:

```text
8.8.8.8/
├── normalscan.txt
├── versionscan.txt
└── scriptscan.txt
```

No need to manually save scan results.

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/maahi-coder/NmapX.git
```

Move into the project directory:

```bash
cd NmapX
```

Give execute permission:

```bash
chmod +x networkchunk.bash
```

Run the tool:

```bash
./networkchunk.bash
```

---

## 📸 Preview

```text
 ██████   █████                                     █████ █████
░░██████ ░░███                                     ░░███ ░░███
 ░███░███ ░███  █████████████    ██████   ████████  ░░███ ███
 ░███░░███░███ ░░███░░███░░███  ░░░░░███ ░░███░░███  ░░█████
 ░███ ░░██████  ░███ ░███ ░███   ███████  ░███ ░███   ███░███
 ░███  ░░█████  ░███ ░███ ░███  ███░░███  ░███ ░███  ███ ░░███
 █████  ░░█████ █████░███ █████░░████████ ░███████  █████ █████
```

---

## 🎯 Why I Built This

This project was created to:

* Learn Bash scripting
* Automate repetitive Nmap commands
* Practice Linux fundamentals
* Improve cybersecurity skills
* Build real projects while learning

Rather than only watching tutorials, I wanted to learn by building something useful.

---

## 🛣 Roadmap

* [ ] Ping Scan
* [ ] OS Detection
* [ ] Menu-Based Interface
* [ ] Timestamped Reports
* [ ] Custom Scan Selection
* [ ] Better Error Handling
* [ ] Additional NSE Scan Modules

---

## ⚠️ Disclaimer

This tool is intended for:

* Educational Purposes
* Personal Labs
* Authorized Security Testing

Always obtain permission before scanning any network or system.

---

## 👨‍💻 Author

### Mahi Mahenthiran

Cybersecurity Student • Cloud Security Learner • Bash Scripting Enthusiast

> "Every expert was once a beginner. NmapX is one of the projects I built while learning cybersecurity and automation."

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a star.

### 🚀 More features coming soon.

</div>
