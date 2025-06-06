#  File Integrity Monitor (FIM) – Python Project

This is a  **File Integrity Monitor** written in Python. It monitors one or more files for unauthorized changes by calculating file hashes and logging any detected modifications.

---

##  What is a File Integrity Monitor (FIM)?

A **File Integrity Monitor (FIM)** is a tool used in cybersecurity to detect if files have been altered, intentionally or unintentionally. It plays a critical role in:

-  Detecting unauthorized access or tampering
- Preventing data breaches and insider threats
-  Ensuring compliance with standards like **PCI-DSS**, **HIPAA**, and **SOX**

---

## ⚙ How It Works

1. The script calculates a **SHA-256 hash** (digital fingerprint) of each file listed.
2. It checks the files repeatedly at fixed intervals.
3. If the hash changes, the script logs the change along with a timestamp.
4. Logs are stored in the `/log` directory for further analysis.

---

##  Getting Started

### 1. Prerequisites

Ensure you have **Python 3.x** installed. To check: 

```bash
python --version

How to Run 

1. Run: `python fim.py`
2. Modify the file: `watched_file.txt`
3. Check the `logs` folder for updates

## Why It Matters

FIM tools are used in real-world cybersecurity to:
- Detect insider threats
- Track unauthorized access
- Meet compliance requirements (PCI-DSS, HIPAA, etc.)
