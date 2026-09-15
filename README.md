<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f1724,45:0b63ff,100:ff2d55&height=190&section=header&text=Nikodem%20Mahlik&fontSize=44&fontColor=e6eef8&fontAlignY=38&desc=Cybersecurity%20Enthusiast%20%C2%B7%20SOC%20%2B%20Red%20Team%20%C2%B7%20Gda%C5%84sk,%20PL&descAlignY=58&descSize=16" alt="Nikodem Mahlik — Cybersecurity Enthusiast" />

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=19&pause=1200&color=10B981&center=true&vCenter=true&width=700&height=45&lines=Computer+Science+student+%7C+Cybersecurity+major;SOC:+Splunk+%2B+Sysmon+%2B+MITRE+ATT%26CK;Offensive:+Burp+Suite,+Nmap,+Metasploit;Building+Hackademy+%E2%80%94+my+own+CTF+platform" alt="What I do" />

<br/>

<a href="https://xnikko.github.io/portfolio/"><img src="https://img.shields.io/badge/Portfolio-0b63ff?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/nikodem-mahlik/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://tryhackme.com/p/NikkO"><img src="https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=88cc14" alt="TryHackMe" /></a>
<img src="https://img.shields.io/badge/Gda%C5%84sk%2C%20Poland-1f2937?style=for-the-badge&logo=googlemaps&logoColor=ff2d55" alt="Location" />
<img src="https://img.shields.io/badge/Open%20to%20work-10b981?style=for-the-badge&logo=statuspage&logoColor=white" alt="Open to work" />

</div>

---

## `whoami`

Computer Science student specialising in **cybersecurity**, based in Gdańsk. I work both sides of the line: I build detections and triage incidents, then attack my own labs to see where they fall apart.

