
# Home Cybersecurity Lab Setup

This lab is designed for hands on training in ethical hacking, network
security, and cybersecurity ops. The environment is isolated from
my personal network to ensure security and anonymity.

## Hardware

Lenovo laptop (Windows 10)
- Main lab machine used for running security tools and VMs

Asus Router (Lab Network)
- Provides an isolated network for cybersecurity lab work

Raspberry Pi 5
- Lightweight Linux system for IoT projects, scripting, or network monitoring

Alpha AWUS036ACH Wi-fi Adapter
- Used for wireless packet capture and pentesting with Kali Linux

Jetson Orin Nano (planned)
- Intended for future AI-based security projects like camera monitoring

Ethernet cables
- Used to ensure wired, secure connections within the lab

## Software and Operating Systems

Windows 10
- Base OS for the Lenovo lab laptop

Kali Linux (Live or VM)
- Used for penetration testing and ethical hacking tools

Ubuntu Linux
- General-purpose Linux environment for scripting and tools

ProtonVPN
- Dedicated VPN for anonymized lab traffic

Git
- Used for version control of scripts and configuration files

GitHub
- Repository hosting for lab documentation and project files

## Tools and Utilities

Nmap
- Scanning and mapping networks and ports

Wireshark
- Capturing and analyzing network traffic

Metasploit Framework
- Used for learning and testing exploits

Burp Suite (Community Edition)
- Tool for testing web application security

Python
- Used for creating automation scripts and testing tools

Command-Line Tools (Bash, Powershell)
- For scripting, scanning, and system control

## Security Practices

- Lab network is completely isolated from personal network
- Custom SSID is used; guest networks are disabled
- NordVPN is used only on personal Macbook, not lab machine
- ProtonVPN is dedicated for lab systems only
- Lab and personal user accounts are kept separate

## Goals of the Lab

- Develop skills in pentesting and vulnerability assessment
- Learn network security, traffic analysis, and firewall evasion
- Buid custom scripts for automation and reporting
- Document tools, configurations, and experiments in GitHub

This is a total work in progress and will evolve as I continue my studies 
in computer science with a focus in cybersecurity.

# cybersecurity-lab
My personal cybersecurity lab for hands on training and tool testing
# 🛡️ Cybersecurity Lab

This repository documents my hands-on work in cybersecurity as part of my academic and personal learning journey. It includes tools, scripts, configurations, and notes related to ethical hacking, penetration testing, and system hardening.



## 📁 Folder Structure

| Folder            | Description |
|-------------------|-------------|
| `nmap-scans/`     | Nmap scan outputs, scripts, and command examples |
| `wifi-attacks/`   | Logs, tools, and scripts used in Wi-Fi security testing |
| `metasploit/`     | Payloads, exploit configs, and post-exploitation notes |
| `python-scripts/` | Custom scripts for automation, scanning, or parsing |
| `writeups/`       | Documentation of lab exercises, CTFs, or reports |
| `screenshots/`    | Images showing terminal output or attack results |
| `config-files/`   | Configuration files for routers, firewalls, services, etc. |

---

## 📝 Notes

- This lab is built on real-world experimentation in a safe, isolated environment.
- Tools used include `nmap`, `aircrack-ng`, `Wireshark`, `Metasploit`, and custom Python scripts.
- All activities are conducted within ethical and legal boundaries.

---

## 🔐 Disclaimer

This repository is intended for educational purposes only. All testing is performed on systems I own or have explicit permission to test. Unauthorized access to systems is illegal and unethical.

