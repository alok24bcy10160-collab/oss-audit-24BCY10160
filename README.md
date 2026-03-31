# Open Source Audit Project

## Student Details

* **Name:** Alok Ebel Paul
* **Registration Number:** 24BCY10160
* **Course:** Open Source Software (OSSC NGMC)

---

## Chosen Software

**Software Selected:** [e.g., Python / Git / Apache HTTP Server]

**Category:** [Programming Language / Version Control / Web Server]
**License:** [e.g., GPL v2 / MIT / Apache 2.0 / PSF License]

---

## Project Overview

This project presents a structured audit of a real-world open-source software system. It explores:

* The origin and philosophy behind the software
* Its licensing model and ethical implications
* Its footprint within a Linux environment
* Its role in the broader open-source ecosystem

In addition, five shell scripts have been developed to demonstrate practical Linux skills such as automation, system inspection, and log analysis.

---

## Repository Contents

| File Name    | Description                     |
| ------------ | ------------------------------- |
| `script1.sh` | System Identity Report          |
| `script2.sh` | FOSS Package Inspector          |
| `script3.sh` | Disk and Permission Auditor     |
| `script4.sh` | Log File Analyzer               |
| `script5.sh` | Open Source Manifesto Generator |
| `README.md`  | Project documentation           |

---

## System Requirements

* Linux OS (Ubuntu / Debian / WSL recommended)
* Bash shell
* Basic Linux utilities: `grep`, `awk`, `du`, `df`, `uptime`, `whoami`
* Internet connection (for package installation)

---

## Installation and Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/[your-username]/oss-audit-[rollnumber].git
cd oss-audit-[rollnumber]
```

### Step 2: Grant Execute Permissions

```bash
chmod +x *.sh
```

---

## Script Execution Guide

### Script 1: System Identity Report

Displays Linux system details such as distribution, kernel version, user, uptime, and license.

```bash
./script1.sh
```

---

### Script 2: FOSS Package Inspector

Checks whether a package is installed and displays version, license, and summary.

```bash
./script2.sh
```

---

### Script 3: Disk and Permission Auditor

Reports directory sizes, ownership, and permissions for key system folders.

```bash
./script3.sh
```

---

### Script 4: Log File Analyzer

Analyzes a log file and counts occurrences of a keyword (default: "error").

```bash
./script4.sh /var/log/syslog error
```

---

### Script 5: Open Source Manifesto Generator

Prompts the user for input and generates a personalized open-source philosophy statement.

```bash
./script5.sh
```

---

## Concepts Demonstrated

* Shell scripting fundamentals
* Variables and command substitution (`$()`)
* Conditional logic (`if-else`)
* Loops (`for`, `while`)
* Case statements
* File handling and redirection (`>`, `>>`)
* Text processing using `grep`, `awk`, and `cut`
* User input handling using `read`

---

## Learning Outcomes

* Understanding open-source philosophy and licensing
* Hands-on experience with Linux command-line tools
* Writing and executing shell scripts
* Automating system-level tasks
* Exploring real-world open-source ecosystems

---

## Notes

* All scripts are tested on a Linux environment
* Ensure execution permissions are granted before running scripts
* Some commands may require `sudo` privileges depending on system configuration

---

## Acknowledgment

This project was completed as part of the Open Source Software course and reflects independent learning and hands-on practice with Linux and open-source tools.

---

## Submission Details

* GitHub Repository: [Paste your repository link here]
* Project Report: Submitted separately via VITyarthi portal

---
