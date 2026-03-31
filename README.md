# 📦 Open Source Software Audit Project

## 👤 Student Details

* **Name:** RASHI GAUR
* **Registration Number:** 24BEC10031
* **Course:** Open Source Software

---

## 💻 Chosen Software

### **Git (Distributed Version Control System)**

Git is an open-source distributed version control system used to track changes in source code during software development. It enables efficient collaboration, maintains version history, and supports large-scale project management.

---

## 📂 Project Structure

This repository consists of multiple shell scripts designed to demonstrate core Linux and open-source concepts:

---

### 🔹 Script 1 — System Identity Report

* Displays system-level information:

  * Linux distribution
  * Kernel version
  * Logged-in user
  * System uptime
  * Current date and time

* **Concepts Used:**
  `variables`, `command substitution`, `echo`

---

### 🔹 Script 2 — FOSS Package Inspector

* Verifies whether a package (Git) is installed

* Displays version and package-related details

* Uses a `case` statement to describe the software

* **Concepts Used:**
  `if-else`, `case`, `dpkg`

---

### 🔹 Script 3 — Disk and Permission Auditor

* Audits important system directories

* Displays:

  * Directory size
  * Permissions
  * Ownership details

* **Concepts Used:**
  `for loop`, `awk`, `du`, `ls`

---

### 🔹 Script 4 — Log File Analyzer

* Reads a log file and searches for a keyword

* Displays:

  * Total occurrences
  * Last matching log entries

* **Concepts Used:**
  `while loop`, `grep`, `counters`

---

### 🔹 Script 5 — Open Source Manifesto Generator

* Accepts interactive user input

* Generates a personalized open-source manifesto

* Saves output to a `.txt` file

* **Concepts Used:**
  `read`, `file handling`, `string formatting`

---

## ⚙️ Requirements

* Linux Environment (Ubuntu / WSL / Docker)
* Bash Shell
* Basic Linux Utilities:

  * `grep`
  * `awk`
  * `du`
  * `ls`

---

## ▶️ How to Run the Scripts

### Step 1: Make scripts executable

```bash
chmod +x *.sh
```

### Step 2: Execute scripts

```bash
./script1.sh
./script2.sh
./script3.sh
```

### Run Script 4 (with arguments)

```bash
./script4.sh /var/log/syslog error
```

### Run Script 5

```bash
./script5.sh
```

---

## 📸 Additional Notes

* All scripts were tested in a Linux environment
* Each script is well-commented for better understanding

---

## 📘 Learning Outcomes

* Strong understanding of Linux commands and shell scripting
* Practical exposure to open-source tools and workflows
* Hands-on experience with automation and system-level operations
* Better understanding of open-source philosophy and collaboration

---

## 🔗 GitHub Repository

👉 https://github.com/rashi-gaur/linux_shell_scripting_oss_rashi

---

## 📄 License

This project is developed for academic purposes as part of the Open Source Software course.
