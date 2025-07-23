# Ethical Hacking Lab Report (DVWA + Metasploitable2)

This project is a professional penetration testing assessment conducted in a local lab setup using Kali Linux, Metasploitable2, and DVWA (Damn Vulnerable Web Application).

> ⚠️ All testing was done in a controlled virtual environment for educational and ethical purposes only.

---

## 🔧 Tools Used

- Kali Linux (Attacker Machine)
- Metasploit Framework
- Nmap
- DVWA (Web Application Target)
- Metasploitable2 (Network Services Target)

---

## 🧪 Vulnerabilities Exploited

### 🖥️ Metasploitable2
- `vsftpd 2.3.4` — Backdoor Exploit
- `Samba smbd 3.0.20` — Remote Code Execution
- `Unreal IRC` — Backdoor Remote Shell

### 🌐 DVWA
- Command Injection (Low Security Level)

---

## 📂 Contents

- `Report.pdf` – Full penetration testing report with commands, methodology, and recommendations.
- `README.md` – Project summary and toolset overview.
- `screenshots/` – *(Optional)* Screenshots from exploitation sessions.

---

## ✅ Key Outcomes

- Gained root shell access on Metasploitable via 3 different exploits.
- Verified command execution on DVWA through insecure web input.
- Post-exploitation demonstrated privilege levels and possible lateral movement.
- Provided recommendations for system hardening and secure configuration.

---

## 📌 Note

This report was part of a technical assignment and demonstrates ethical hacking practices in a safe lab environment. No real-world systems were harmed.

