<div align="center">

<img src="https://www.kali.org/images/kali-logo.svg" width="220">

#  NMAPX

### Automated Nmap Scanning Made Simple

<p align="center">

![Bash](https://img.shields.io/badge/Bash-Scripting-121011?style=for-the-badge\&logo=gnubash\&logoColor=white)

![Nmap](https://img.shields.io/badge/Nmap-Network%20Scanner-red?style=for-the-badge)

![Linux](https://img.shields.io/badge/Linux-Kali_Linux-blue?style=for-the-badge\&logo=linux\&logoColor=white)

![Version](https://img.shields.io/badge/Version-v1.0-orange?style=for-the-badge)

![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

</p>

<p align="center">

<a href="https://github.com/maahi-coder/NmapX">
<img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github">
</a>

<a href="https://github.com/maahi-coder/NmapX/stargazers">
<img src="https://img.shields.io/badge/Give_A_Star-FFD700?style=for-the-badge">
</a>

<a href="https://github.com/maahi-coder/NmapX/issues">
<img src="https://img.shields.io/badge/Report_Issue-red?style=for-the-badge">
</a>

<a href="https://github.com/maahi-coder/NmapX/fork">
<img src="https://img.shields.io/badge/Fork_Project-blue?style=for-the-badge">
</a>

</p>

<p align="center">

![Stars](https://img.shields.io/github/stars/maahi-coder/NmapX?style=for-the-badge)

![Forks](https://img.shields.io/github/forks/maahi-coder/NmapX?style=for-the-badge)

![Issues](https://img.shields.io/github/issues/maahi-coder/NmapX?style=for-the-badge)

</p>

</div>

---

# 🎯 About NMAPX

NMAPX is a Bash-based Nmap automation tool built during my cybersecurity learning journey.

While practicing reconnaissance and enumeration, I noticed that I repeatedly executed the same Nmap commands.

Instead of manually running every scan one by one, I decided to automate the process using Bash scripting and create a lightweight tool that performs multiple scans automatically while saving the results in an organized structure.

This project helped me learn:

* Linux
* Bash Scripting
* Automation
* Nmap
* File Handling
* Basic Cybersecurity Workflow

---

# ⚡ Features

✅ Beautiful Custom Banner

✅ Colorful Terminal Output

✅ Nmap Dependency Checking

✅ Automatic Folder Creation

✅ Automatic Report Generation

✅ Normal Nmap Scan

✅ Service Version Detection

✅ NSE Script Scan

✅ Beginner Friendly

✅ Lightweight

---

# 🔍 Scan Modules

## 1️⃣ Normal Scan

```bash
nmap <target>
```

Discovers:

* Open Ports
* Running Services
* Basic Host Information

---

## 2️⃣ Version Detection Scan

```bash
nmap -sV <target>
```

Detects:

* Service Versions
* Software Information

---

## 3️⃣ NSE Script Scan

```bash
nmap -sC <target>
```

Runs:

* Default Nmap Scripts
* Basic Enumeration Scripts

---

# 📂 Generated Output

After scanning a target:

```text
8.8.8.8/
├── normalscan.txt
├── versionscan.txt
└── scriptscan.txt
```

Each scan result is automatically saved for future analysis.

---

# 🚀 Installation

Clone Repository:

```bash
git clone https://github.com/maahi-coder/NmapX.git
```

Move Into Directory:

```bash
cd NmapX
```

Make Script Executable:

```bash
chmod +x networkchunk.bash
```

Run Tool:

```bash
./networkchunk.bash
```

---

# 🖥 Preview

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

# 🛣 Roadmap

* [ ] Ping Scan
* [ ] OS Detection
* [ ] Full Port Scan
* [ ] UDP Scan
* [ ] Menu Based Interface
* [ ] Export Reports
* [ ] Timestamped Results
* [ ] Advanced NSE Modules
* [ ] Better Error Handling

---

# 🧠 Why This Project Exists

I believe the best way to learn cybersecurity is by building.

Instead of only watching videos or reading documentation, I wanted to create something practical.

NMAPX started as a small Bash scripting exercise and slowly became one of my first cybersecurity automation projects.

---

# ⚠ Disclaimer

This tool is intended for:

* Educational Purposes
* Home Labs
* Personal Learning
* Authorized Security Assessments

Always obtain proper authorization before scanning systems or networks.

---

# 👨‍💻 Author

## Mahi Mahenthiran

Cybersecurity Student

Cloud Security Learner

Bash Scripting Enthusiast

Future Security Engineer

---

<div align="center">

## ⭐ If you found this project useful, consider giving it a star.

### Thank you for visiting NMAPX 🚀

</div>
