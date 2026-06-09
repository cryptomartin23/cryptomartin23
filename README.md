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
║  "Build it. Break it. Document it. Harden it."              ║
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

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=YOURUSERNAME&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00FF41&icon_color=00FF41&text_color=c9d1d9" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOURUSERNAME&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00FF41&text_color=c9d1d9" />

</div>

-----

## 🎯 Certifications & Training

|Status    |Credential                                     |Platform               |
|----------|-----------------------------------------------|-----------------------|
|✅ Complete|Cybersecurity Graduate                         |Gokstad Akademiet, 2026|
|✅ Complete|ISC2 Certified in Cybersecurity                |ISC2             , 2026|
|🔨 Active  |TryHackMe — Security paths                     |TryHackMe              |
|📌 
<div align="center">
  <img src="https://tryhackme-badge.ra0.io/YOURUSERNAME" alt="TryHackMe Badge" />
</div>

-----

## 📡 Currently


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
  <img src="https://komarev.com/ghpvc/?username=YOURUSERNAME&style=flat-square&color=00FF41&label=profile+views" />
  <br/><br/>
  <sub>⚡ <i>"The quieter you become, the more you are able to hear."</i> — Kali Linux</sub>
</div>
