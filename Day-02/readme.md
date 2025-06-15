# 🧠 Cybersecurity Notes – Day 2

Welcome to **Day 2** of our Cybersecurity learning journey!  
This session covers critical foundational concepts including common threats, types of viruses, phishing techniques, and essential Kali Linux tools.

---

## 🔬 Topics Covered

### 1. 🦠 Types of Viruses

Viruses are malicious software programs that can replicate and spread to other systems. Understanding them helps in recognizing potential attack vectors.

- **File Infector Virus** – Attaches to executable files; activates when the file is run.
- **Macro Virus** – Targets applications like MS Word/Excel using macros.
- **Boot Sector Virus** – Infects system boot loaders or MBR (Master Boot Record).
- **Polymorphic Virus** – Constantly changes its code to avoid detection.
- **Metamorphic Virus** – Rewrites its own code completely every time it runs.
- **Resident Virus** – Resides in RAM and can interfere with system operations.

---

### 2. ⚠️ Cybersecurity Threats

Cyber threats are malicious acts seeking to damage, steal, or disrupt digital systems.

- **Malware** – Software designed to harm systems (viruses, worms, trojans).
- **Ransomware** – Locks data and demands ransom for decryption.
- **Man-in-the-Middle (MITM)** – Attacker intercepts communications between two parties.
- **DDoS (Distributed Denial of Service)** – Overloads a server with requests to take it offline.
- **Zero-Day Exploit** – Attack that occurs before a vulnerability is patched.

---

### 3. 🎣 Phishing Attacks

Phishing is a type of social engineering where attackers deceive users into revealing sensitive information.

- **Email Phishing** – Fake emails pretending to be from trusted sources.
- **Spear Phishing** – Targeted phishing with personalized info to appear legitimate.
- **Smishing** – Phishing via SMS/text messages.
- **Vishing** – Voice phishing using phone calls.
- **Clone Phishing** – Duplicate of a legitimate message with malicious links or attachments.

🛡️ *Tip: Always verify links and sender authenticity before clicking or responding.*

---

### 4. 🧰 Basic Kali Linux Tools

Kali Linux is a powerful penetration testing OS packed with cybersecurity tools. Below are some basic tools introduced:

| Tool | Use Case |
|------|----------|
| **Nmap** | Network scanning and port detection |
| **Wireshark** | Network packet analyzer |
| **Hydra** | Password cracking via brute-force |
| **Burp Suite** | Web vulnerability scanner |
| **Nikto** | Web server scanning |
| **Whois** | Domain and IP info lookup |
| **Netcat (nc)** | Port scanning and banner grabbing |
| **Gobuster** | Directory brute-forcing |

🧪 Most tools can be run from the terminal, e.g.:

```bash
nmap -sV 192.168.1.1
