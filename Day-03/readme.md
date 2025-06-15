# 📘 Cybersecurity Notes – Day 3

Welcome to **Day 3** of our Cybersecurity course!  
In this session, we focused on using **GitHub** for version control and collaboration, along with learning some **essential Linux commands** that every cybersecurity practitioner should know.

---

## 🔧 GitHub Basics

GitHub is a web-based platform used to host and manage code using **Git**, a distributed version control system.

### 🗂️ Key Concepts:

- **Repository (repo)**: A folder/project hosted on GitHub.
- **Commit**: A snapshot of changes made to a file.
- **Branch**: A parallel version of the repository.
- **Pull Request (PR)**: A request to merge changes from one branch to another.
- **Clone**: Make a local copy of a remote repo.

### ⚙️ Common Git Commands:

```bash
git init                     # Initialize a local repo
git clone <url>              # Clone a remote repo
git status                   # Show current changes
git add <file>               # Stage a file for commit
git commit -m "message"      # Commit changes with message
git push                     # Upload local changes to GitHub
git pull                     # Download updates from remote repo
```

### 📂 File & Directory Navigation

```bash
pwd              # Print working directory
ls               # List directory contents
cd <dir>         # Change directory
mkdir <dir>      # Create new directory
rm <file>        # Remove file
rm -r <dir>      # Remove directory recursively
touch <file>     # Create new empty file
cp <src> <dst>   # Copy files or directories
mv <src> <dst>   # Move or rename files/directories
```

### 🧠 System Info & Monitoring

```bash
whoami           # Show current user
uname -a         # System kernel and architecture info
top              # Real-time process usage monitor
df -h            # Disk space in human-readable format
free -h          # Memory usage
```

### 🌐 Networking Basics

```bash
ifconfig         # Show network interfaces (deprecated, but still useful)
ip a             # Modern replacement for ifconfig
ping <host>      # Test network connection
netstat -tuln    # List open ports and listening services
```

### 📦 Package Management (Debian-based Systems)

```bash
sudo apt update                # Update list of available packages
sudo apt upgrade               # Upgrade installed packages
sudo apt install <package>     # Install new package
```
