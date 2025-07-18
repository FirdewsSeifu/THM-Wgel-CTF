# 🧠 TryHackMe - Wgel CTF Write-Up

This repository contains my write-up for the **TryHackMe - Wgel CTF** room. It covers the steps taken to gain user and root access through enumeration, SSH exploitation, and privilege escalation.

---

## 🗂️ Contents

- `THM-Wgel-CTF.md` – Step-by-step walkthrough with screenshots.

---

## 🔧 Tools Used

- Nmap  
- Gobuster  
- SSH  
- Netcat  
- Wget  
- Linux enum commands

---

## 🏁 Summary

- Enumerated open ports and web content  
- Discovered `.ssh` directory and extracted private key  
- Gained SSH access as `jessie`  
- Found user flag  
- Used `sudo wget` to exfiltrate root flag

---

## 📌 Notes

- All testing was done in a legal TryHackMe environment.  
- For educational purposes only.

---

## 🔗 Author

- GitHub: [@FirdewsSeifu](https://github.com/FirdewsSeifu)
