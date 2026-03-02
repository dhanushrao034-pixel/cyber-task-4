# cyber-task-4
This project demonstrates basic firewall configuration using Windows Firewall or UFW on Linux. It includes steps to view existing firewall rules, block Telnet port (23), allow SSH port (22), test connectivity, and restore rules. The project highlights network traffic filtering and basic firewall management concepts in cybersecurity.
# 🔥 Firewall Configuration and Management

## 📌 Task 4 – Cyber Security Internship

## 🎯 Objective
The objective of this task is to configure and test basic firewall rules to allow or block network traffic using Windows Firewall or UFW on Linux.

## 🛠 Tools Used
- Windows Defender Firewall
OR
- UFW (Uncomplicated Firewall) – Linux

## 📂 Task Steps

### 1. Check Existing Firewall Rules
List current firewall rules to understand active configurations.

 (Linux):
sudo ufw status

### 2. Block Telnet Port (23)
Telnet is insecure because it sends data without encryption.

Command:
sudo ufw deny 23

### 3. Allow SSH Port (22)
SSH is used for secure remote connections.

Command:
sudo ufw allow 22

### 4. Test Firewall Rules
Attempt to connect to blocked port and verify that access is denied.

Example:
telnet localhost 23

### 5. Remove Test Rule
Restore firewall to original state.

Command:
sudo ufw delete deny 23

## 📊 Outcome
- Learned how to configure firewall rules
- Understood inbound and outbound traffic filtering
- Practiced blocking and allowing specific ports

## 🔐 Key Concepts
- Firewall configuration
- Network traffic filtering
- Ports and protocols
- UFW management
- Windows Firewall rules

## 📸 Screenshots
Screenshots of firewall rules and configurations are included in the repository.

## 📄 Report
Detailed explanation of the task is available in the report.pdf file.

## 👨‍💻 Author
Dhanush Rao  
Cyber Security Internship
