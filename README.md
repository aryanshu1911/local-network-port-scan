# 🔍 Local Network Port Scan with Nmap

This project documents the use of **Nmap** to scan a local machine on a virtualized network. The scan identifies open ports, services, and potential security risks. It’s part of my learning journey in **Cybersecurity** and **Network Reconnaissance**.

---

## 📌 Objective

- Perform an aggressive Nmap scan (`-A`) on a local network machine.
- Identify open ports and active services.
- Analyze potential vulnerabilities or misconfigurations.
- Document findings and mitigation suggestions.

---

## 🛠️ Tools Used

- **Nmap 7.94SVN**
- Virtual Machine (target) running **Windows OS** inside **VirtualBox**

---

## 🧪 Scan Details

**Scan Command Used:**
```bash
nmap -A 192.168.1.X -oN scan_results.txt

Note: The last octet of the target IP address has been masked with 'X' for privacy and security reasons.
