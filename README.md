<div align="center">

# 👋 Hi, I'm Collins Chukwu

### 🛡️ SOC Analyst | Security Monitoring | Threat Detection

**Learning by building, investigating, detecting, and documenting real-world security scenarios.**

<p>
  <img src="https://img.shields.io/badge/SOC-Analyst-111111?style=for-the-badge&logo=shield&logoColor=white" />
  <img src="https://img.shields.io/badge/SIEM-Splunk-111111?style=for-the-badge&logo=splunk&logoColor=white" />
  <img src="https://img.shields.io/badge/Endpoint-Wazuh-111111?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Telemetry-Sysmon-111111?style=for-the-badge" />
</p>

</div>

---

# 🛡️ About Me

I'm Collins, an aspiring **SOC Analyst** building practical experience through hands-on security operations labs and investigation projects.

My SOC journey focuses on understanding how security events are generated, collected, detected, investigated, and documented.

Rather than only learning security concepts theoretically, I build controlled lab scenarios and investigate the resulting telemetry using tools commonly found in security operations environments.

### 🔎 My current SOC focus

* Security Monitoring
* SIEM Investigation
* Log Analysis
* Endpoint Telemetry
* Threat Detection
* Threat Hunting
* Incident Investigation
* PowerShell Investigation
* Process Analysis
* Network Security Monitoring
* Security Automation
* SOC Documentation

---

# 🧰 SOC Stack

## 📊 SIEM & Security Monitoring

<p align="center">   <img src="https://skillicons.dev/icons?i=windows,kali" height="55" /> </p>

<p align="center">


\

</p>

**Used for:** log collection, security monitoring, alert investigation, event correlation, and security analysis.

---

## 🖥️ Endpoint Telemetry

<p align="center">

\

</p>

**Telemetry I work with:**

`Process Creation` · `Network Connections` · `File Creation` · `Registry Activity`

---

## 🔍 Investigation & Detection

<p align="center">

\

</p>

**Investigation techniques:**

`Process Analysis` · `Parent/Child Relationships` · `Command-Line Analysis` · `Event Correlation` · `Timeline Analysis` · `IOC Investigation`

---

## 🌐 Network Investigation

<p align="center">
  <img src="https://skillicons.dev/icons?i=kali,linux" height="55" />
</p>

<p align="center">

\

</p>

**Focus:**

`Network Reconnaissance` · `Port Discovery` · `Service Enumeration` · `SMB Analysis`

---

## ⚙️ SOC Automation

<p align="center">

</p>

Exploring security automation and how repetitive SOC workflows can be connected and automated.

**Focus:**

`Alert Automation` · `Workflow Automation` · `Security Integrations` · `AI-Assisted SOC Workflows`

---

# 🧪 My SOC Lab

My SOC journey is built around a controlled virtual lab where I can generate security activity, collect telemetry, investigate events, and document findings.

```text
                    ┌──────────────────────┐
                    │      SOC Analyst     │
                    │  Investigate & Hunt   │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │        Splunk        │
                    │   SIEM / Analysis    │
                    └──────────┬───────────┘
                               │
                ┌──────────────┴──────────────┐
                │                             │
                ▼                             ▼
        ┌──────────────┐             ┌──────────────┐
        │    Wazuh     │             │    Sysmon    │
        │  Monitoring  │             │  Telemetry   │
        └──────┬───────┘             └──────┬───────┘
               │                            │
               └────────────┬───────────────┘
                            ▼
                    ┌──────────────┐
                    │ Windows 11   │
                    │   Endpoint   │
                    └──────────────┘

              Kali Linux → Security Testing
```

### Lab Environment

| Component            | SOC Role                          |
| -------------------- | --------------------------------- |
| 🪟 Windows 11        | Monitored endpoint                |
| 🔍 Splunk Enterprise | SIEM & investigation              |
| 🛡️ Wazuh            | Endpoint monitoring & alerting    |
| 📊 Sysmon            | Detailed endpoint telemetry       |
| 🐉 Kali Linux        | Security testing & reconnaissance |
| ⚙️ n8n               | Security automation               |
| 🖥️ VMware           | Virtualized lab environment       |

---

# 🚀 AI-SOC Journey

## `ai-soc-journey`

My primary cybersecurity portfolio documenting my progression toward becoming a SOC Analyst.

The repository contains hands-on projects involving:

### 📊 Security Monitoring

Collecting and analyzing endpoint and Windows security telemetry.

### 🔎 Investigation

Investigating suspicious activity using SIEM searches and endpoint data.

### 🧠 Detection Engineering

