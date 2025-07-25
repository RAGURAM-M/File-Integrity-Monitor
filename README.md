# 🛡️ File Integrity Monitor

A simple Python tool to monitor file changes by calculating and comparing hash values using SHA-256. This script helps detect unauthorized modifications, deletions, or additions in files within a directory, ensuring file integrity.

## 🔧 Features

- Computes SHA-256 hash of each file
- Detects:
  - ✅ Modified files
  - ❌ Deleted files
  - 🆕 New files
- Stores and compares hashes using a JSON file
- Lightweight and easy to use

## 🐍 Requirements

- Python 3.x
- No third-party packages required (uses built-in `hashlib`, `json`, `os`)

## 📁 Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/file-integrity-monitor.git
   cd file-integrity-monitor

### Enter the path of the directory you want to monitor when prompted.

### The script will:

  - Compare current file hashes with previous ones
  - Display a report of any changes
  - Save updated hashes to file_hashes.json

##  📷 Example Output

**Before Modifying**

![Image](https://github.com/user-attachments/assets/3523a6b2-4dfc-439e-b5b3-9d751a8b7f87)

**After Modifying**

![Image](https://github.com/user-attachments/assets/bc20e4c2-806e-427b-9372-dd628a664e34)

## 💡 Use Cases
Monitoring critical system or project files

Detecting tampering or accidental changes

Backup verification

---

