<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,35:1e1b4b,65:0a3d62,100:00b4d8&height=190&section=header&text=Ashish%20Kumar&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Security%2C%20backend%20and%20agentic%20AI&descAlignY=58&descSize=19&descColor=7dd3fc&animation=fadeIn" width="100%" alt="Ashish Kumar"/>

<a href="https://github.com/Ashiii27">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&width=760&lines=B.Tech+CSE+student+at+MMMUT%2C+graduating+2027;I+work+on+security+tools+and+backend+systems;Lately+I+have+been+building+agents+with+LangChain;Currently+working+on+MCPGuard" alt="B.Tech CSE student at MMMUT, graduating 2027"/>
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ashiii27-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashiii27/)
[![GitHub](https://img.shields.io/badge/GitHub-Ashiii27-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ashiii27)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top_3%25-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/Ashiii27)
[![Portfolio](https://img.shields.io/badge/Portfolio-My_Site-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-website-flax-seven-68.vercel.app)
[![Email](https://img.shields.io/badge/Email-ashiii.2790%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ashiii.2790@gmail.com)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Ashiii27&label=Profile%20Views&color=0ea5e9&style=flat)
![Followers](https://img.shields.io/github/followers/Ashiii27?label=Followers&style=flat&color=7c3aed&logo=github&logoColor=white)

</div>

## About me

Hi, I'm Ashish. I'm a B.Tech CSE student at MMMUT, Gorakhpur, graduating in 2027.

I got into cybersecurity first. Most of my early time went into SOC labs, TryHackMe (top 3% there now), Windows logs and packet captures. Along the way I kept feeling that reading about attacks was not enough, I wanted to build the things I was trying to defend. That is what pushed me towards backend development.

These days my time is split three ways: security tools, backend work in Python, Go and TypeScript, and AI agents. The agent side is fairly recent and honestly the most interesting to me right now, mostly because it brings the other two together. An agent that can call tools is basically a backend with a mind of its own, and it needs the same care with permissions, input checks and logging that any other system does. Probably more.

What I'm up to at the moment:

- Building [MCPGuard](https://github.com/Ashiii27/mcpguard), a small proxy that checks MCP tool calls before they run. It looks for leaked secrets, prompt injection and writes to files that should not be touched.
- Working through LangChain and agent patterns in [agenticLangChain](https://github.com/Ashiii27/agenticLangChain). I mostly care about how agents use tools and where that can go wrong.
- Looking for internships in security, backend or AI engineering, in that area or somewhere in between.

## What I work on

### Security

This is where I started, and I still spend a good amount of time here. Log and PCAP analysis, Windows event logs, writing detections and mapping them to MITRE ATT&CK, that sort of thing. Most of my early repos are home labs and small tools from learning this.

### Backend

Python, Go and TypeScript, usually FastAPI or Express on top. I try to pay attention to the unglamorous parts: auth, validation, rate limits, decent error handling. The [backend-projects](https://github.com/Ashiii27/backend-projects) repo is where a lot of my practice code lives.

### Agentic AI

LangChain agents, MCP and tool calling. My interest here is less about making agents do impressive demos and more about what happens when they are given real access to files, APIs and shells. That is the problem MCPGuard came out of.

## Tools I use

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=py,go,ts,js,cpp,bash,powershell&perline=7" alt="Python, Go, TypeScript, JavaScript, C++, Bash, PowerShell"/>

**Backend and APIs**

<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,flask,postgres,supabase,postman&perline=7" alt="Node.js, Express, FastAPI, Flask, PostgreSQL, Supabase, Postman"/>

**Other stuff**

<img src="https://skillicons.dev/icons?i=react,vite,tailwind,docker,git,github,githubactions,linux,vercel&perline=9" alt="React, Vite, Tailwind, Docker, Git, GitHub, GitHub Actions, Linux, Vercel"/>

</div>

A few more specific ones that do not have neat icons:

| Area | Things I use |
| :--- | :--- |
| AI / agents | LangChain, MCP, Groq and Gemini models, Pydantic for structured output |
| Security | MITRE ATT&CK, Wireshark, Sigma rules, STIX 2.1, JA3 fingerprinting |
| Forensics | EVTX parsing, FTK Imager, Autopsy, Windows registry, timeline work |

## Projects

These are the ones I would point to first. The rest of my repos are mostly notes, labs and things I built while learning.

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/Ashiii27/mcpguard">MCPGuard</a></h3>
<p>A security proxy for the Model Context Protocol, written in Python with no dependencies. It sits between an MCP client and server and checks every tool call before it goes through. If it spots a secret in the arguments, signs of prompt injection, or a write to a sensitive path, the call gets blocked. This started because I could not find a simple way to do this and wanted to see if I could build one.</p>
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/MCP-Tool_calls-7C3AED?style=flat"/>
</p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/Ashiii27/honeypot-network">Honeypot Network</a></h3>
<p>A honeypot setup in Go that pretends to be six services at once: SSH, HTTP, FTP, SMB, MySQL and Redis. It records what attackers actually do, credentials they try, commands they run, files they upload, then maps that behaviour to MITRE ATT&amp;CK and pulls out IOCs. There is a React dashboard that streams it live and lets you replay SSH sessions.</p>
<p>
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/Ashiii27/WinLogin-Forensics">WinLogin Forensics</a></h3>
<p>Parses Windows authentication logs and lines up logons across Local, MSA, RDP and Kerberos so odd access patterns are easier to spot. Works with event IDs 4624, 4625, 4648, 4768 and 4776. I co-authored an IEEE paper based on this work with Dr. Vimal Kumar at MMMUT, which is how this project started.</p>
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/IEEE-Paper-701C1C?style=flat&logo=ieee&logoColor=white"/>
</p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/Ashiii27/SentinelX">SentinelX</a></h3>
<p>A network intrusion detection system in C++. I wrote the packet parsing pipeline myself (capture, then IP, TCP and HTTP) instead of leaning on a library for all of it, mostly to understand what was actually inside a packet. Detectors plug in through a common interface and the alerts come out tagged with severity and ATT&amp;CK techniques.</p>
<p>
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/libpcap-Packet_capture-00B4D8?style=flat"/>
</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/Ashiii27/PCAP-Forensics-Analyser">PCAP Forensics Analyser</a></h3>
<p>A command line tool for picking apart packet captures. It rebuilds TCP sessions, pulls IOCs out of HTTP, DNS, FTP and TLS traffic, and flags things like port scans, DNS tunnelling and cleartext logins. It also does JA3 fingerprinting, which is a neat trick I picked up from how real NDR tools identify malware traffic. Output is JSON, so it can feed into other tooling.</p>
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Wireshark-PCAP-1679A7?style=flat&logo=wireshark&logoColor=white"/>
</p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/Ashiii27/cve-explorer">CVE Explorer</a></h3>
<p>A small web app for searching CVEs with live data from the NVD and Exploit-DB. Nothing fancy, it was one of my earlier full stack builds and a good way to learn how a frontend and an API fit together. It is deployed if you want to click around.</p>
<p>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black"/>
</p>
</td>
</tr>
</table>

### Other repos worth a look

| Repo | Notes |
| :--- | :--- |
| [Agentic LangChain](https://github.com/Ashiii27/agenticLangChain) | My LangChain notes and experiments, written from a security angle. Safe tool use, prompt injection, validating model output with Pydantic. |
| [Backend Projects](https://github.com/Ashiii27/backend-projects) | Practice backend work in TypeScript and JavaScript. REST APIs, an Express server, a tested HTTP API. |
| [Exposure](https://github.com/Ashiii27/Exposure) | Shows what a web page gets up to behind your back: trackers, fingerprinting scripts, third party requests, plotted as a graph. Work in progress. |
| [CyberSecurity HomeLabs](https://github.com/Ashiii27/CyberSecurity-HomeLabs-Setup) | The DFIR home lab I set up with a Windows VM and WSL for practising investigations. For whatever reason this is my most starred repo. |

## A bit of background

| | |
| :--- | :--- |
| TryHackMe | Top 3% globally. Mostly SOC and blue team paths. |
| IEEE paper | Co-authored a paper on Windows authentication forensics with Dr. Vimal Kumar, MMMUT. |
| PSB Hackathon 2026 | Built MAFIA at the PSB Cybersecurity Hackathon (IIT Hyderabad and Bank of India), an Android malware and fraud checker with a WhatsApp bot on the front and a dashboard behind it. |
| College | B.Tech CSE, MMMUT Gorakhpur, class of 2027. |

## GitHub stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Ashiii27&show_icons=true&include_all_commits=true&count_private=true&rank_icon=github&hide_border=true&bg_color=0d1117&title_color=22d3ee&icon_color=a78bfa&text_color=c9d1d9" alt="GitHub stats for Ashiii27"/>
&nbsp;
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ashiii27&layout=compact&langs_count=8&hide_border=true&bg_color=0d1117&title_color=22d3ee&text_color=c9d1d9" alt="Languages I use most"/>

<br/><br/>

<img height="170" src="https://streak-stats.demolab.com/?user=Ashiii27&hide_border=true&background=0d1117&stroke=22d3ee&ring=a78bfa&fire=22d3ee&currStreakNum=ffffff&sideNums=ffffff&currStreakLabel=22d3ee&sideLabels=a78bfa&dates=8b949e" alt="Contribution streak"/>

<br/><br/>

<img width="94%" src="https://github-readme-activity-graph.vercel.app/graph?username=Ashiii27&bg_color=0d1117&color=22d3ee&line=a78bfa&point=ffffff&area=true&hide_border=true" alt="Activity over time"/>

</div>

## Contribution graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="assets/github-snake.svg"/>
  <img alt="Contribution graph" src="assets/github-snake-dark.svg"/>
</picture>

<sub>The snake is generated from my actual contribution data and lives in this repo under <code>assets/</code>, so it does not depend on any outside service. It is a snapshot rather than a live feed for now.</sub>

</div>

<div align="center">

## Get in touch

LinkedIn or email is the fastest way to reach me. I read everything, replies might take a day or two if college is busy.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ashiii27-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashiii27/)
&nbsp;
[![Email](https://img.shields.io/badge/Email-ashiii.2790%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ashiii.2790@gmail.com)
&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-My_Site-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-website-flax-seven-68.vercel.app)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4d8,35:0a3d62,65:1e1b4b,100:0d1117&height=110&section=footer" width="100%" alt=""/>

</div>
