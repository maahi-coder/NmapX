<div align="center">

# ⚡ NMAPX ⚡

### Automated Nmap Reconnaissance & Enumeration Toolkit

> Built with Bash • Powered by Nmap • Designed for Linux

<br>

![Bash](https://img.shields.io/badge/Bash-Scripting-121011?style=for-the-badge\&logo=gnubash\&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-Network%20Scanner-red?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-Compatible-blue?style=for-the-badge\&logo=linux\&logoColor=white)
![Version](https://img.shields.io/badge/Version-v1.0-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

<br>

![Stars](https://img.shields.io/github/stars/maahi-coder/NmapX?style=for-the-badge)
![Forks](https://img.shields.io/github/forks/maahi-coder/NmapX?style=for-the-badge)
![Issues](https://img.shields.io/github/issues/maahi-coder/NmapX?style=for-the-badge)

<br><br>

<a href="https://github.com/maahi-coder/NmapX">
<img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github">
</a>

<a href="https://github.com/maahi-coder/NmapX/stargazers">
<img src="https://img.shields.io/badge/Give_A_Star-FFD700?style=for-the-badge">
</a>

<a href="https://github.com/maahi-coder/NmapX/issues">
<img src="https://img.shields.io/badge/Report_Issue-red?style=for-the-badge">
</a>

<br><br>

# 🐧 Supported Linux Distributions

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge\&logo=kalilinux\&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge\&logo=ubuntu\&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge\&logo=debian\&logoColor=white)
![Parrot OS](https://img.shields.io/badge/Parrot_OS-15E0ED?style=for-the-badge)
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge\&logo=archlinux\&logoColor=white)

<br>

![Fedora](https://img.shields.io/badge/Fedora-51A2DA?style=for-the-badge\&logo=fedora\&logoColor=white)
![Linux Mint](https://img.shields.io/badge/Linux_Mint-87CF3E?style=for-the-badge\&logo=linuxmint\&logoColor=white)
![openSUSE](https://img.shields.io/badge/openSUSE-73BA25?style=for-the-badge\&logo=opensuse\&logoColor=white)
![Manjaro](https://img.shields.io/badge/Manjaro-35BF5C?style=for-the-badge\&logo=manjaro\&logoColor=white)
![Rocky Linux](https://img.shields.io/badge/Rocky_Linux-10B981?style=for-the-badge)

</div>

---

# 🎯 About NMAPX

NMAPX is a lightweight Bash-based Nmap automation tool built as part of my cybersecurity learning journey.

Instead of manually typing multiple Nmap commands every time, NMAPX automates common reconnaissance tasks, organizes scan results, and saves reports automatically.

The project was created to improve my Bash scripting, Linux, automation, and cybersecurity skills through hands-on practice.

---

# ⚡ Features

* 🎨 Custom Cyber Banner
* 🔍 Normal Nmap Scan
* 🛠 Service Version Detection Scan
* 🚀 NSE Script Scan
* 📂 Automatic Folder Creation
* 💾 Automatic Report Saving
* 🐧 Linux Friendly
* 📖 Beginner Friendly
* ⚡ Lightweight & Fast

---

# 📦 Installation

Clone the repository:

```bash
git clone https://github.com/maahi-coder/NmapX.git
```

Move into the project directory:

```bash
cd NmapX
```

Give execution permission:

```bash
chmod +x networkchunk.bash
```

Run the tool:

```bash
./networkchunk.bash
```

---

# 🚀 How To Use

Start the tool:

```bash
./networkchunk.bash
```

Example:

```text
[+] do you want to do any scans (yes/no): y

[+] enter your target ip address (ex:8.8.8.8): scanme.nmap.org
```

NMAPX will automatically:

1. Check whether Nmap is installed
2. Create a target folder
3. Run Normal Scan
4. Run Version Detection Scan
5. Run NSE Script Scan
6. Save all reports

---

# 📂 Output Structure

After scanning:

```text
scanme.nmap.org/
├── normalscan.txt
├── versionscan.txt
└── scriptscan.txt
```

All reports are saved automatically for later analysis.

---

# 🔍 Included Scans

## Normal Scan

```bash
nmap <target>
```

Discovers open ports and basic service information.

---

## Version Detection

```bash
nmap -sV <target>
```

Detects service versions running on the target.

---

## NSE Script Scan

```bash
nmap -sC <target>
```

Runs Nmap's default scripting engine scripts.

---

# 🖥 Example Workflow

```text
User Starts NMAPX
        ↓
Enter Target
        ↓
Folder Created
        ↓
Normal Scan
        ↓
Version Scan
        ↓
Script Scan
        ↓
Reports Saved
        ↓
Finished
```

---

# 🛣 Roadmap

* [ ] Ping Scan
* [ ] OS Detection
* [ ] Full Port Scan
* [ ] UDP Scan
* [ ] Interactive Menu System
* [ ] Timestamped Reports
* [ ] Advanced NSE Modules
* [ ] Better Error Handling

---

# 🧠 Why I Built This

While learning Nmap and Linux, I noticed that I repeatedly typed the same commands.

Instead of doing everything manually, I built NMAPX to automate the process and gain practical experience with Bash scripting and cybersecurity workflows.

This project represents my learning-by-building approach to cybersecurity.

---

# ⚠ Disclaimer

This tool is intended only for:

* Educational Purposes
* Personal Labs
* Learning Environments
* Authorized Security Testing

Always obtain permission before scanning systems or networks.

---

# 👨‍💻 Author

## Mahi Mahenthiran

Cybersecurity Student • Cloud Security Learner • Bash Scripting Enthusiast

> Learning by Building • Improving by Automating

---

<div align="center">

## ⭐ If you found this project useful, consider giving it a star.

### 🚀 Happy Scanning with NMAPX 🚀

</div>
