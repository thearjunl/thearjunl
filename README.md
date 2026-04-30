

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=45&duration=4500&pause=1500&color=00BFFF&center=true&vCenter=true&width=900&lines=Hi+👋+I'm+Arjun+L"/>



**SOC Analyst · Security Researcher · Builder of AI-Powered Security Tools**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-thearjunl-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thearjunl/)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-arjunl-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/arjunl)
[![LeetCode](https://img.shields.io/badge/LeetCode-thearjunl-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/thearjunl/)
[![Email](https://img.shields.io/badge/Email-theearjunl@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:theearjunl@gmail.com)
![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Opportunities-00FF41?style=flat-square)

</div>

---

## `whoami`

I'm an Integrated MCA graduate from Kerala, India, specialising in cybersecurity and secure application development. I don't just study security — I build tools that automate the boring parts of it.

My work sits at the intersection of AI and defensive security: SOC automation, IAM governance, penetration testing frameworks. If something can be done with a local LLM and a Python script, I'll build it.

Currently hunting for **SOC Analyst / Security Analyst roles** in India. CEH v13 in progress. Active on TryHackMe.

---

## 🔐 Projects

> These are the ones worth looking at. Each one solves a real problem.

---

### [KAALI](https://github.com/thearjunl/KAALI) — AI-Powered SOC Alert Correlation & Investigation Assistant

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_AI-4285F4?style=flat-square&logo=google&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

KAALI simulates a real SOC workflow end-to-end. It ingests raw security logs (Linux `auth.log`, Suricata IDS), detects anomalies like brute-force attempts, correlates multi-stage events into incidents, enriches them with threat intel from **AbuseIPDB** and **VirusTotal**, then calls **Google Gemini** to act as a senior analyst — generating MITRE ATT&CK-mapped summaries and remediation steps. A React dashboard surfaces everything for human review.

**What it actually does:**
- Parses and indexes real security logs into Elasticsearch in real-time
- Detects brute-force, lateral movement, and account compromise patterns
- Correlates individual alerts into incident chains (e.g. failed logins → successful login = Account Compromise)
- Generates executive-grade AI incident reports with ATT&CK mapping
- Auto-blocks attacker IPs via iptables on critical incidents

---

### [Ghost-Protocol](https://github.com/thearjunl/Ghost-Protocol) — Autonomous NHI Auditor for AWS IAM

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama_(Llama_3)-000000?style=flat-square)
![Athena](https://img.shields.io/badge/AWS_Athena-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

Enterprises run thousands of IAM roles consumed by services, not humans. These Non-Human Identities are almost always over-provisioned — they carry wildcard permissions but use a handful of API calls. Ghost-Protocol closes that gap.

**What it actually does:**
- Discovers every NHI role (EC2, Lambda, etc.) across your AWS account
- Correlates allowed permissions against real CloudTrail usage over 30 days via Athena
- Sends the delta to a **local LLM (Ollama/Llama 3)** which generates a scoped least-privilege replacement policy
- Quarantines high-risk identities immediately with a non-destructive Deny-All permissions boundary — no accidental deletions

> Cloud security + AI + zero dependency on third-party LLM APIs. Everything runs locally.

---

### [KUROKAMI](https://github.com/thearjunl/KUROKAMI) — AI-Driven Penetration Testing Framework

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-0073CF?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

Production-grade pen testing framework with LLM-powered module orchestration. Not a script wrapper — a full agentic loop that plans, executes, and reasons about findings.

**What makes it different:**
- AI orchestration: the LLM selects and sequences `k_*` modules based on target context, not a static scan order
- FAISS vector index for retrieval-augmented analysis — findings from past sessions inform current reasoning
- Complete audit trail: every action, finding, reasoning chain stored in SQLite/PostgreSQL
- Multi-format reports: JSON, HTML, PDF
- Production hardened: rate limiting, input validation, Fernet encryption, JWT auth, 70%+ test coverage
- Docker + Kubernetes manifests included

---

### [OriginCheck](https://github.com/thearjunl/OriginCheck) — AI Plagiarism Detector

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_AI-4285F4?style=flat-square&logo=google&logoColor=white)

Plagiarism detection using Google Programmable Search Engine for source discovery and Gemini AI for similarity analysis. Built to explore practical LLM integration for NLP tasks.

---

## 🏅 Certifications & Training

| Credential | Issuer | Status |
|---|---|---|
| CEH v13 — Certified Ethical Hacker | EC-Council | 🔵 In Progress |
| ISO/IEC 27001:2022 Lead Auditor | PECB | ✅ Completed |
| Cyber Threat Intelligence — CTIGA / CTI 101 | arcX | ✅ Completed |
| ISEA · CSEDP | Govt. of India | ✅ Completed |
| Google Cybersecurity Specialization | Google / Coursera | ✅ Completed |
| Oracle Cloud Infrastructure Generative AI | Oracle | ✅ Completed |
| TryHackMe — SOC Level 1 Path | TryHackMe | ✅ Active |

---

## 💼 Experience

**Security Analyst Intern** — Red Team Hacker Academy *(VAPT, vulnerability assessment, security tooling)*

**Software Developer Intern** — Zoople Technologies *(full-stack development, React, Node.js)*

---

## 🧰 Core Stack

```
Security      →  Wireshark · Nmap · Burp Suite · Metasploit · SIEM tools · MITRE ATT&CK
Cloud         →  AWS (IAM, CloudTrail, Lambda, Athena) · Oracle Cloud
Languages     →  Python · JavaScript · TypeScript · Java
Web           →  React · Next.js · FastAPI · Node.js · PostgreSQL · Supabase
AI / ML       →  Ollama · Gemini API · FAISS · LangChain-style RAG
OS            →  Linux (primary) · Windows
```

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=thearjunl&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=00BFFF&icon_color=00FF41&text_color=C9D1D9)

![GitHub Streak](https://streak-stats.demolab.com?user=thearjunl&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=00BFFF&ring=00FF41&fire=00BFFF&currStreakLabel=00BFFF)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=thearjunl&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=00BFFF&text_color=C9D1D9)

</div>

---

## 🌐 TryHackMe

<div align="center">

[![TryHackMe](https://tryhackme-badges.s3.amazonaws.com/arjunl.png)](https://tryhackme.com/p/arjunl)

</div>

---

## 🔭 Currently Working On

- `KAALI` — adding automated SIEM-style dashboards and multi-source log correlation
- `Ghost-Protocol` — multi-account AWS support and Terraform policy export
- CEH v13 practical labs and exam prep
- Actively applying for **SOC Analyst / Security Analyst** roles across India

---

## 📬 Let's Talk

If you're hiring for SOC / Security Analyst roles or want to collaborate on security tooling — reach out.

- 📧 [theearjunl@gmail.com](mailto:theearjunl@gmail.com)
- 💼 [linkedin.com/in/thearjunl](https://www.linkedin.com/in/thearjunl/)
- 🌐 Open to roles in Kerala, broader India, and remote-first positions

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/thearjunl/thearjunl/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/thearjunl/thearjunl/output/pacman-contribution-graph.svg">
  <img alt="contribution graph" src="https://raw.githubusercontent.com/thearjunl/thearjunl/output/pacman-contribution-graph.svg">
</picture>

![Profile Views](https://komarev.com/ghpvc/?username=thearjunl&color=00BFFF&style=flat-square&label=Profile+Views)

