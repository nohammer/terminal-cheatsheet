# terminal-cheatsheet
A simple and practical terminal cheatsheet with the most useful commands for beginners and developers.
# 🧠 Terminal Cheatsheet for Developers

A compact, no-nonsense guide with essential terminal commands for working efficiently as a developer on macOS/Linux.

---

## 🔁 Navigation & Filesystem

```bash
pwd             # Show current directory
ls              # List files in directory
ls -la          # List all files, incl. hidden, long format
cd my_folder    # Go into a folder
cd ..           # Go up one level
mkdir test      # Create folder named 'test'
touch file.txt  # Create new file
rm file.txt     # Delete file
rm -rf folder/  # Force delete folder recursively
```

## 📝 File Operations

```bash
cat file.txt             # Show file contents
nano file.txt            # Edit file with nano
cp file1.txt file2.txt   # Copy file
mv old.txt new.txt       # Rename or move file
```

## 🔎 Search & Filter

```bash
grep 'hello' file.txt         # Find 'hello' in file
ps aux | grep python          # Find Python processes
find . -name "*.py"           # Find all Python files
```

## 📦 Package Management (Debian-based)

```bash
sudo apt update           # Update package index
sudo apt upgrade          # Upgrade packages
sudo apt install git      # Install git
```

## 🔧 Process & System

```bash
top                      # Live system processes
htop                     # Better top (if installed)
kill 1234                # Kill process with PID 1234
clear                    # Clear terminal screen
```

## 🛰️ Networking

```bash
curl http://example.com         # Make HTTP request
ping google.com                 # Ping server
ifconfig / ip a                # Show IP info (macOS/Linux)
```

## 🗃️ Git Basics

```bash
git clone <url>               # Clone repo
git status                    # Show status
git add .                     # Stage all changes
git commit -m "Message"      # Commit with message
git push                      # Push to remote
git pull                      # Pull latest changes
```

---

> 👨‍💻 Made for beginners, dreamers & future power users. Keep hacking!
