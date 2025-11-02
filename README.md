# Raspberry Pi 5 DNS Server Lab 🧠  
*Part of the MTPortfolio — Hands-On IT Labs, Networking, Scripting, Cybersecurity, and Beyond*

## 🧩 Overview
This lab demonstrates how I configured a **Raspberry Pi 5** as a functional **DNS server** within my home-lab subnet.  
It showcases core **System Administration** and **Networking** skills, including static IP configuration, DNS service management, and hands-on command-line walkthroughs in the Pi OS terminal. 

The goal: show how a small, low-cost device can provide critical infrastructure services reliably and securely.

---

## 🎯 Objectives
- Convert a Raspberry Pi 5 into a DNS server using either **DNSMasq** and **BIND9**.  
- Step-by-step walkthroughs on setting up both DNS software packages on Raspberry Pi OS.  
- Demonstrate proper **static IP configuration** and **DNS forwarding**.  
- Working with tools such as apt package manager, systemctl, nano, nmcli, and more
- Verification of domain name resolution


---

🖥️ **Live Project Webpage:**  
👉 [Raspberry Pi 5 DNS Server Lab](https://mark-thompson01.github.io/MTPortfolio/Skills/Raspberry%20Pi%205%20DNS%20Server%20Lab/)

---

📂 **Hosted on GitHub Pages:**  
All images, HTML, and styling are embedded within the GitHub Pages site itself.



---

## 🧰 Tools & Technologies
- **Hardware:** Raspberry Pi 5 (8 GB RAM)
- **OS:** Raspberry Pi OS Bookworm (64-bit Lite)  
- **DNS Software:** DNSMasq / BIND9
- **Shell & Administration:** Bash + apt + nano + NetworkManager + systemctl + service
- **Networking Tools:** `ping`, `dig`, `nslookup`, `nmcli`, `ip a` `hostname -I` 
- **Version Control:** Git + GitHub for documentation  

---

🧠 What I Learned
- How to setup and configure a DNS server on a Raspberry Pi 5 with DNSMasq and BIND9
- How DNSMasq is lightweight and perfect for SOHO networks
- How BIND9 is geared more for larger enterprise networks, with more granular administration
- How to manually setup a forward and reverse lookup zone
- How to properly edit .conf files with intended specifications
- How to utilize new tools such as nmcli to discover what connection profile maps to what interface
- Using nmcli to discover, verify, and make modifications to existing connection profiles

## 📁 More from Me

Visit my full GitHub Pages portfolio to explore additional projects:

🔗 [MTPortfolio – Full Project Index](https://mark-thompson01.github.io/MTPortfolio/)


##

📄 **License**  
This content is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
