# 🧠 Networking Notes (TryHackMe)

This file contains everything I'm learning from networking rooms on TryHackMe — especially the fundamentals of how devices communicate over the internet and how hackers can understand and exploit those connections. Here's what I've learned so far:

---

## 🌐 What is Networking?

Networking is the communication between devices (computers, phones, servers) using protocols and shared rules to exchange data. It's how we access websites, send emails, and transfer files.

---

## 📦 Key Networking Concepts I Learned

### 1. *IP Addresses*
- Every device on a network has an *IP address* — like a home address.
- IPv4 example: 192.168.1.1
- Can be public (internet) or private (local network).

### 2. *Ports*
- A port is like a door in a house where data enters.
- Example:  
  - Port 80 = HTTP  
  - Port 443 = HTTPS  
  - Port 22 = SSH  
- I learned that attackers often scan ports to find vulnerabilities.

### 3. *Protocols*
- Rules that define how data is sent.
- Common protocols:
  - *TCP* (reliable, connection-based)
  - *UDP* (faster, but no guarantee)
  - *HTTP, **DNS, **FTP, **SMTP*, etc.

### 4. *Subnetting*
- Subnetting helps divide IP networks into smaller groups.
- Makes networks more efficient and secure.

### 5. *Ping & Traceroute*
- ping checks if a host is reachable.
- tracert (or traceroute) shows the path a packet takes.


## 🧠 Key Takeaways

- Every device has an IP and communicates via ports.
- Ports and services can be vulnerable and should be protected.
- Understanding traffic helps both in defense and attacks.
- Packet analysis is powerful — Wireshark shows real data moving.

---

📝 More notes coming soon as I progress through more TryHackMe rooms and hands-on labs!
