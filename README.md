COMPANY: CODTECH IT SOLUTIONS

NAME: PITTA MEGHANA

INTERN ID: CT12MLF

DOMAIN: CYBER SECURITY AND ETHICAL HACKING

BATCH DURATION: FEBRUARY 5th, 2025 to MAY 5th, 2025

MENTOR NAME: NEELA SANTHOSH KUMAR

## 🛡️ Penetration Testing Toolkit

  A comprehensive and beginner-friendly **Python-based toolkit** for conducting essential **penetration testing and ethical hacking tasks**. It combines scanning, enumeration, and exploitation techniques in one modular, customizable CLI tool.

## 📖 About

  The **Penetration Testing Toolkit** is designed for cybersecurity learners and professionals who want a lightweight yet powerful set of tools for network and application assessment. The toolkit includes port scanning, service detection, basic vulnerability scanning, and brute-force functionality.


## ✨ Features

  - ⚡ Fast multi-threaded **port scanner**
  - 🔍 Banner grabbing and **service enumeration**
  - 📄 Detect common **vulnerabilities** using predefined checks
  - 🔐 **Brute-force** login modules for SSH/FTP (for educational use)
  - 📁 Easy to add new modules (modular design)
  - 👨‍💻 Command-line interface for quick execution

## 🧰 Technologies Used
  
  - Python 3.x
  - `socket`, `subprocess`, `paramiko`, `ftplib`
  - `argparse` for CLI
  - `threading` for performance
  - `colorama` for colored output

## 🚀 Getting Started

### 🔧 Prerequisites

  Install the required libraries:
  
  ```bash
  pip install paramiko colorama
  ````
  
  ### ⬇️ Clone the Repository
  
  ```bash
  git clone https://github.com/your-username/pen-testing-toolkit.git
  cd pen-testing-toolkit
  ```

## ⚙️ Usage

  ### 🔎 Port Scanning
  
  ```bash
  python toolkit.py --scan --target 192.168.1.1
  ```
  
  ### 🧠 Service Enumeration
  
  ```bash
  python toolkit.py --enum --target 192.168.1.1 --port 80
  ```
  
  ### 🔓 Brute Force (SSH)
  
  ```bash
  python toolkit.py --brute-ssh --target 192.168.1.1 --user root --wordlist passwords.txt
```

  ### 🔓 Brute Force (FTP)
  
  ```bash
  python toolkit.py --brute-ftp --target 192.168.1.1 --user admin --wordlist passwords.txt
  ```

⚠️ Disclaimer
  This toolkit is intended for **educational purposes** and authorized testing **only**. Unauthorized use against systems without permission is strictly prohibited and illegal.