Developing queries and detection logic from observed security events.

### 🕵️ Threat Hunting

Searching telemetry for suspicious behaviors and indicators.

### 🚨 Incident Response

Following structured investigation workflows from alert → evidence → analysis → conclusion.

### ⚙️ Automation

Exploring how SOC processes can be automated using workflow automation and AI.

### 📝 Documentation

Documenting investigations, queries, observations, evidence, and conclusions.

👉 **[Explore my AI-SOC Journey →](https://github.com/Legacy-Col/ai-soc-journey)**

---

# 🔬 SOC Investigations

## `INC-001` — Suspicious PowerShell Activity

**Status:** Closed / Benign Lab Activity

**Environment:** Windows 11

**Tools:** Wazuh · Sysmon · Splunk

### Investigation Focus

* PowerShell process execution
* Parent/child process relationships
* Command-line analysis
* Process IDs
* Endpoint telemetry
* Event correlation
* Evidence-based investigation

The investigation demonstrated the importance of validating suspicious-looking activity against available telemetry and surrounding context rather than treating an alert as malicious solely based on its appearance.

---

# 📚 SOC Learning Roadmap

```text
                    SOC ANALYST JOURNEY
                           │
                           ▼
                 ┌──────────────────┐
                 │ Security Basics  │
                 └────────┬─────────┘
                          ▼
                 ┌──────────────────┐
                 │   SIEM / Logs    │
                 └────────┬─────────┘
                          ▼
                 ┌──────────────────┐
                 │ Endpoint         │
                 │ Telemetry        │
                 └────────┬─────────┘
                          ▼
                 ┌──────────────────┐
                 │ Investigation    │
                 └────────┬─────────┘
                          ▼
                 ┌──────────────────┐
                 │ Detection        │
                 │ Engineering      │
                 └────────┬─────────┘
                          ▼
                 ┌──────────────────┐
                 │ Threat Hunting   │
                 └────────┬─────────┘
                          ▼
                 ┌──────────────────┐
                 │ Incident         │
                 │ Response         │
                 └────────┬─────────┘
                          ▼
                 ┌──────────────────┐
                 │ Automation + AI  │
                 └──────────────────┘
```

---

# 📝 My Documentation Approach

> **If I can't support it with evidence, I don't claim it.**

Every investigation should answer:

**1. What happened?**

**2. What evidence was observed?**

**3. Why was it suspicious?**

**4. What additional evidence was investigated?**

**5. What was the final assessment?**

**6. What could be improved or investigated further?**

Where possible, my projects include:

* 🔹 SIEM queries
* 🔹 Event IDs
* 🔹 Telemetry
* 🔹 Screenshots
* 🔹 Process information
* 🔹 Network information
* 🔹 Investigation timelines
* 🔹 Evidence
* 🔹 Findings
* 🔹 Lessons learned

---

# 🎯 Current SOC Goals

* [x] Build a Windows security lab
* [x] Deploy Sysmon telemetry
* [x] Deploy Wazuh monitoring
* [x] Configure Splunk
* [x] Learn SIEM investigation
* [x] Investigate Windows processes
* [x] Investigate PowerShell activity
* [x] Practice network reconnaissance
* [ ] Build more realistic attack scenarios
* [ ] Develop detection rules
* [ ] Map detections to MITRE ATT&CK
* [ ] Build automated SOC workflows
* [ ] Integrate AI into SOC workflows
* [ ] Complete advanced investigation scenarios
* [ ] Continue building a professional SOC portfolio

---

# 📜 Certifications & Learning

### 🎓 Currently Preparing

**CompTIA Security+**

Focus areas include:

`Threats` · `Vulnerabilities` · `Security Operations` · `Network Security` · `Identity` · `Risk Management` · `Security Architecture`

### 📚 Completed Training

* Axia Africa — Cybersecurity Training
* HSC Consult — Cybersecurity Training

---

# 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Legacy-Col&show_icons=true&theme=tokyonight&hide_border=true" height="165"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Legacy-Col&layout=compact&theme=tokyonight&hide_border=true" height="165"/>

</div>

---

# 🤝 Connect With Me

<div align="center">

<a href="https://github.com/Legacy-Col">
<img src="https://img.shields.io/badge/GitHub-Legacy--Col-181717?style=for-the-badge&logo=github" />
</a>

<a href="YOUR_LINKEDIN_URL">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" />
</a>

<a href="mailto:YOUR_EMAIL">
<img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

</div>

---

<div align="center">

### 🛡️ Detect. Investigate. Respond. Automate.

**Building my SOC skills one investigation at a time.**

</div>
