<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=42&duration=4000&pause=1500&color=FF4444&center=true&vCenter=true&width=900&lines=Hi+%F0%9F%91%8B+I'm+Arjun+L;Offensive+Security+%7C+AI+%2B+Hacking;I+break+things+ethically." />

**Offensive Security · Penetration Testing · AI-Powered Attack Tooling**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-thearjunl-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thearjunl/)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-arjunl-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/arjunl)
[![Portfolio](https://img.shields.io/badge/Portfolio-thearjunl.vercel.app-FF4444?style=flat-square&logo=vercel&logoColor=white)](https://thearjunl.vercel.app/)
[![Email](https://img.shields.io/badge/Email-arjunlputhuvelil333@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:arjunlputhuvelil333@gmail.com)
![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Offensive%20Security%20Roles-FF4444?style=flat-square)

</div>

---

## `whoami`

```bash
$ cat /etc/arjun.conf

Name        : Arjun L
Degree      : Integrated MCA — Cybersecurity (2026), Amal Jyothi College of Engineering, Kerala
Focus       : Offensive Security · Penetration Testing · AI/LLM Security Research
Internships : Red Team Hacker Academy (VAPT) · WIN in Life Academy (Cybersecurity)
CEH         : v13 — In Progress
Status      : Actively seeking Offensive Security / Penetration Testing roles
```

I'm a cybersecurity graduate who builds tools that attack things — ethically. My work sits at the intersection of offensive security and AI: agentic pentesting frameworks, LLM security research, phishing detection ML, and cloud IAM attack surface analysis.

I don't just study OWASP Top 10. I build systems that automate finding it.

---

## 🔴 Projects — The Ones Worth Looking At

---

### [KUROKAMI](https://github.com/thearjunl/KUROKAMI) — Agentic LLM-Driven Penetration Testing Framework

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS_RAG-0073CF?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

A production-grade agentic pentesting framework where the LLM doesn't just assist — it **orchestrates**. KUROKAMI plans, sequences, and reasons about findings using a FAISS vector index over real CVE and MITRE ATT&CK data. Not a script wrapper. A full autonomous attack loop.

**Security-relevant internals:**
- LLM selects and sequences attack modules (`k_*`) based on target context — dynamic, not static
- RAG over CVE/MITRE ATT&CK data for context-aware exploit reasoning
- Full audit trail: every action, reasoning chain, and finding stored in SQLite/PostgreSQL
- Fernet encryption, JWT auth, rate limiting, input validation — security-hardened by design
- Multi-format reports: JSON, HTML, PDF
- **LLM security research**: includes prompt injection resistance testing and agentic attack surface boundary analysis
- Docker + Kubernetes manifests for reproducible deployment

> *The first tool I built that made me realize how dangerous a poorly sandboxed LLM agent actually is.*

---

### [Nizhal](https://github.com/thearjunl/Nizhal) — ML-Based Phishing Detection Chrome Extension

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![ML](https://img.shields.io/badge/Random_Forest-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

Manifest V3 Chrome extension for real-time phishing URL detection. Random Forest ML model served via FastAPI, layered with Google Safe Browsing API. Built to tackle OWASP A05 (Security Misconfiguration) and social engineering vectors at the browser level.

**What it covers:**
- Real-time URL feature extraction and classification (ML + rule-based hybrid)
- Google Safe Browsing API integration for layered threat validation
- Sub-100ms detection latency for seamless browsing
- Addresses OWASP Top 10: phishing, credential harvesting, malicious redirects

---

### [Ghost-Protocol](https://github.com/thearjunl/Ghost-Protocol) — Autonomous NHI Auditor for AWS IAM

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama_(Llama_3)-000000?style=flat-square)
![Athena](https://img.shields.io/badge/AWS_Athena-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

Enterprises run thousands of IAM roles consumed by services, not humans. These Non-Human Identities are almost always over-provisioned. Ghost-Protocol finds that gap and closes it — autonomously.

**Attack surface covered:**
- Discovers every NHI role (EC2, Lambda, OIDC) across AWS account
- Correlates allowed permissions vs real CloudTrail usage (30-day window) via Athena
- Local LLM (Ollama/Llama 3) generates scoped least-privilege replacement policies
- Quarantines high-risk identities instantly with non-destructive Deny-All boundary
- Cloud security + IAM attack surface + zero third-party LLM dependency

---

### [KAALI](https://github.com/thearjunl/KAALI) — AI-Powered SOC Alert Correlation Engine

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_AI-4285F4?style=flat-square&logo=google&logoColor=white)

End-to-end SOC workflow simulation. Ingests raw Linux `auth.log` and Suricata IDS logs, detects brute-force and lateral movement, correlates multi-stage events into incidents, enriches with AbuseIPDB + VirusTotal intel, and uses Gemini to generate MITRE ATT&CK-mapped incident reports. Auto-blocks attacker IPs via iptables on critical incidents.

---

## 🛠️ Offensive Security Stack

```
Pentesting     →  Burp Suite · Nmap · Metasploit · Wireshark · Nikto
Web Security   →  OWASP Top 10 · SQLi · XSS · SSRF · IDOR · API Security
Cloud          →  AWS IAM · CloudTrail · Lambda · Athena · Oracle Cloud
AI/LLM Sec    →  Prompt Injection · SSRF via Agents · Agentic Attack Surface Research
Languages      →  Python · JavaScript · TypeScript · Bash
Frameworks     →  FastAPI · React · Next.js · Node.js
ML/AI          →  Ollama · FAISS · Gemini API · scikit-learn · RAG pipelines
OS             →  Kali Linux · Ubuntu · Windows
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
> Security operations, threat analysis, cybersecurity awareness training

**Security Analyst Intern** — Red Team Hacker Academy
> VAPT, vulnerability assessment, offensive security tooling, ethical hacking techniques

**Software Developer Intern** — Zoople Technologies
> Full-stack development (React, Node.js, Python Django), secure coding practices

---

## 🔭 Currently Working On

- `KUROKAMI` — expanding LLM security research: prompt injection vectors and agentic SSRF scenarios
- `Ghost-Protocol` — multi-account AWS support and Terraform least-privilege policy export
- CEH v13 practical labs and exam prep
- Actively applying for **Offensive Security Intern / Penetration Testing** roles

---

## 📬 Let's Talk

If you're hiring for offensive security, pentesting, or security engineering — reach out.

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

![Profile Views](https://komarev.com/ghpvc/?username=thearjunl&color=FF4444&style=flat-square&label=Profile+Views)

</div>
