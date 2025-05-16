<h1 align="center" id="title">PayloadMaster</h1>

<p align="center" id="description">
PayloadMaster is a Bash-based toolkit that automates the creation of Metasploit payloads, sets up listeners, scans for MS17-010 vulnerabilities, and exploits Windows targets using EternalBlue. Designed for ethical hacking, it simplifies the workflow for penetration testers, students, and cybersecurity professionals in controlled environments.
</p>

---

## 🧐 Features

- Supports payload creation for **Windows**, **Linux**, and **Android** platforms.
- Interactive selection of payload types (`meterpreter`, `shell_reverse_tcp`, etc.).
- Scans for **MS17-010 (EternalBlue)** vulnerabilities.
- Exploits vulnerable **Windows systems** using EternalBlue.
- Enables **Remote Desktop (VNC)** on compromised Windows targets.
- Creates **HTA-based phishing servers** for Windows payload delivery.
- Automates **Metasploit listener setup** with selected parameters.

---

## ⚙️ Prerequisites

- **Metasploit Framework** (`msfconsole`, `msfvenom`)
- Bash Shell (Linux/macOS)
- Internet connection (optional, but recommended)
- Root privileges (for most exploit tasks)

---

## 🛠️ Installation Steps

1. **Clone the repository:**

```bash
git clone https://github.com/lohitkolluri/PayloadMaster.git
