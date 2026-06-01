<div align="center">

# ⚡ NMAPX ⚡

### Automated Reconnaissance & Enumeration Toolkit

> Built with Bash • Powered by Nmap • Inspired by Kali Linux

<br>

![Bash](https://img.shields.io/badge/Bash-Scripting-121011?style=for-the-badge\&logo=gnubash\&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-Network%20Scanner-red?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-Kali_Linux-blue?style=for-the-badge\&logo=linux\&logoColor=white)
![Version](https://img.shields.io/badge/Version-v1.0-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

<br><br>

![Stars](https://img.shields.io/github/stars/maahi-coder/NmapX?style=for-the-badge)
![Forks](https://img.shields.io/github/forks/maahi-coder/NmapX?style=for-the-badge)
![Issues](https://img.shields.io/github/issues/maahi-coder/NmapX?style=for-the-badge)

<br><br>

<a href="https://github.com/maahi-coder/NmapX">
<img src="https://img.shields.io/badge/View_Repository-black?style=for-the-badge&logo=github">
</a>

<a href="https://github.com/maahi-coder/NmapX/stargazers">
<img src="https://img.shields.io/badge/Give_A_Star-yellow?style=for-the-badge">
</a>

<a href="https://github.com/maahi-coder/NmapX/issues">
<img src="https://img.shields.io/badge/Report_Issue-red?style=for-the-badge">
</a>

</div>

---

# 🐉 Overview

NMAPX is a lightweight Bash-based Nmap automation tool created during my cybersecurity learning journey.

Instead of repeatedly typing Nmap commands manually, NMAPX automates common reconnaissance tasks and stores the results in organized report files.

This project was built to improve my understanding of:

* Linux
* Bash Scripting
* Automation
* Nmap
* Network Reconnaissance
* Cybersecurity Workflows

---

# ⚡ Features

* 🎨 Custom Cyber Banner
* 📂 Automatic Report Organization
* 💾 Scan Result Saving
* 🔍 Normal Nmap Scan
* 🛠 Service Version Detection
* 🚀 NSE Script Scan
* 🐧 Linux Friendly
* 📖 Beginner Friendly

---

# 📂 Report Structure

```text
TARGET_IP/
├── normalscan.txt
├── versionscan.txt
└── scriptscan.txt
```

Every scan is automatically saved.

---

# 🚀 Quick Start

Clone the repository:

```bash
git clone https://github.com/maahi-coder/NmapX.git
```

Move into the directory:

```bash
cd NmapX
```

Make executable:

```bash
chmod +x networkchunk.bash
```

Run:

```bash
./networkchunk.bash
```

---

# 🔍 Included Scans

### Normal Scan

```bash
nmap <target>
```

### Version Detection

```bash
nmap -sV <target>
```

### NSE Script Scan

```bash
nmap -sC <target>
```

---

# 🛣 Future Roadmap

* [ ] Ping Scan
* [ ] Full Port Scan
* [ ] OS Detection
* [ ] UDP Scan
* [ ] Interactive Menu
* [ ] Timestamped Reports
* [ ] Advanced NSE Modules

---

# ⚠ Disclaimer

This tool is intended for educational purposes and authorized security testing only.

Always ensure you have permission before scanning systems or networks.

---

# 👨‍💻 Author

## Mahi Mahenthiran

Cybersecurity Student | Cloud Security Learner | Bash Scripting Enthusiast

> Learning by building. Improving through automation.

---

<div align="center">

## ⭐ Star the repository if you found it useful.

### Happy Scanning 🚀

</div>
