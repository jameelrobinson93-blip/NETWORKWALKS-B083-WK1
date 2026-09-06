# 🔐 Cybersecurity Lab Environment Setup
## 🛡️ Cybersecurity Skills

![Cybersecurity](https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square\&labelColor=C00000)
![VirtualBox](https://img.shields.io/badge/VirtualBox-7.2-0070C0?style=flat-square\&labelColor=000000)
![Kali Linux](https://img.shields.io/badge/Kali%20Linux-2026.2-E87500?style=flat-square\&labelColor=000000\&logo=kalilinux\&logoColor=white)
![Linux](https://img.shields.io/badge/Skill-Linux-404040?style=flat-square\&labelColor=C00000)
![Networking](https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square\&labelColor=000000)
![Penetration Testing](https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square\&labelColor=000000\&logo=kalilinux\&logoColor=white)
![Virtualization](https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square\&labelColor=C00000)
![GitHub](https://img.shields.io/badge/GitHub-404040?style=flat-square\&labelColor=0070C0\&logo=github\&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square\&labelColor=C000000\&logo=kalilinux\&logoColor=white)
![NetworkWalks](https://img.shields.io/badge/NetworkWalks-404040?style=flat-square\&labelColor=C000000)
![Ethical Hacking](https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square\&labelColor=000000\&logo=kalilinux\&logoColor=white)

## 📖 Project Overview

This project is focused on building my own **virtual cybersecurity and penetration-testing lab** using Oracle VirtualBox and Kali Linux.

The goal of this lab is to create a safe and controlled environment where I can practice cybersecurity skills such as **network scanning, reconnaissance, vulnerability assessment, and penetration testing**.

I configured the lab using a private virtual network so I can add additional virtual machines in the future and use them as controlled targets for **authorized security testing**. This environment will allow me to continue developing my hands-on cybersecurity skills without affecting real-world systems or networks.

---
## 🎯 Objectives

The main objectives of this cybersecurity lab are to:

* Install and configure **Oracle VirtualBox**.
* Install and configure **Kali Linux** as a virtual machine.
* Create a private **NAT Network** for the cybersecurity lab environment.
* Configure network connectivity between the virtual machine and lab network.
* Assign and verify a consistent IP address for the Kali Linux VM.
* Test network connectivity and DNS resolution.
* Create a clean **VM snapshot** for recovery and future testing.
* Document each step of the lab setup with screenshots and notes.
* Build a controlled environment for future cybersecurity labs and security testing.

## 🛠️ Technologies & Tools

* Kali Linux
* Oracle VirtualBox
* NAT Network
* Linux Networking
* DNS
* Virtual Machines
* GitHub
* Nmap

## 📌 Project Purpose

This project demonstrates the setup of a controlled virtual cybersecurity environment using Kali Linux and Oracle VirtualBox. The environment will be used for future hands-on exercises involving networking, vulnerability assessment, penetration testing, and cybersecurity analysis.

---

# 🪜 Lab Setup

## Step 1 — Install VirtualBox

I installed Oracle VirtualBox to create and manage my virtual machines.

### Screenshot

![VirtualBox](screenshots/01-virtualbox.png)

---

## Step 2 — Install Kali Linux

I installed Kali Linux as my primary cybersecurity virtual machine.

Kali Linux will be used for security testing, networking, troubleshooting, and cybersecurity labs.

### Screenshot

![Kali Installation](screenshots/02-kali-installation.png)

---

## Step 3 — Start Kali Linux

After completing the installation, I started the Kali Linux virtual machine and verified that the operating system was working correctly.

### Screenshot

![Kali Desktop](screenshots/03-kali-desktop.png)

---

## Step 4 — Configure Network Settings

I configured the network settings for the Kali Linux virtual machine through VirtualBox.

The network configuration allows the virtual machine to communicate with the network while keeping my cybersecurity testing environment controlled.

### Screenshot

![Network Settings](screenshots/04-network-settings.png)

---

## Step 5 — Check the IP Address

I used the Kali terminal to check the assigned IP address.

Command used:

```bash
ip a
