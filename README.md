<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=38&duration=3500&pause=1200&color=00D4FF&center=true&vCenter=true&width=900&lines=Hi+%F0%9F%91%8B+I'm+Arjun+L;Application+Security+%7C+Offensive+Security;I+build+secure+systems+by+understanding+how+they+break." />

**Application Security · Offensive Security · AI/LLM Security Research**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-thearjunl-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thearjunl/)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-arjunl-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/arjunl)
[![Portfolio](https://img.shields.io/badge/Portfolio-thearjunl.vercel.app-00D4FF?style=flat-square&logo=vercel&logoColor=white)](https://thearjunl.vercel.app/)
[![Email](https://img.shields.io/badge/Email-arjunlputhuvelil333@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:arjunlputhuvelil333@gmail.com)
![Status](https://img.shields.io/badge/Status-Open%20to%20AppSec%20%7C%20Security%20Engineering%20%7C%20Offensive%20Security-00D4FF?style=flat-square)

</div>

---

## `whoami`

```bash
$ cat /etc/arjun.conf

Name          : Arjun L
Degree        : Integrated MCA — Cybersecurity (2026)
College       : Amal Jyothi College of Engineering, Kerala

Focus         : Application Security · Offensive Security · AI/LLM Security
Internships   : WIN in Life Academy · Red Team Hacker Academy · Zoople Technologies

AppSec Skills : Vulnerability Triage & Remediation
                Secure SDLC (SSDLC) Optimization
                OWASP Top 10 · Threat Modeling
                Security Automation & Tooling
                CI/CD Security · Docker · Kubernetes

Languages     : Python · JavaScript · TypeScript · Bash · Go (learning)
Certifications: ISO/IEC 27001:2022 Lead Auditor
                Google Cybersecurity Professional Certificate
                CEH v13 (In Progress)

Status        : Open to Application Security, Security Engineering,
                Product Security, and Offensive Security opportunities
```

I'm a cybersecurity graduate who builds security solutions at the intersection of **Application Security**, **Offensive Security**, and **AI/LLM Security Research**.

I've worked on vulnerability management, SSDLC automation, web and API security testing, security tooling development, and AppSec reporting dashboards — across internships and production-grade projects. I don't just study OWASP Top 10. I build systems that find, track, and remediate it.

---

## 🛡️ Projects — Built for Real Security Impact

---

### [Argus](https://github.com/thearjunl/Argus) — Application Security Automation Platform

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

A production-grade Application Security automation platform designed to optimize **Secure Software Development Lifecycle (SSDLC)** workflows — reducing manual effort in vulnerability tracking, triage, and remediation.

**What Argus does:**
- Full vulnerability lifecycle management — intake, triage, assignment, remediation tracking, validation
- CVSS severity scoring and automated risk classification
- OWASP Top 10 vulnerability categorization with remediation guidance
- AI-powered remediation recommendations surfaced in context
- Real-time Application Security dashboards for team-level metrics
- Automated PDF security report generation for stakeholders
- JWT-based authentication with RBAC
- Dockerized deployment with CI/CD pipeline integration

> *Built after observing how much time security teams spend on spreadsheets instead of fixing vulnerabilities. Argus automates the workflow so engineers can focus on what matters.*

---

### [KUROKAMI](https://github.com/thearjunl/KUROKAMI) — Agentic LLM-Driven Penetration Testing Framework

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS_RAG-0073CF?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

A production-grade agentic pentesting framework where the LLM doesn't just assist — it **orchestrates**. KUROKAMI plans, sequences, and reasons about findings using a FAISS vector index over real CVE and MITRE ATT&CK data.

**Security-relevant internals:**
- LLM dynamically selects and sequences attack modules (`k_*`) based on target context
- RAG over CVE/MITRE ATT&CK data for context-aware exploit reasoning
- Full audit trail: every action, reasoning chain, and finding stored in SQLite/PostgreSQL
- Fernet encryption, JWT auth, rate limiting, input validation — security-hardened by design
- Multi-format reports: JSON, HTML, PDF
- **LLM security research**: prompt injection resistance testing and agentic attack surface boundary analysis
- Docker + Kubernetes manifests for reproducible deployment

> *The project that made me deeply understand how dangerous a poorly sandboxed LLM agent is — and how to defend against it.*

---

### [Nizhal](https://github.com/thearjunl/Nizhal) — ML-Based Phishing Detection Chrome Extension

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![ML](https://img.shields.io/badge/Random_Forest-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

Manifest V3 Chrome extension for real-time phishing URL detection. Random Forest ML model served via FastAPI, layered with Google Safe Browsing API. Directly addresses **OWASP A05** and social engineering attack vectors at the browser level.

**What it covers:**
- Real-time URL feature extraction and ML + rule-based hybrid classification
- Google Safe Browsing API integration for layered threat validation
- Sub-100ms detection latency
- Covers phishing, credential harvesting, and malicious redirect scenarios from OWASP Top 10

---

### [Ghost-Protocol](https://github.com/thearjunl/Ghost-Protocol) — Autonomous NHI Auditor for AWS IAM

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama_(Llama_3)-000000?style=flat-square)
![Athena](https://img.shields.io/badge/AWS_Athena-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

Enterprises run thousands of IAM roles consumed by services, not humans. These Non-Human Identities are almost always over-provisioned. Ghost-Protocol identifies that gap and closes it — autonomously.

**What it covers:**
- Discovers every NHI role (EC2, Lambda, OIDC) across an AWS account
- Correlates allowed permissions vs real CloudTrail usage (30-day window) via Athena
- Local LLM (Ollama/Llama 3) generates scoped least-privilege replacement policies
- Quarantines high-risk identities instantly with non-destructive Deny-All boundary
- Zero third-party LLM dependency

---

### [KAALI](https://github.com/thearjunl/KAALI) — AI-Powered SOC Alert Correlation Engine

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_AI-4285F4?style=flat-square&logo=google&logoColor=white)

End-to-end SOC workflow simulation. Ingests raw Linux `auth.log` and Suricata IDS logs, detects brute-force and lateral movement, correlates multi-stage events into incidents, enriches with AbuseIPDB + VirusTotal threat intel, and uses Gemini to generate MITRE ATT&CK-mapped incident reports. Auto-blocks attacker IPs via iptables on critical incidents.

---

## 🛠️ Security & Engineering Stack

```
Application Security  →  SSDLC · Vulnerability Management · OWASP Top 10
                          Threat Modeling · Security Automation · AppSec Dashboards
                          Burp Suite · OWASP ZAP · CVE Triage

Web & API Security    →  SQLi · XSS · SSRF · IDOR · API Security Testing
                          OWASP Top 10 Exploitation & Remediation

Cloud Security        →  AWS IAM · CloudTrail · Lambda · Athena · Oracle Cloud

AI/LLM Security       →  Prompt Injection · SSRF via Agents
                          Agentic Attack Surface Research

Languages             →  Python · JavaScript · TypeScript · Bash

Frameworks            →  FastAPI · React · Next.js · Node.js · Python Django

DevSecOps             →  Docker · Kubernetes · CI/CD Pipelines · Git · GitHub Actions

ML/AI                 →  Ollama · FAISS · Gemini API · scikit-learn · RAG Pipelines

OS                    →  Kali Linux · Ubuntu · Windows
```

---

## 🏅 Certifications

| Credential | Issuer | Status |
|---|---|---|
| CEH v13 — Certified Ethical Hacker | EC-Council | 🔵 In Progress |
| ISO/IEC 27001:2022 Lead Auditor | PECB | ✅ Completed |
| Cyber Threat Intelligence — CTIGA / CTI 101 | arcX / Red Team Leaders | ✅ Completed |
| CSEDP — Social Engineering Defense | The SecOps Group | ✅ Completed |
| Google Cybersecurity Specialization | Google / Coursera | ✅ Completed |
| Oracle Cloud Infrastructure Generative AI | Oracle | ✅ Completed |
| ISEA — Information Security Awareness | Govt. of India | ✅ Completed |
| TryHackMe — SOC Level 1 Path | TryHackMe | ✅ Active |

---

## 💼 Experience

**Cybersecurity Intern** — WIN in Life Academy *(March 2026 – Present)*
> Vulnerability triage and remediation validation · SSDLC support · Burp Suite & OWASP ZAP testing · Python security automation · Threat modeling · Cybersecurity awareness training

**Security Analyst Intern** — Red Team Hacker Academy
> VAPT · Web and API penetration testing · Vulnerability assessment and reporting · Offensive security tooling · OWASP Top 10 exploitation and documentation

**Software Developer Intern** — Zoople Technologies
> Full-stack development (React · Node.js · Python Django) · Secure coding practices · CI/CD pipeline experience

---

## 🔭 Currently Working On

- `Argus` — expanding SSDLC automation: GitHub Actions integration and JIRA vulnerability sync
- `KUROKAMI` — expanding LLM security research: prompt injection vectors and agentic SSRF scenarios
- `Ghost-Protocol` — multi-account AWS support and Terraform least-privilege policy export
- CEH v13 practical labs and exam prep
- Open to **Application Security**, **Security Engineering**, **Product Security**, and **Offensive Security** roles

---

## 📬 Let's Talk

If you're building a security engineering team or hiring for AppSec, security tooling, or offensive security roles — reach out.

- 📧 [arjunlputhuvelil333@gmail.com](mailto:arjunlputhuvelil333@gmail.com)
- 💼 [linkedin.com/in/thearjunl](https://www.linkedin.com/in/thearjunl/)
- 🌐 [thearjunl.vercel.app](https://thearjunl.vercel.app/)
- 📍 Kerala, India — open to Bangalore onsite, pan-India, and remote roles

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/thearjunl/thearjunl/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/thearjunl/thearjunl/output/pacman-contribution-graph.svg">
  <img alt="contribution graph" src="https://raw.githubusercontent.com/thearjunl/thearjunl/output/pacman-contribution-graph.svg">
</picture>

![Profile Views](https://komarev.com/ghpvc/?username=thearjunl&color=00D4FF&style=flat-square&label=Profile+Views)

</div>
