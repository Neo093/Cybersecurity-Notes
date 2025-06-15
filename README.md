# 🛡️ Cybersecurity Notes

Welcome to the **Cybersecurity Notes** repository!  
This repo contains curated content, commands, and documentation to help students and enthusiasts explore the world of cybersecurity.

---

## 📘 Overview of Cybersecurity

Cybersecurity refers to the practice of protecting systems, networks, and programs from digital attacks. These cyberattacks are usually aimed at accessing, changing, or destroying sensitive information, extorting money, or interrupting normal business processes.

### 🔐 Types of Cybersecurity

1. **Network Security**
   - Protects network infrastructure from unauthorized access or misuse.
   - Includes firewalls, VPNs, and IDS/IPS.

2. **Information Security**
   - Safeguards data from unauthorized access or alteration.

3. **Application Security**
   - Ensures software is free from threats and vulnerabilities.

4. **Operational Security (OPSEC)**
   - Covers decisions and procedures around data handling.

5. **Cloud Security**
   - Focuses on protecting cloud-based systems and data.

6. **Endpoint Security**
   - Protects end-user devices like PCs and smartphones.

7. **Identity and Access Management (IAM)**
   - Manages users’ access to systems and resources securely.

8. **Disaster Recovery & Business Continuity**
   - Plans to restore systems after a breach or failure.

---

## 🖥️ How to Install VMware Workstation

VMware Workstation allows you to run multiple operating systems as virtual machines on a single host machine.

### 🔧 Installation Steps:

1. **Download VMware Workstation:**
   - Go to: https://www.vmware.com/products/workstation-pro.html
   - Choose the correct version for your operating system.

2. **Install:**
   - Run the installer and follow on-screen instructions.
   - Restart your system if prompted.

3. **(Optional) Install License Key:**
   - Free version available with limited features.
   - Paid version offers advanced tools.

4. **Create a Virtual Machine:**
   - Open VMware → `Create New Virtual Machine` → Follow wizard

---

## 🐱‍💻 How to Install Kali Linux on VMware

Kali Linux is a Debian-based Linux distro used for penetration testing and security auditing.

### 📥 Download Kali ISO:

- Go to: https://www.kali.org/get-kali/
- Choose "Installer" or "Live" ISO version

### ⚙️ Steps to Install on VMware:

1. **Launch VMware Workstation.**

2. **Create a New Virtual Machine:**
   - Choose “Typical (recommended)”
   - Select “Installer disc image file (iso)” and choose Kali ISO

3. **Name and Specify Disk Capacity:**
   - Allocate at least **20 GB** storage
   - Choose “Split virtual disk into multiple files”

4. **Customize Hardware (Optional):**
   - Set **Memory (RAM)** to 2GB or more
   - Allocate 2+ processors if available
   - Enable Virtualization in BIOS if needed

5. **Start Virtual Machine & Install Kali:**
   - Follow Kali's installation wizard (Graphical Install recommended)
   - Set username, password, timezone, disk partition

6. **Post-Install Steps:**
   - Update Kali:  
     ```bash
     sudo apt update && sudo apt upgrade
     ```
   - Install VMware Tools (for better integration and screen scaling)

---

## 📂 Repository Structure

