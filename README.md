<div align="center">

# `root@github:~$ whoami`

### Root3301

**Cybersecurity · Infrastructure · OSINT · Digital Investigation**

*Building, securing and understanding systems — then probably breaking them again in the homelab.*

<br>

<a href="https://root3301.fr">
  <img src="https://img.shields.io/badge/root3301.fr-Portfolio-18181B?style=for-the-badge&logo=firefoxbrowser&logoColor=white">
</a>
<a href="https://github.com/Rooot3301">
  <img src="https://img.shields.io/badge/GitHub-Rooot3301-181717?style=for-the-badge&logo=github&logoColor=white">
</a>
<a href="https://www.twitch.tv/Root33011">
  <img src="https://img.shields.io/badge/Twitch-Root33011-9146FF?style=for-the-badge&logo=twitch&logoColor=white">
</a>

</div>

---

## `> whoami`

I'm a 🇫🇷 **Cybersecurity & Infrastructure Technician** working with real-world production environments, Linux systems, virtualization, networking, endpoint security and automation.

Outside of work, I spend most of my time experimenting with infrastructure, building tools, investigating how things work and running a slightly unreasonable homelab.

```text
root@github
│
├── cybersecurity
│   ├── infrastructure security
│   ├── digital investigation
│   ├── network analysis
│   ├── OSINT
│   └── security automation
│
├── infrastructure
│   ├── Linux
│   ├── Proxmox / VMware
│   ├── networking & firewalls
│   ├── monitoring
│   └── self-hosting
│
├── development
│   ├── Python
│   ├── Bash
│   ├── JavaScript / Node.js
│   └── automation tooling
│
└── side_quests
    ├── homelab
    ├── space & science-fiction
    ├── Star Citizen
    ├── content creation
    └── 33011 Digital
```

My philosophy is pretty simple:

> **Understand the system. Automate what can be automated. Secure what matters.**

---

## `> cat current-focus.txt`

🔐 **Infrastructure security** — hardening, segmentation, endpoint protection and monitoring  
🐧 **Linux** — administration, automation and migration of services  
🕵️ **OSINT** — passive reconnaissance and digital investigation  
⚙️ **Automation** — removing repetitive infrastructure work with scripts and tooling  
🏠 **Homelab** — experimenting with networking, virtualization and self-hosted services  
🔬 **Security research** — understanding systems from both defensive and offensive perspectives  

---

## `> ls ./stack`

### Infrastructure

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=flat-square&logo=vmware&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?style=flat-square&logo=opnsense&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-212121?style=flat-square&logo=pfsense&logoColor=white)

### Security & Monitoring

