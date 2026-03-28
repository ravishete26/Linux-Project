# 🚀 Linux Server Administration & Automation

## 📌 Project Overview

This project demonstrates Linux server management and automation using shell scripting and system tools.

## 🛠️ Technologies Used

* Linux (Ubuntu/CentOS)
* Shell Scripting (Bash)
* Cron Jobs
* tar, gzip
* fdisk, mkfs

## ⚙️ Features

✔ User & Group Management
✔ File Permission Management
✔ Package Installation
✔ Disk Partitioning
✔ Backup Automation
✔ Job Scheduling (Cron)
✔ Log Management
✔ System Monitoring

## 📂 Project Structure

* scripts/ → Automation scripts
* docs/ → Command explanations
* Project.pdf → Full documentation

## 🚀 How to Run Scripts

### Give permission:

chmod +x scripts/*.sh

### Run:

./scripts/user_setup.sh
./scripts/backup.sh
./scripts/monitor.sh

## ⏰ Cron Setup Example

crontab -e

Add:
0 2 * * * /path/to/scripts/backup.sh

## 📌 Outcome

* Automated Linux admin tasks
* Reduced manual effort
* Improved system monitoring

## 👨‍💻 Author

Ravi Babasaheb Shete
