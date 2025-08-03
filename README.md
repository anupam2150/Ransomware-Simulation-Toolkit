# 🛡️ Ransomware Simulation Toolkit (Educational)

A **Python-based cybersecurity educational toolkit** designed to **safely simulate ransomware attacks** in isolated environments for hands-on training in **malware analysis**, **cryptography**, and **defensive security**.

> ⚠️ This project is strictly for educational and research purposes in controlled environments. Do not use on production systems.

---

## 🔍 Features

- 🔐 **AES-256 Encryption** of target files/folders
- 📄 **Ransom Note Generation** with customizable messages
- 🔑 **One-Time Decryption Key** support for secure key management
- 🖥️ Dual Interface: **CLI** + **Tkinter GUI**
- ♻️ **Recovery Mechanism** to restore encrypted files
- 🛠️ Simulates **Incident Response Workflows**
- 📚 Perfect for training in:
  - Malware behavior analysis
  - Symmetric key cryptography
  - Security operations & IR

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.8+
- Works on Windows, Linux (tested on Kali)
- Recommended: Use in VM or sandboxed environment

### 📦 Installation

```bash
git clone https://github.com/yourusername/ransomware-simulation-toolkit.git
cd ransomware-simulation-toolkit
pip install -r requirements.txt
```

### 🧪 Usage

#### GUI Mode
```bash
python gui_launcher.py
```

#### CLI Mode
```bash
python cli_ransomware.py --encrypt /path/to/files
python cli_ransomware.py --decrypt /path/to/encrypted --key YOUR_KEY
```

---

## 🧰 File Structure

```bash
├── gui_launcher.py           # Tkinter-based GUI interface
├── cli_ransomware.py         # CLI mode script
├── encryption.py             # AES-256 logic
├── key_manager.py            # Handles one-time keys
├── recovery.py               # Recovery and decryption workflow
├── ransom_note.txt           # Customizable ransom note
├── requirements.txt
└── README.md
```

---

## 🧠 Learning Objectives

- Understand how ransomware operates
- Learn AES encryption/decryption workflows
- Explore response and mitigation strategies
- Build cyber hygiene awareness

---

## 🛑 Disclaimer

This project is intended **solely for educational purposes**. Use only in **isolated lab setups**. The developer is **not responsible for any misuse**.

---

## 👨‍💻 Author

- **Anupam Shinde**  
  [LinkedIn](https://www.linkedin.com/in/anupamshinde/) • [GitHub](https://github.com/anupam2150)
