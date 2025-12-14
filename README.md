# Network-Penetration-Tester-Roadmap-Full-Progress-Checklist
Roadmap
# 🛡️ Network Penetration Tester — Progress Checklist

A complete, structured learning roadmap to track my journey from networking fundamentals to full network penetration testing.

---

## ✅ STAGE 1 — CORE NETWORKING (2–4 weeks)

### 🔹 OSI & TCP/IP Models
- [x] Understand all 7 OSI layers  
- [x] Map OSI → TCP/IP model  
- [x] Know PDU: Frame, Packet, Segment  

### 🔹 TCP & UDP (Deep Understanding)
- [x] TCP 3-way handshake (SYN, SYN/ACK, ACK)
- [x] FIN, RST, retransmission
- [x] Sequence & ACK numbers  
- [x] Sliding window & flow control  
- [x] TCP vs UDP behavior  

### 🔹 IP Addressing (IPv4 & IPv6 basics)
- [x] Private vs Public IP  
- [x] ARP: IP → MAC mapping  
- [x] DHCP: IP assignment  
- [x] DNS: name resolution  
- [x] NAT / PAT  

### 🔹 Subnetting (Practical Only)
- [x] /24, /30, /31, /32  
- [x] Find network & broadcast address  
- [x] Determine usable host range  
- [x] Understand why networks can't communicate  

### 🔹 Switching & Routing
- [x] VLAN concepts  
- [x] Access vs Trunk ports  
- [x] 802.1Q tagging  
- [x] STP basics  
- [x] MAC address table  
- [x] Static routes  
- [x] Basic OSPF  

---

## ✅ STAGE 2 — NETWORK TOOLS MASTERY (1–2 weeks)

### 🔹 Nmap (Beginner → Advanced)
- [x] Host discovery (-sn)
- [x] Port scans (SYN, Connect, UDP)
- [x] Service/version detection (-sV)
- [x] OS fingerprinting (-O)
- [x] Firewall evasion (-Pn, --data-length)
- [x] Timing options (T1–T5)
- [x] NSE scripts (vuln, auth, exploit)

### 🔹 Wireshark
- [x] Capture filters  
- [x] Display filters  
- [x] Follow TCP streams  
- [x] Identify scans/attacks  
- [x] Detect ARP poisoning  
- [x] Analyze traffic  

### 🔹 Packet Crafting Tools (Optional but powerful)
- [ ] hping3  
- [ ] Scapy (Python-based)  

---

## ✅ STAGE 3 — NETWORK ATTACK FOUNDATIONS (3–6 weeks)

### 🔹 Layer 2 (Local Network) Attacks
- [ ] ARP poisoning  
- [ ] MITM attacks  
- [ ] DNS spoofing  
- [ ] DHCP starvation  
- [ ] Evil Twin WiFi  
- [ ] MAC spoofing  
- [ ] Session hijacking  
- [ ] VLAN hopping  
- [ ] TCP sequence prediction  

### 🔹 Tools To Practice
- [ ] Bettercap  
- [ ] Ettercap  
- [ ] arpspoof  
- [ ] Responder  
- [ ] mitm6  
- [ ] Wireshark analysis  

---

## ✅ STAGE 4 — SERVICE-LEVEL EXPLOITATION (4–8 weeks)

### 🔹 SMB Attacks
- [ ] Enumerate shares  
- [ ] SMB version detection  
- [ ] NTLM relay  
- [ ] Password brute-force  
- [ ] EternalBlue on vulnerable systems  

### 🔹 SSH / FTP / Telnet
- [ ] Banner grabbing  
- [ ] Weak cipher detection  
- [ ] Brute-force  
- [ ] Misconfiguration exploitation  

### 🔹 Web Servers (Internal Network)
- [ ] Directory fuzzing  
- [ ] Default credentials  
- [ ] Outdated software detection  
- [ ] Reverse shells  

### 🔹 Other Vulnerable Services
- [ ] SNMP enumeration  
- [ ] Redis misconfigurations  
- [ ] RDP exploitation  
- [ ] Proxy misconfigurations (Squid)  

### 🔹 Tools To Master
- [ ] Metasploit  
- [ ] Hydra  
- [ ] Nmap NSE scripts  
- [ ] enum4linux  
- [ ] crackmapexec  
- [ ] snmpwalk  

---

## ✅ STAGE 5 — PIVOTING & LATERAL MOVEMENT (Advanced)

### 🔹 Core Pivoting Skills
- [ ] Compromise a machine  
- [ ] Add routes in Metasploit  
- [ ] Use proxychains  
- [ ] Pivot with SSH  
- [ ] Build tunnels (chisel, socat)  
- [ ] Enumerate internal networks  
- [ ] Move between VLANs  
- [ ] Escalate privileges on multiple hosts  

### 🔹 Tools
- [ ] Proxychains  
- [ ] Chisel  
- [ ] SOCAT  
- [ ] SSH tunneling  
- [ ] Metasploit route add  

---

## ✅ STAGE 6 — PYTHON FOR HACKING (3–6 weeks)

### 🔹 Python Basics for Pentesting
- [ ] TCP/UDP socket programming  
- [ ] File handling  
- [ ] Loops, functions  
- [ ] Error handling  

### 🔹 Build Hacking Tools
- [ ] Port scanner  
- [ ] Directory brute-forcer  
- [ ] Password brute-force script  
- [ ] Packet sniffer (Scapy)  
- [ ] Reverse shell  
- [ ] MITM scripts  
- [ ] Auto-recon tool  

### 🔹 Python Modules
- [ ] scapy  
- [ ] socket  
- [ ] requests  
- [ ] paramiko  
- [ ] ftplib  
- [ ] subprocess  

---

## ✅ STAGE 7 — FULL HACKING LAB SETUP

### 🔹 Virtual Machines To Install
- [ ] Kali Linux  
- [ ] Windows 10  
- [ ] Windows Server  
- [ ] Metasploitable 2  
- [ ] Metasploitable 3  
- [ ] DVWA  
- [ ] OWASP Juice Shop  
- [ ] Parrot OS  

### 🔹 External Practice Platforms
- [ ] VulnHub  
- [ ] TryHackMe  
- [ ] HackTheBox  

---

## 🏁 FINAL GOAL  
✔ Perform full penetration tests  
✔ Build full attack chains  
✔ Scan, exploit, pivot, escalate  
✔ Write custom scripts  
✔ Document real-world pentests  

This checklist tracks my entire journey to becoming a **Network Penetration Tester**.
