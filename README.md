# eNotes - Windows Privilege Escalation Lab

![eNotes Banner](https://img.shields.io/badge/Difficulty-Medium-orange) ![Platform](https://img.shields.io/badge/Platform-Windows%2010-blue) ![License](https://img.shields.io/badge/License-Free-green)

A free alternative to **SecNotes** from Hack The Box, designed for practicing Windows penetration testing and privilege escalation.

---

## 📌 Overview

**eNotes** is a vulnerable Windows 10 VM machine that I created as a free alternative to the **SecNotes** machine from Hack The Box. While preparing for certifications like **PNPT** and studying the **Windows Privilege Escalation** course from TCM Security, I found that access to SecNotes requires a paid HTB subscription. 

I decided to recreate the machine with the same vulnerabilities and attack vectors, and share it freely with the community.

---

## 🎯 Purpose

This machine is designed for practicing:

- ✅ **Cross-Site Request Forgery (XSRF/CSRF)** exploitation
- ✅ **Second-Order SQL Injection** attacks
- ✅ **SMB enumeration** and credential harvesting
- ✅ **Web application** pentesting
- ✅ **Windows Subsystem for Linux (WSL)** privilege escalation
- ✅ **PNPT exam preparation** (TCM Security)
- ✅ **OSCP/OCSP-style** practice labs
- ✅ **General Windows exploitation** techniques

---

## 🖥️ Machine Details

| Property | Details |
|----------|---------|
| **Name** | eNotes |
| **OS** | Windows 10 Pro (Build 17134) |
| **Difficulty** | Medium |
| **Services** | IIS, MySQL, SMB, WSL Ubuntu |
| **Vulnerabilities** | XSRF, Second-Order SQLi, Credential Exposure, WSL Priv Esc |
| **Inspired By** | [SecNotes (HTB)](https://0xdf.gitlab.io/2019/01/19/htb-secnotes.html) |

---

## 📥 Download

### File Information

- **Filename:** `eNotes.7z`
- **Compressed Size:** 19.5 GB
- **Extracted Size:** ~22 GB
- **Format:** OVA (compatible with VMware/VirtualBox)
- **SHA256:** `[YOUR_SHA256_HASH_HERE]`

### Download Links

- **Mega.nz:** [Download Link](YOUR_MEGA_LINK)

---

## 🚀 Setup Instructions

### Requirements

- **Hypervisor:** VMware Workstation/Player or VirtualBox
- **RAM:** 4GB minimum (recommended)
- **Disk Space:** 25GB free
- **Network:** NAT or Bridged mode

### Installation Steps

1. Download the VM from the link below  
2. Import it into **VirtualBox** or **VMware**  
3. Configure networking as **NAT** or **Host-Only**  
4. Start the machine and begin enumeration  

---

## 🏁 Flags

- **User Flag:** Located at `C:\Users\enes\Desktop\user.txt`
- **Root Flag:** Located at `C:\Users\Administrator\Desktop\root.txt`

---

## 📚 Learning Resources

This machine is perfect for:

- **TCM Security - Practical Ethical Hacking** course
- **TCM Security - Windows Privilege Escalation** course
- **PNPT (Practical Network Penetration Tester)** certification prep
- **OSCP/OCSP** preparation
- General Windows penetration testing practice

---

## 🛠️ Troubleshooting

### VM won't boot
- Ensure virtualization is enabled in BIOS
- Allocate at least 4GB RAM
- Check VMware/VirtualBox version compatibility

### Can't find VM IP address
```bash
# From attacking machine
sudo netdiscover -r 192.168.1.0/24
# OR
sudo arp-scan -l
```
---

## ⚠️ Disclaimer

This VM is for **educational purposes only**. It contains intentional vulnerabilities and should only be used in isolated lab environments. Do not deploy on production networks.

---

## 🤝 Contributing

Found an issue or have suggestions? Feel free to:
- Open an issue
- Submit a pull request
- Contact me on [LinkedIn](YOUR_LINKEDIN)

---

## 📜 License

This project is free and open-source. You may use, modify, and distribute it freely for educational purposes.

---

## 🙏 Credits

- **Inspired by:** [SecNotes](https://www.hackthebox.com/machines/secnotes) by [0xdf](https://0xdf.gitlab.io/)
- **Course Reference:** [TCM Security - Windows Privilege Escalation](https://academy.tcm-sec.com/)
- **Created by:** [Enes Ismaili](https://www.linkedin.com/in/enes-ismaili/)

---

## 📞 Contact

- **GitHub:** [@enes-ismaili](https://github.com/enes-ismaili)
- **LinkedIn:** https://www.linkedin.com/in/enes-ismaili/

---

