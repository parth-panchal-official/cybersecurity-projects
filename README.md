# 📂 Cybersecurity Projects – Parth Panchal

This repository contains a collection of cybersecurity tools and applications developed as part of my internship at **Elevate Labs**. These projects cover topics like password analysis, network packet sniffing, and secure file storage using advanced encryption techniques. Each project includes both CLI and GUI options along with detailed documentation.

---

## ✅ Projects Overview

1. 🔐 **Password Strength Analyzer & Wordlist Generator**
2. 🕵️‍♂️ **Real-Time Network Packet Sniffer with Alert System**
3. 🔐 **Secure File Storage System with AES-256 Encryption**

---

## 📖 Project Details

### 1. 🔐 Password Strength Analyzer & Wordlist Generator

A dual-purpose tool for analyzing password strength and generating targeted wordlists to simulate real-world attack scenarios.

**Key Features:**

* Password strength analysis using `zxcvbn`
* Crack time estimation & feedback
* Custom wordlist generation with inputs like name, birthdate, etc.
* GUI interface with Tkinter
* Auto-generated timestamped wordlists

**Technologies Used:** Python, Tkinter, zxcvbn

**Run Instructions:**

```bash
pip install -r requirements.txt
python main.py   # CLI
python app/gui_main.py   # GUI
```

---

### 2. 🕵️‍♂️ Real-Time Network Packet Sniffer with Alert System

A Python-based packet sniffing application with anomaly detection and credential sniffing capabilities, paired with a modern GUI.

**Key Features:**

* Real-time packet sniffing using Scapy
* Detection of port scans and flooding attacks
* DNS query logging and credential sniffing
* Email alerts via SMTP
* SQLite logging & export functionality
* GUI built with Tkinter and ttkbootstrap

**Technologies Used:** Python, Scapy, Matplotlib, SQLite, SMTP, Tkinter

**Run Instructions:**

```bash
pip install -r requirements.txt
python main.py
```

Setup environment variables in `.env` for email alerts.

---

### 3. 🔐 Secure File Storage System with AES-256 Encryption

A file encryption and decryption tool that secures files using AES-256, metadata logging, and integrity checks.

**Key Features:**

* AES-256 encryption & decryption
* File integrity verification with SHA-256
* Metadata logging and CSV export
* GUI using PyQt5 and drag-and-drop functionality
* CLI with secure password management

**Technologies Used:** Python, PyQt5, cryptography, hashlib

**Run Instructions:**

```bash
pip install -r requirements.txt
python gui_launcher.py   # GUI
python main.py encrypt <file> --password <password>   # CLI encrypt
python main.py decrypt <file> --password <password>   # CLI decrypt
pytest tests/test_main.py   # Run tests
```

---

## 📁 Repository Structure

```bash
cybersecurity-projects/
├── password_strength_analyzer/
├── network_sniffer_alert_system/
├── secure_file_storage_system/
├── requirements.txt
└── README.md
```

Each project folder contains its own source files, dependencies, and documentation.

---

## 🚀 How to Get Started

1. Clone the repository:

   ```bash
   git clone https://github.com/parthpanchal/cybersecurity-projects.git
   cd cybersecurity-projects
   ```

2. Navigate to the specific project folder and follow its instructions.

3. Install dependencies using:

   ```bash
   pip install -r requirements.txt
   ```

---

## 📄 License

MIT License – freely use, modify, and distribute with proper credit.

---

## 🙋‍♂️ About Me

I'm **Parth Panchal**, a cybersecurity enthusiast with hands-on experience in developing tools for vulnerability analysis, network monitoring, and secure data management. This repository reflects my skills and contributions during my internship at **Elevate Labs**.

Feel free to explore, learn, and contribute!