- 🛡️ **Blue team** — running an **Active Directory home lab** wired into **Splunk**, mapping attacks to **MITRE ATT&CK** and writing detection rules on Sysmon telemetry
- ⚔️ **Red team** — web app security and network pentesting, TryHackMe **Jr Penetration Tester** path
- 🧪 **Builder** — I turn what I learn into tools: a CTF platform, a pocket SOC dashboard, a honeypot, a file integrity monitor
- 💼 Internship at **[@Seargin](https://github.com/Seargin)** — SIEM & Log Analysis
- 📫 Reach me on [LinkedIn](https://www.linkedin.com/in/nikodem-mahlik/) · full portfolio at **[xnikko.github.io/portfolio](https://xnikko.github.io/portfolio/)**

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🎯 Hackademy
**CTF platform with original scenarios**

Hands-on security learning through simulated real-world IT incidents — scenario engine, flag database, virtual terminals, user management.

`React` `TailwindCSS` `Java` `Spring Boot` `PostgreSQL`

[**Live demo →**](https://hackademy-front.onrender.com/)
<sub>Free Render hosting — cold start takes 1–3 min.</sub>

</td>
<td width="50%" valign="top">

### 🔍 AD Home Lab — Threat Detection
**Active Directory + SIEM detection engineering**

Segmented AD environment feeding Splunk Enterprise. Attack simulation with Atomic Red Team, detections mapped to MITRE ATT&CK, hardening via GPO.

`Active Directory` `Splunk` `Sysmon` `PowerShell` `Kali`

[**Network diagram →**](https://xnikko.github.io/portfolio/schematsieci.png)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📱 [SIEM-Mobile](https://github.com/xNikkO/siem-mobile)
**Pocket SOC dashboard for Splunk**

Polls the Splunk REST API for Sysmon events, classifies them CRITICAL / WARNING / INFO with rule-based correlation (encoded PowerShell, IEX downloads, LOLBins, log clears), and serves a mobile-style alert feed.

`Python` `Kivy` `Splunk REST API`

[![Stars](https://img.shields.io/github/stars/xNikkO/siem-mobile?style=flat&color=0b63ff&labelColor=1f2937)](https://github.com/xNikkO/siem-mobile)
[![Demo](https://img.shields.io/badge/video%20demo-ff2d55?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=kFst2ubFmDQ)

</td>
<td width="50%" valign="top">

### 🕵️ [Fake-Login Honeypot](https://github.com/xNikkO/fake-login-honeypot)
**HTTP honeypot with credential capture**

Serves a decoy login page, records harvested credentials and attacker metadata, and pushes real-time alerts to Discord via webhook.

`Python` `HTTP` `Discord Webhooks`

[![Repo](https://img.shields.io/badge/source-1f2937?style=flat&logo=github&logoColor=white)](https://github.com/xNikkO/fake-login-honeypot)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧬 [File Integrity Monitor](https://github.com/xNikkO/File-Integrity-Monitor)
**FIM with VirusTotal enrichment**

Watches filesystem changes and hashes tracked files, with optional VirusTotal scanning of executables to flag known-bad binaries.

`Python` `Hashing` `VirusTotal API`

[![Stars](https://img.shields.io/github/stars/xNikkO/File-Integrity-Monitor?style=flat&color=0b63ff&labelColor=1f2937)](https://github.com/xNikkO/File-Integrity-Monitor)

</td>
<td width="50%" valign="top">

### 🧾 [Vinted Scraper](https://github.com/xNikkO/VintedScraper)
**OSINT-style seller tracker**

Tracks Vinted sellers over time, recording active and sold listings straight into Google Sheets for analysis.

`Python` `Scraping` `Google Sheets API`

[![Stars](https://img.shields.io/github/stars/xNikkO/VintedScraper?style=flat&color=0b63ff&labelColor=1f2937)](https://github.com/xNikkO/VintedScraper)

</td>
</tr>
</table>

<sub>🎮 Off-duty: [SlimeSurvivor](https://github.com/xNikkO/SlimeSurvivor) — a survivor-like game in Godot/GDScript. 🎓 Coursework lives on my university account: [@NikkodemM](https://github.com/NikkodemM).</sub>

---

## Arsenal

<table>
<tr>
<th align="left" width="33%">🛡️ SOC &amp; Analysis</th>
<th align="left" width="33%">⚔️ Offensive &amp; Web</th>
<th align="left" width="33%">⚙️ Dev &amp; Infrastructure</th>
</tr>
<tr valign="top">
<td>

- SIEM: **Splunk**, Elastic Stack
- EDR: **CrowdStrike Falcon**
- Log analysis (Syslog, auth.log)
- Traffic analysis — **Wireshark**
- Incident triage &amp; **MITRE ATT&amp;CK**

</td>
<td>

- Web: **Burp Suite**, OWASP ZAP
- SQLi, SSRF, CSRF, IDOR, Cmd Injection
- Network: **Nmap**, **Metasploit**
- Privilege escalation (Linux &amp; Windows)
- Atomic Red Team simulation

</td>
<td>

- **Python** automation, **Bash** scripting
- **Java / Spring Boot**, TypeScript, React
- Linux administration, **Docker**
- PostgreSQL, MySQL, MongoDB
- Networking fundamentals (**CCNA**)

</td>
</tr>
</table>

<div align="center">

<img src="https://skillicons.dev/icons?i=python,bash,powershell,java,spring,js,ts,react,tailwind,postgres,mysql,mongodb,docker,linux,git,aws,cpp,godot&perline=9" alt="Tech stack" />

</div>

---

## Certifications &amp; Paths

<div align="center">

[![CCNA](https://img.shields.io/badge/CCNA:%20Introduction%20to%20Networks-049fd9?style=for-the-badge&logo=cisco&logoColor=white)](https://xnikko.github.io/portfolio/certificate-CCNA.pdf)
[![Jr Penetration Tester](https://img.shields.io/badge/Jr%20Penetration%20Tester-212C42?style=for-the-badge&logo=tryhackme&logoColor=88cc14)](https://tryhackme.com/certificate/THM-6R9EE67UBD)
[![Pre Security](https://img.shields.io/badge/Pre%20Security-212C42?style=for-the-badge&logo=tryhackme&logoColor=88cc14)](https://tryhackme.com/certificate/THM-ZAEYDTGZQ2)
[![Web Fundamentals](https://img.shields.io/badge/Web%20Fundamentals-212C42?style=for-the-badge&logo=tryhackme&logoColor=88cc14)](https://tryhackme.com/certificate/THM-TEAANL4KH7)
[![CyberSecurity 101](https://img.shields.io/badge/CyberSecurity%20101-212C42?style=for-the-badge&logo=tryhackme&logoColor=88cc14)](https://tryhackme.com/certificate/THM-FCU7HU6SRY)
[![Advent of Cyber 2025](https://img.shields.io/badge/Advent%20of%20Cyber%202025-212C42?style=for-the-badge&logo=tryhackme&logoColor=88cc14)](https://tryhackme-certificates.s3-eu-west-1.amazonaws.com/THM-M4FKUXECDS.pdf)

</div>

---

## Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=xNikkO&theme=dark&hide_border=true&background=0f1724&ring=0b63ff&fire=ff2d55&currStreakLabel=10b981&sideLabels=94a3b8&dates=94a3b8" />
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com/?user=xNikkO&theme=default&hide_border=true&ring=0b63ff&fire=ff2d55&currStreakLabel=0b63ff" />
  <img src="https://streak-stats.demolab.com/?user=xNikkO&hide_border=true" alt="GitHub streak stats" width="500" />
</picture>

</div>

<div align="center">
<sub><code>All systems operational.</code></sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff2d55,55:0b63ff,100:0f1724&height=110&section=footer" alt="" />
</div>