![SentinelOne](https://img.shields.io/badge/SentinelOne-6E1BFF?style=flat-square&logoColor=white)
![NinjaOne](https://img.shields.io/badge/NinjaOne-0066CC?style=flat-square&logoColor=white)
![Graylog](https://img.shields.io/badge/Graylog-FF3633?style=flat-square&logo=graylog&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![AdGuard](https://img.shields.io/badge/AdGuard-68BC71?style=flat-square&logo=adguard&logoColor=white)

### Development & Automation

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

---

## `> ls ./projects --featured`

<table>
<tr>
<td width="50%" valign="top">

### 🔍 NETTRACE

**Passive OSINT domain analysis toolkit.**

Collect and correlate publicly available information about domains without relying on paid APIs.

**Features**
- WHOIS analysis
- DNS enumeration
- Certificate transparency
- Passive subdomain discovery
- JSON / TXT reports
- Domain trust scoring

**Stack**

`Python` `OSINT` `DNS` `WHOIS`

<a href="https://github.com/Rooot3301/NETTRACE">View repository →</a>

</td>

<td width="50%" valign="top">

### ⚙️ Ninjaa

**Linux RMM Agent Manager.**

Tooling designed to automate deployment, maintenance and diagnostics of RMM agents across Linux systems.

**Features**
- RPM & DEB support
- systemd management
- Agent health checks
- Integrity verification
- SELinux / AppArmor detection
- Automation-friendly CLI

**Stack**

`Bash` `Linux` `systemd` `Automation`

<a href="https://github.com/Rooot3301/Ninjaa">View repository →</a>

</td>
</tr>
</table>

---

## `> ./tracesic --status`

### 🐉 Tracesic

**Digital Investigation Workspace — Work in progress**

A local-first desktop workspace designed for cyber and forensic investigations.

The objective is to bring together the different parts of an investigation into a single structured environment:

```text
case
├── artifacts
├── evidence
├── notes
├── timeline
├── relationships
└── reports
```

Built around the idea that investigation tooling should assist the analyst — **not replace their judgement**.

`Python` · `PySide6` · `SQLite` · `SQLAlchemy` · `Pydantic`

> Currently under development.

---

## `> sudo homelab status`

### 🏠 Homelab

My homelab is where most bad ideas become good learning experiences.

```text
                         INTERNET
                            │
                            ▼
                    ┌──────────────┐
                    │   FIREWALL   │
                    │   OPNsense   │
                    └──────┬───────┘
                           │
                 VLANs / IDS / IPS
                           │
                    ┌──────▼───────┐
                    │   NETWORK    │
                    │    10 GbE    │
                    └──────┬───────┘
                           │
                ┌──────────▼──────────┐
                │       PROXMOX       │
                │                     │
                ├── Monitoring        │
                ├── DNS               │
                ├── Security tooling  │
                ├── Development       │
                ├── Self-hosting      │
                └── Experiments       │
                └─────────────────────┘
```

It gives me a playground to experiment with:

`Virtualization` · `Networking` · `VLANs` · `Firewalls` · `Linux` · `Containers` · `Monitoring` · `Security`

without discovering in production that *“technically it worked in the lab”*.

---

## `> ls ./other-interests`

Cybersecurity isn't the only thing running in my brain.

🚀 Space & space exploration  
🌌 Science fiction  
🛰️ Star Citizen & Squadron 42  
📸 Virtual photography  
🎥 Content creation  
🛠️ Digital & community projects  

I'm also building projects through **33011 Digital**, mixing technology, content and the universes I'm passionate about.

---

## `> git log --graph --oneline`

<p align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/Rooot3301/Rooot3301/output/github-contribution-grid-snake-dark.svg?v=2"
    />
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/Rooot3301/Rooot3301/output/github-contribution-grid-snake.svg?v=2"
    />
    <img
      alt="GitHub contribution snake"
      src="https://raw.githubusercontent.com/Rooot3301/Rooot3301/output/github-contribution-grid-snake.svg?v=2"
    />
  </picture>
</p>

---

## `> github-stats`

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=Rooot3301&show_icons=true&include_all_commits=true&count_private=true&theme=transparent&hide_border=true"
    height="165"
    alt="GitHub stats"
  />
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs?username=Rooot3301&layout=compact&langs_count=6&theme=transparent&hide_border=true"
    height="165"
    alt="Most used languages"
  />
</p>

---

## `> spotify --recent`

<p align="center">
  <a href="https://open.spotify.com/user/root3301">
    <img
      src="https://spotify-recently-played-readme.vercel.app/api?user=root3301&count=5&unique=true"
      alt="Spotify recently played"
    />
  </a>
</p>

---

## `> contact`

<p align="center">

<a href="https://root3301.fr">
  <img src="https://img.shields.io/badge/Website-root3301.fr-18181B?style=for-the-badge&logo=firefoxbrowser&logoColor=white">
</a>
<a href="https://github.com/Rooot3301">
  <img src="https://img.shields.io/badge/GitHub-Rooot3301-181717?style=for-the-badge&logo=github&logoColor=white">
</a>
<a href="https://www.twitch.tv/Root33011">
  <img src="https://img.shields.io/badge/Twitch-Root33011-9146FF?style=for-the-badge&logo=twitch&logoColor=white">
</a>

</p>

<p align="center">
  <code>root@root3301.fr:~$ █</code>
</p>

<p align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=Rooot3301.Rooot3301" alt="Profile visitors">
</p>
