# File Integrity Monitor (FIM)

A simple Python-based File Integrity Monitor that watches for file changes using hash comparisons.

## What is a File Integrity Monitor?

A FIM detects unauthorized changes to files by checking their hash values over time.

## How It Works

1. Monitors the hash of `watched_file.txt`
2. If the file changes, logs the event with a timestamp
3. Saves logs in the `logs/file_changes.log`

## How to Run

1. Run: `python fim.py`
2. Modify the file: `watched_file.txt`
3. Check the `logs` folder for updates

## Why It Matters

FIM tools are used in real-world cybersecurity to:
- Detect insider threats
- Track unauthorized access
- Meet compliance requirements (PCI-DSS, HIPAA, etc.)
