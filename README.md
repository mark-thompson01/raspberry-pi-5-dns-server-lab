# Raspberry Pi 5 DNS Server Lab 🧠  
*Part of the MTPortfolio — Hands-On IT Labs, Networking, Scripting, Cybersecurity, and Beyond*

## 🧩 Overview
This lab demonstrates how I configured a **Raspberry Pi 5** as a functional **DNS server** within my home-lab subnet.  
It showcases core **System Administration** and **Networking** skills, including static IP configuration, DNS service management, Linux hardening, and automation using Bash and cron.

The goal: show how a small, low-cost device can provide critical infrastructure services reliably and securely.

---

## 🎯 Objectives
- Convert a Raspberry Pi 5 into a DNS server using either **BIND9** or **Pi-hole**.  
- Run DNS services **alongside existing automation scripts and cron jobs**.  
- Demonstrate proper **static IP configuration** and **DNS forwarding**.  
- Apply **security best practices** (firewall, SSH hardening, limited query access).  
- Verify name resolution from multiple client systems.  
- Document the full process for professional demonstration.

---

## 🧰 Tools & Technologies
- **Hardware:** Raspberry Pi 5 (4 GB RAM) + external SSD  
- **OS:** Raspberry Pi OS Bookworm (64-bit Lite)  
- **DNS Software:** BIND9 / Pi-hole  
- **Shell & Automation:** Bash + cron  
- **Networking Tools:** `ping`, `dig`, `nslookup`, `ss`, `ufw`  
- **Version Control:** Git + GitHub for documentation  

---

## ⚙️ Setup Steps
1. **Update Packages**
   ```bash
   sudo apt update && sudo apt upgrade -y
