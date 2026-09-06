# 🔐 Cybersecurity Lab Environment Setup

A hands-on cybersecurity lab built with **Oracle VirtualBox** and **Kali Linux** for practicing networking, reconnaissance, vulnerability assessment, and authorized security testing.

---

## 🛡️ Skills & Technologies

### Cybersecurity

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-404040?style=flat-square)
![Vulnerability Assessment](https://img.shields.io/badge/Vulnerability%20Assessment-C00000?style=flat-square)
![Penetration Testing](https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square)
![Ethical Hacking](https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square)

### Operating Systems & Virtualization

![Kali Linux](https://img.shields.io/badge/Kali%20Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-000000?style=flat-square&logo=linux&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=flat-square)

### Networking

![Networking](https://img.shields.io/badge/Networking-238F89?style=flat-square)
![NAT Network](https://img.shields.io/badge/NAT%20Network-238F89?style=flat-square)
![DNS](https://img.shields.io/badge/DNS-0070C0?style=flat-square)
![Nmap](https://img.shields.io/badge/Nmap-0070C0?style=flat-square)

### Development & Tools

![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

---

## 📖 Project Overview

This project focuses on building my own **virtual cybersecurity and penetration-testing lab** using Oracle VirtualBox and Kali Linux.

The goal of this lab is to create a safe and controlled environment where I can practice cybersecurity skills such as:

- Network scanning
- Reconnaissance
- Vulnerability assessment
- Penetration testing
- Linux administration
- Network troubleshooting

I configured the lab on a private virtual network so additional virtual machines can be added in the future and used as controlled targets for **authorized security testing**.

---

## 🎯 Objectives

The main objectives of this cybersecurity lab are to:

- Install and configure **Oracle VirtualBox**.
- Install and configure **Kali Linux** as a virtual machine.
- Create a private **NAT Network** for the lab environment.
- Configure network connectivity for the Kali Linux VM.
- Assign and verify the Kali Linux IP address.
- Test network connectivity and DNS resolution.
- Create a clean **VirtualBox snapshot** for recovery.
- Document the setup process with screenshots and notes.
- Prepare the environment for future cybersecurity labs.

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| **Kali Linux** | Cybersecurity testing and Linux environment |
| **Oracle VirtualBox** | Virtual machine management |
| **7-Zip** | Extracting compressed lab files |
| **NAT Network** | Private virtual networking |
| **Nmap** | Network scanning |
| **GitHub** | Project documentation and version control |

---

## 📌 Project Purpose

This project demonstrates the setup of a controlled virtual cybersecurity environment using Kali Linux and Oracle VirtualBox.

The environment will be used for future hands-on exercises involving networking, vulnerability assessment, penetration testing, and cybersecurity analysis.

---

# 🪜 Lab Setup

## Step 1 — Download & Install 7-Zip

**Resource:**  
https://7-zip.org/download.html

**Purpose:**  
I used 7-Zip to extract compressed files needed for my virtual lab environment.

---

## Step 2 — Download & Install VirtualBox

**Resource:**  
https://virtualbox.org/wiki/Downloads

<img width="478" alt="VirtualBox installation" src="https://github.com/user-attachments/assets/18b685a4-21fa-4dd4-a70c-d63d570d8330" />

**Purpose:**  
I installed Oracle VirtualBox to create and manage the virtual machines used in my cybersecurity lab.

---

## Step 3 — Download & Install Kali Linux

**Resource:**  
https://kali.org/get-kali

<img width="1120" alt="Kali Linux installation" src="https://github.com/user-attachments/assets/99af80ce-54c3-48e7-8784-c0772dff0eeb" />

**Purpose:**  
I installed Kali Linux as the primary cybersecurity virtual machine for security testing, networking, troubleshooting, and future labs.

---

## Step 4 — Configure the Virtual Network

**Purpose:**  
I configured the VirtualBox network settings for the Kali Linux VM. The private network provides a controlled environment for future cybersecurity testing.

<img width="1859" alt="NAT Network configuration" src="https://github.com/user-attachments/assets/3f636665-0c7b-4909-91db-5bd69c4957d8" />

<img width="557" alt="Virtual machine network settings" src="https://github.com/user-attachments/assets/918ce7b7-3f88-4678-a7d7-4ea20e1a18ab" />

---

## Step 5 — Start Kali Linux

**Purpose:**  
After completing the installation, I started the Kali Linux virtual machine and verified that the operating system was working correctly.

<img width="1285" alt="Kali Linux desktop" src="https://github.com/user-attachments/assets/7145b8cb-2b2c-4ffa-8432-3f4f4191c3b6" />

---

## Step 6 — Configure the Kali Linux Network

**Purpose:**  
I configured the Kali Linux network settings and verified the IP configuration. A consistent IP address makes it easier to document and reference the Kali VM during future exercises.

<img width="699" alt="Kali Linux IP configuration" src="https://github.com/user-attachments/assets/ae8e246a-33ad-4417-a47e-a3524b9b97b8" />

---

## Step 7 — Check the IP Address

**Purpose:**  
I used the Kali Linux terminal to check the assigned IP address.

**Command used:**

```bash
ip a
```

This allowed me to verify the network interface and confirm that the virtual machine received an IP address.

---

## Step 8 — Verify Network Connectivity

<img width="729" alt="Network verification" src="https://github.com/user-attachments/assets/be805ba9-35cc-470d-a67a-57d64e1264fe" />

**Purpose:**  
I verified that the network configuration was working correctly before completing the lab setup.

---

## Step 9 — Create a Clean VM Snapshot

**Purpose:**  
After completing the initial configuration, I created a VirtualBox snapshot to establish a clean baseline for the laboratory.

If a future exercise changes or damages the VM configuration, I can restore the machine to this known-good state.

<img width="1049" alt="VirtualBox snapshot" src="https://github.com/user-attachments/assets/e9ef2f5b-720d-484d-b85d-94ae89c4c391" />

---

# ⚠️ Problems Encountered & Solutions

### Problem 1 — Kali Linux Could Not Connect to the Network

**Problem:**  
Kali Linux was not receiving the expected IP address after configuring the virtual network.

**Solution:**  
I checked the VirtualBox network adapter settings and verified that the correct NAT Network was selected. I then restarted the network connection and confirmed the IP address using `ip a`.

---

### Problem 2 — Virtual Machine Settings Needed to Be Corrected

**Problem:**  
The virtual machine did not initially have the correct memory and network settings for the lab.

**Solution:**  
I reviewed the VirtualBox settings and adjusted the VM resources and network adapter configuration before starting the machine again.

---

### Problem 3 — Needed a Recovery Point

**Problem:**  
I wanted to make sure I could restore the Kali Linux environment if a future cybersecurity lab caused configuration problems.

**Solution:**  
After completing the basic setup, I created a clean VirtualBox snapshot. This provides a recovery point that can be used to return the VM to its working configuration.

---

# 📚 What I Learned

Through this project, I learned how to build and configure a virtual cybersecurity environment using **VirtualBox and Kali Linux**.

The project helped me develop a better understanding of:

### 1. NAT vs. NAT Network

I learned that **NAT** and **NAT Network** are different VirtualBox networking options.

A NAT Network allows multiple virtual machines to communicate with each other while also providing external network connectivity. This makes it useful for building a multi-machine cybersecurity lab.

### 2. Virtual Machine Networking

I learned how VirtualBox network adapters connect virtual machines to different types of networks and how network settings affect communication.

### 3. IP Address Configuration

I learned how to check and verify network information in Kali Linux using commands such as:

```bash
ip a
```

This helped me understand IP addresses, network interfaces, subnetting, gateways, and DNS configuration.

### 4. Virtual Machine Snapshots

I learned how to create a **VirtualBox snapshot** after completing the initial lab setup.

A clean snapshot provides a known-good recovery point that I can use if a future cybersecurity exercise changes or breaks the virtual machine.

### 5. Troubleshooting

I gained hands-on experience troubleshooting VirtualBox and network configuration issues.

I learned to check network adapter settings, verify the assigned IP address, test connectivity, and make configuration changes when necessary.

### 6. Documentation

I learned that documenting technical work is an important part of cybersecurity.

I documented the setup process using **screenshots, commands, problems, and solutions** so I can review my work and recreate the environment in the future.

### 7. Building a Cybersecurity Lab

Most importantly, I learned how to create a controlled environment where I can continue developing hands-on cybersecurity skills.

---

# 🔐 Security & Ethical Use

This laboratory was created strictly for **educational and authorized security testing purposes**.

All security testing should only be performed against systems and networks that I own or have explicit permission to test.

---

# 🔗 Tools & Resources

- **7-Zip:** https://7-zip.org/download.html
- **Oracle VirtualBox:** https://virtualbox.org/wiki/Downloads
- **Kali Linux:** https://kali.org/get-kali
- **GitHub:** https://github.com/

---

# 👤 Author

**Jameel Robinson**

Cybersecurity Professional | SOC Analyst | Cybersecurity Analyst

**LinkedIn:**  
https://www.linkedin.com/in/jameel-robinson-102560295

---

# 📌 Project Information

| Item | Details |
|---|---|
| **Project** | Virtual Cybersecurity & Penetration Testing Lab |
| **Platform** | Oracle VirtualBox |
| **Operating System** | Kali Linux |
| **Network** | Private NAT Network |
| **Focus** | Cybersecurity Lab Setup & Virtual Networking |
| **Author** | Jameel Robinson |
