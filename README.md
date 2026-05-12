<div align="center">

# Ashish Kumar

**B.Tech CSE · MMMUT Gorakhpur · Graduating August 2026**

Seeking roles in **SOC Analysis · Blue Team Engineering · Digital Forensics**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ashiii27-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashiii27/)
[![GitHub](https://img.shields.io/badge/GitHub-Ashiii27-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Ashiii27)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top%203%25%20Globally-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/Ashiii27)

</div>

---

## About

Blue team-focused security engineer with hands-on experience in threat detection, Windows log forensics, and network traffic analysis. Currently building real-world tools that map to MITRE ATT&CK and correlate multi-source authentication artifacts — the kind of work that sits at the core of modern SOC and DFIR operations.

**Areas of depth:** Network Intrusion Detection · EVTX Forensics · PCAP Analysis · Incident Response · OSINT

---

## Projects

### [SentinelX](https://github.com/Ashiii27/SentinelX) — C++ Network Intrusion Detection System

A modular NIDS built from scratch that captures live traffic, parses it through a custom pipeline, and maps detections to MITRE ATT&CK techniques with structured alert output.

- Custom `PacketCapture → IP → TCP → HTTP` parser pipeline with pluggable detector architecture via abstract `BaseDetector` interface
- Alert system with severity classification and ATT&CK technique tagging
- Designed for extensibility — new detection modules added without touching core logic

**Stack:** C++ · libpcap · MITRE ATT&CK Framework

---

### [WinLogon Forensics](https://github.com/Ashiii27/Windows-Login-Extractor) — Multi-Auth Artifact Correlation

Forensics tool that correlates Windows authentication artifacts across Local Accounts, Microsoft Accounts, RDP, and Active Directory / Kerberos — surfacing anomalous access patterns from EVTX logs.

- Parses and cross-correlates key Event IDs: 4624, 4625, 4648, 4768, 4776, and more
- Flags suspicious patterns across authentication mechanisms in a unified view
- IEEE-format research paper in progress under supervision of Dr. Vimal Kumar, MMMUT

**Stack:** Python · PowerShell · EVTX Parsing · FTK Imager · Autopsy · Wireshark

---

### [PCAP Forensics Analyser](https://github.com/Ashiii27/PCAP-Forensics-Analyser) — Network Traffic Forensics

Deep PCAP analysis tool for protocol dissection, IOC extraction, and anomaly flagging from captured network traffic.

---

## Skills

| Category | Skills |
|---|---|
| **Languages** | C++ · Python · PowerShell |
| **Tools** | Wireshark · FTK Imager · Autopsy · Kali Linux · VS Code |
| **Domains** | Threat Detection · MITRE ATT&CK · EVTX/Windows Forensics · PCAP Analysis · Incident Response · OSINT |

---

## Certifications & Learning

| Status | Platform / Certification |
|---|---|
| 🟢 Active | TryHackMe — **Top 3% globally** |
| 🟡 In Progress | LetsDefend · CyberDefenders · PortSwigger Web Security Academy |
| 📌 Next | CompTIA Security+ |
| 🗺️ Roadmap | CySA+ → TCM Security PTP → OSCP |

---

## GitHub Activity

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com/?user=Ashiii27&theme=github-dark-blue&hide_border=true)](https://github.com/Ashiii27)

</div>

---

<div align="center">
<sub>Open to SOC Analyst, Blue Team, and Digital Forensics roles · Available August 2026</sub>
</div>
