<h1 align="center" id="title">PayloadMaster</h1>

<p id="description">PayloadMaster is a bash script that streamlines the process of creating Metasploit payloads setting up listeners for different platforms scanning for MS17-010 vulnerabilities and exploiting Windows targets using MS17-010 (EternalBlue).</p>

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Supports Windows Linux and Android platforms.
*   Allows you to choose the payload type based on the selected platform.
*   Scans for MS17-010 vulnerabilities.
*   Exploits Windows targets using MS17-010 (EternalBlue).
*   Enables Remote Desktop on Windows targets using MS17-010.
*   Creates payloads with a link (HTA Server).

<h2>⚙️ Prerequisites</h2>

* Metasploit Framework
* Bash shell (Linux and macOS)

<h2>🛠️ Installation Steps:</h2>

<p>1. Clone the repository:</p>

```
git clone https://github.com/lohitkolluri/PayloadMaster.git
```

<p>2. Navigate to the script directory:</p>

```
cd PayloadMaster
```

<p>3. Make the script executable:</p>

```
chmod +x payloadmaster.sh
```

<p>4. Run the script:</p>

```
./payloadmaster.sh
```

<p>5. Follow the on-screen instructions to create payloads scan for vulnerabilities and exploit targets.</p>

# PayloadMaster: Metasploit Automation Script for Ethical Penetration Testing

**PayloadMaster** is a Bash-based toolkit that automates the creation of payloads and execution of common Metasploit modules. It's designed to simplify tasks for ethical hackers, cybersecurity students, and penetration testers working in controlled environments or training labs.

## 🚀 Features

- Generate payloads for Windows, Linux, and Android using `msfvenom`
- Automatically launch Metasploit listeners (`multi/handler`)
- Scan for MS17-010 (EternalBlue) vulnerabilities
- Exploit vulnerable Windows systems using EternalBlue
- Enable remote desktop (VNC) access on compromised systems
- Create HTA phishing payload servers

## ⚠️ Disclaimer

> This tool is provided **strictly for educational purposes**, ethical hacking practice, and authorized penetration testing only.
>
> ⚠️ **Unauthorized use** of this script on networks or devices you do not own or have **explicit permission** to test is **illegal** and may result in **criminal prosecution**.
>
> The creator of this tool is **not responsible** for any misuse, damages, or legal consequences caused by this software.
>
> Always follow local laws and industry standards for ethical hacking and obtain proper consent before engaging in any form of security testing.

## 🧪 Intended Use

This tool is ideal for:
- CTFs (Capture The Flag competitions)
- Cybersecurity labs (e.g., TryHackMe, HackTheBox)
- Internal network testing with client approval
- Education and learning in ethical hacking courses

## 🛠️ Requirements

- Linux or macOS terminal
- Metasploit Framework installed (`msfconsole`, `msfvenom`)
- Root privileges for network operations

## 📦 How to Run

```bash
chmod +x payloadmaster.sh
./payloadmaster.sh


<h2>🛡️ License:</h2>

This project is licensed under the [MIT License](LICENSE)
