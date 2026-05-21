# Linux Basics

## Objective
Learning Linux commands and terminal navigation for AWS and DevOps tasks.

## Topics Covered
* Linux Fundamentals & OS Basics
* User Management & Security Permissions
* File Handling & Text Manipulation 
* System Admin, Networking & Monitoring
* Shell Scripting Basics
* Git Version Control

---

## Commands Learned

### 1. Terminal & User Management
* `man` - Opens manual pages for commands
* `clear` - Clears the terminal screen
* `echo` - Prints text to the terminal
* `whoami` - Shows current logged-in user
* `su` / `sudo bash` - Switch to root user
* `sudo` - Run commands with root privileges
* `useradd` / `userdel` - Add or remove system users
* `passwd` - Change user password
* `groupadd` / `groupdel` - Manage user groups

### 2. Navigation & File Operations
* `pwd` - Print current working directory
* `cd` - Change directory
* `ls` - List files (`ls -l` for permissions)
* `touch` - Create an empty file
* `vi` - Classic text editor
* `cat` - View file content (`cat -n` for line numbers)
* `cp` - Copy files/directories
* `mv` - Move or rename files
* `rm` - Delete files (`rm -r` for folders)
* `mkdir` / `rmdir` - Create or remove empty directories

### 3. Text Filtering & Scripting Tools
* `grep` - Search text for patterns
* `sort` - Sort lines alphabetically or numerically
* `cut` - Extract specific columns from a file
* `sed` - Stream editor (used for find-and-replace text)
* `uniq` - Filter out duplicate lines
* `awk` - Advanced text/data processing language
* `tr` - Translate or convert characters (e.g., lowercase to uppercase)

### 4. System Admin & Networking
* `lsof` - List open files and processes
* `id` - Show user and group IDs
* `tar` - Archive/extract `.tar` files
* `watch` - Run a command repeatedly in real-time
* `history` - View previous commands used
* `free` - Check system memory usage (`free -m`)
* `df` / `du` - Check disk space and folder sizes
* `ssh` / `ssh-keygen` - Remote login and SSH key generation
* `ifconfig` / `ip address` - Check network interfaces and IPs
* `netstat` - Monitor active network connections
* `nslookup` - Check DNS details for a domain
* `curl` - Transfer data/download from a URL
* `env` - View environment variables
* `iptables` - Manage firewall rules
* `apt-get` - Package manager for installing software (Ubuntu)

### 5. Git Basics
* `git config` - Set user name and email
* `git init` - Create a new local repo
* `git clone` - Copy a remote repo to local machine
* `git add` - Stage file changes (`git add .`)
* `git commit -m` - Save staged changes with a note
* `git push` / `git pull` - Sync changes with GitHub/Remote
* `git branch` - List or create branches
* `git checkout` - Switch branches
* `git merge` / `git rebase` - Combine branch workflows

---

## Notes
* This repository is part of my AWS DevOps internship preparation journey.
* Shell scripts require a `.sh` extension and should start with a shebang line (like `#!/bin/bash`) to run properly.