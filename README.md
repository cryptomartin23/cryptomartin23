<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=650&lines=Martin+Berg+%7C+Cybersecurity+Graduate+%F0%9F%94%90;Cloud+Hardening+%7C+Network+Security+%7C+Threat+Hunting;Breaking+things+responsibly+since+2024+%F0%9F%A7%A0;" />

<br/>

[![TryHackMe](https://img.shields.io/badge/TryHackMe-Active-red?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/cryptomartin)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Martin_Berg-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/martin-berg-337a1586)
[![Portfolio](https://img.shields.io/badge/martinberg.work-live-00FF41?style=flat-square&logo=vercel&logoColor=black)](https://martinberg.work)
[![Email](https://img.shields.io/badge/Email-contact-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mail.martinberg.work)

</div>

-----

```
╔══════════════════════════════════════════════════════════════╗
║  $ whoami                                                    ║
║                                                              ║
║  > Cybersecurity graduate · Gokstad Acadamy, 2026          ║
║  > Specialty: cloud hardening, network security, red/blue    ║
║  > Capstone: 3-tier Azure MVP · NIST CSF 2.0 assessed        ║
║  > Based in Norway · Available for security roles            ║
║                                                              ║
║  "Build it. Break it. Harden it. Document it."              ║
╚══════════════════════════════════════════════════════════════╝
```

-----

## 🏗 Featured Project — Goktek Azure MVP

> A production-deployed, hardened 3-tier Azure network architecture built as a capstone project at Gokstad Akademiet, assessed against NIST CSF 2.0 and mapped to the NICE Framework.

|Layer    |Subnet        |Component                                       |
|---------|--------------|------------------------------------------------|
|🟥 DMZ    |`10.10.1.0/24`|nginx reverse proxy · Cloudflare TLS termination|
|🟧 APP    |`10.10.2.0/24`|WordPress 6.9.1 · nginx + php-fpm               |
|🟦 BACKEND|`10.10.3.0/24`|MariaDB 11.4.3 · no public exposure             |

**VNet:** `10.10.0.0/16` · **Region:** `norwayeast` · **VMs:** Ubuntu 22.04 on `Standard_B2s`

**Security controls implemented:**

- 🔒 Cloudflare TLS with origin certificates — end-to-end encryption
- 🕸 Tailscale WireGuard mesh VPN — zero-trust admin access, no exposed SSH
- 🔥 Azure NSGs with strict deny-by-default inbound rules
- 🔎 Nuclei v3.7.1 vulnerability scan — **8 findings (F-1–F-8)** identified & remediated
- 📋 NIST CSF 2.0 control mapping · NICE Framework role **IO-WRL-004**


-----

## 🛠 Tech Stack

**Cloud & Infrastructure**

![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu_22.04-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-WireGuard-243746?style=for-the-badge&logo=wireguard&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)

**Security Tooling**

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burp-suite&logoColor=white)

**Platforms & OS**

![Fedora](https://img.shields.io/badge/Fedora-51A2DA?style=for-the-badge&logo=fedora&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

**Frameworks & Standards**

![NIST](https://img.shields.io/badge/NIST_CSF_2.0-003087?style=for-the-badge&logoColor=white)
![NICE](https://img.shields.io/badge/NICE_Framework-IO--WRL--004-1B4F72?style=for-the-badge&logoColor=white)
![MITRE](https://img.shields.io/badge/MITRE_ATT%26CK-red?style=for-the-badge&logoColor=white)

-----



-----

## 🎯 Certifications & Training

|Status    |Credential                                     |Platform               |
|----------|-----------------------------------------------|-----------------------|
|✅ Complete|Cybersecurity Graduate                         |Gokstad Akademiet, 2026|
|✅ Complete|ISC2 Certified in Cybersecurity                |ISC2             , 2026|
|🔨 Active  |TryHackMe — Security paths                     |TryHackMe              |
|📌 


-----
## 🎓 Education

<div align="center">

![Degree](https://img.shields.io/badge/Degree-Higher%20Vocational%20Education-0d1117?style=for-the-badge&logo=academia&logoColor=cyan&labelColor=0d1117&color=00bcd4)
![Institution](https://img.shields.io/badge/Gokstad%20Akademiet-Sandefjord%2C%20Norway-0d1117?style=for-the-badge&logo=graduation-cap&logoColor=white&labelColor=161b22&color=6e40c9)
![Credits](https://img.shields.io/badge/Credits-120%20ECTS-0d1117?style=for-the-badge&logo=checkmarx&logoColor=white&labelColor=161b22&color=00bcd4)
![NQF Level](https://img.shields.io/badge/NQF-Level%205.2-0d1117?style=for-the-badge&logo=buffer&logoColor=white&labelColor=161b22&color=6e40c9)
![NOKUT](https://img.shields.io/badge/NOKUT-Accredited-0d1117?style=for-the-badge&logo=verified&logoColor=white&labelColor=161b22&color=2ea043)

</div>

### Fagskole — Cybersikkerhet · Gokstad Akademiet `2024–2026`

**Higher Vocational Degree in Cyber Security** — 120 credits, NQF Level 5.2  
Accredited by NOKUT · Issued 19 June 2026

---

#### 📋 Academic Results

| Code | Subject | Credits |
|------|---------|:-------:|
| CYB1001 | Introduction to Programming | 15.0 |
| DBS1001 | Database Systems | 7.5 |
| DTEK1001 | Digital Technology | 7.5 |
| INF103 | Information Security | 22.5 |
| RVI202 | Frameworks & ISMS | 7.5 |
| CFS202 | Cyber Defence & Security | 15.0 |
| SEH202 | Software Security & Ethical Hacking | 15.0 |
| ESS203 | Enterprise Systems & Security Architecture | 10.0 |
| MTC203 | Security in IoT & Machine Type Communication | 10.0 |
| PRO203 | Capstone Project | 10.0 |

---

#### 🧠 Knowledge & Competencies

- **Security Architecture** — Enterprise systems, ISMS frameworks, security design patterns
- **Ethical Hacking & Penetration Testing** — Planning and executing tests individually and in teams, in accordance with legal and ethical guidelines
- **Cyber Defence** — Threat intelligence, national/local threat landscape assessment, defensive security operations
- **Software Security** — Vulnerability analysis, secure code review, ethical hacking methodology
- **Information Security** — Confidentiality, integrity, availability; GDPR and Norwegian privacy law compliance
- **Database & Digital Systems** — Applied database architecture in cybersecurity contexts
- **IoT & Machine Type Communication** — Security considerations for connected devices and MTC environments
- **Web Technologies** — HTML/CSS applied in security tooling and web projects

#### ⚡ General Competencies

- Plans and executes **ethical hacking and penetration testing** projects independently and in teams
- Applies **industry frameworks** (NIST, ISO 27001 / ISMS) to real-world security work
- Capable of **organisational security development** — translating knowledge into actionable security improvements
- Engages with professional networks across IT disciplines and communicates with system administrators and stakeholders
- Continuously updates vocational knowledge through professional information gathering and industry contact

-----

## 🤝 Let’s Connect

I’m actively looking for **security analyst**, **cloud security**, or **junior pentesting** roles in Norway (remote-friendly welcome).

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/martin-berg-337a1586)
[![Email](https://img.shields.io/badge/Email-Say_Hi-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mail@martinberg.work)
[![Portfolio](https://img.shields.io/badge/martinberg.work-Visit-00FF41?style=for-the-badge&logo=vercel&logoColor=black)](https://martinberg.work)

</div>

-----

<div align="center">
  <sub>⚡ <i>"The quieter you become, the more you are able to hear."</i> — Kali Linux</sub>
</div>
