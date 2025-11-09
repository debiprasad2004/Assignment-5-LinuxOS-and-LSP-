# Assignment-5-LinuxOS-and-LSP-
# Assignment5_SystemMaintenance_UsingBashScript
# 🧰 System Maintenance Suite

## Overview
The **System Maintenance Suite** is a collection of **Bash scripts** that automate common Linux maintenance tasks such as backups, system updates, and log monitoring.  
Each script can run independently or through an interactive **menu-driven interface** for convenience.

This project is designed for Linux or WSL (Windows Subsystem for Linux) environments and demonstrates automation, error handling, and system scripting.

---

## 📁 Files Included
| File | Description |
|------|--------------|
| `backup.sh` | Automates backups of the system or home directory. |
| `update_cleanup.sh` | Updates system packages and removes unused files. |
| `log_monitor.sh` | Scans `/var/log/syslog` for warnings or errors. |
| `maintenance_suite.sh` | Main menu script that combines all the features. |
| `maintenance.log` | Log file generated automatically during execution. |

---

## ⚙️ How to Run

1. **Open Ubuntu (Linux or WSL).**
2. Navigate to the project directory:
   ``bash
   cd system_maintenance

3. Make the scripts executable:
   ``bash
   chmod +x *.sh
   
4. Run the main script:
   ``bash
   ./maintenance_suite.sh
   
6. Follow the on-screen menu options:

   * 1️⃣ Run Backup
   * 2️⃣ Update & Clean System
   * 3️⃣ Monitor Logs
   * 4️⃣ View Log File
   * 5️⃣ Exit

---

## ✨ Features

* 📦 **Automated System Backups** — Compress and store important files safely.
* 🔄 **System Update & Cleanup** — Keep packages up to date and remove old dependencies.
* 🪵 **Log Monitoring & Alerts** — Detect errors or warnings in system logs.
* 🧭 **Interactive Menu** — Simple user interface for easy navigation.
* 🧾 **Logging & Error Handling** — All activities and errors are logged in `maintenance.log`.

---

## 🧠 Example Output

===============================
 System Maintenance Suite
===============================
1️⃣  Run Backup
2️⃣  Update & Clean System
3️⃣  Monitor Logs
4️⃣  View Log File
5️⃣  Exit
--------------------------------
👉 Enter your choice [1-5]:
``

## 🧑‍💻 Author

**Debi Prasad Dash**
Bash scripting | Linux automation | Capstone Project (Assignment 5)
