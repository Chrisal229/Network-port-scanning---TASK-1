# 🔐 Network Port Scanning Task

## 📌 Objective
To perform a TCP SYN scan on my local network to identify active hosts and open ports.

---

## 🛠 Tools Used
- Nmap
- Wireshark (optional)
- Kali Linux (VirtualBox)

---

## 🔎 Steps Performed

1. Identified local IP range using:
   ip a

2. Performed TCP SYN Scan:
   sudo nmap -sS 192.168.1.0/24

3. Saved output:
   sudo nmap -sS 192.168.1.0/24 -oN scan_results.txt
   sudo nmap -sS 192.168.1.0/24 -oX scan_results.xml

4. Analyzed open ports and services.

---

## 🌐 Key Findings

- Active hosts discovered: X
- Open ports identified: 22 (SSH), 80 (HTTP), 443 (HTTPS)
- Some devices had multiple open services.

---

## ⚠ Potential Security Risks

- Open SSH port may allow brute-force attacks.
- HTTP services may expose web vulnerabilities.
- Unnecessary open ports increase attack surface.

---

## 🔥 Conclusion

This task helped me understand:
- Network reconnaissance
- TCP SYN scanning
- Open port analysis
- Basic network security exposure

