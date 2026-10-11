<h1 align="center">Hi, I'm Jawher 👋</h1>
<h3 align="center">Cybersecurity Engineer · SOC Analysis · Linux & System Administration</h3>

<p align="center">
  📍 Tunisia &nbsp;|&nbsp; 🗣️ Arabic · French · English
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/yahyawi-jawher-3625a7186"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://tryhackme.com/p/yhjawher"><img src="https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white"/></a>
  <a href="mailto:jawher.contact@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

---

## 🛡️ About me

Cybersecurity engineer with a networks & systems background, working at the intersection of **security operations** and **infrastructure administration**. I harden the systems I manage, build the detections that watch them, and automate the response.

- 🔎 **Security operations:** alert triage, log analysis, phishing and malware investigation, IOC enrichment, MITRE ATT&CK mapping
- 🎯 **Detection engineering:** Sigma rules and native Wazuh rules, unit-tested against real attack and benign logs
- 🖥️ **System administration:** Linux / Red Hat administration, Ansible automation, network services, NOC supervision
- 📡 **Monitoring:** Prometheus, Grafana and Alertmanager; infrastructure supervision with Nagios in a banking environment (Société Tunisienne de Banque)
- 🏢 **Production experience:** IT Support Technician at Innova Soft: NOC supervision, ticketing, Linux/Red Hat admin, network services
- 🤖 **Builder:** creator of **SOC-AI**, an AI-enhanced SOC platform with LLM triage and human-approved SOAR containment

---

## 🧰 Technical stack

### 🔐 Security operations
**SIEM & detection:** Wazuh · Splunk · ELK Stack · Sigma · Suricata<br>
**Network security:** Wireshark · Snort · Zeek · FortiGate<br>
**Endpoint & logs:** Sysmon · Windows Event Logs · Linux auditd / syslog<br>
**Threat intel:** VirusTotal · AbuseIPDB · AnyRun · URLScan<br>
**SOAR & automation:** n8n · Python · LLM-assisted triage<br>
**Frameworks:** MITRE ATT&CK · Cyber Kill Chain · Pyramid of Pain

### 🖥️ System & network administration
**Operating systems:** Red Hat / RHEL · Linux · Windows Server / Active Directory<br>
**Hardening:** SELinux · firewalld · SSH · sysctl · auditd<br>
**Services:** DNS · DHCP · SSH · Apache / Nginx · user & permission management<br>
**Networking:** TCP/IP · routing & switching · VLANs · firewalls<br>
**Monitoring:** Prometheus · Grafana · Alertmanager · Nagios<br>
**Automation & DevOps:** Ansible · Bash · Docker · Git · GitHub Actions · CI/CD

<p>
  <img src="https://skillicons.dev/icons?i=linux,redhat,ansible,bash,python,docker,prometheus,grafana,elasticsearch,fastapi,react,postgres,githubactions,git&theme=dark"/>
</p>

---

## 📂 Featured projects

| Project | Area | Description |
|---|---|---|
| [**SOC-AI**](https://github.com/jawherxxd/Soc-AI) | SOC / SOAR | AI-enhanced SOC: Wazuh + Suricata alerts correlated and triaged by an LLM, enriched with threat intel, with human-approved FortiGate containment via n8n |
| [**Detection Rules**](https://github.com/jawherxxd/detection-rules) | Detection engineering | 13 Sigma rules (Linux auditd + Active Directory) unit-tested in CI, mapped to MITRE ATT&CK v19, with native Wazuh rules and Splunk / Wazuh queries |
| [**Ansible Linux Production Hardening**](https://github.com/jawherxxd/ansible-linux-production-hardening) | SysAdmin / Security | Lockout-safe RHEL hardening: SSH, SELinux, firewalld, sysctl, auditd mapped to MITRE ATT&CK, auto-updates, and a PASS/FAIL compliance report |
| [**Infra Monitoring Stack**](https://github.com/jawherxxd/infra-monitoring) | SysAdmin / Monitoring | Hardened Prometheus + Grafana + Alertmanager stack: 25 unit-tested alerts (security controls, SELinux, SOC-AI dead-man's switch), Telegram alerts, node_exporter Ansible role |

### 🔗 How they fit together

```mermaid
flowchart LR
    A["🛡️ Hardening<br/>Ansible: SELinux, SSH,<br/>firewalld, auditd"] -->|audit logs| B["🎯 Detection Rules<br/>Sigma + Wazuh"]
    B -->|alerts| C["🤖 SOC-AI<br/>LLM triage + SOAR"]
    D["📈 Monitoring<br/>Prometheus + Grafana"] -.->|watches| A
    D -.->|watches| C
```

---

## 🎓 Education

- **Engineering degree in Cybersecurity** – Tek-Up University
- **Licence en Technologie de l'Informatique**, Networks & Computer Systems – ISET Tozeur (2019–2022)

---

## 💼 Open to

**SOC Analyst** · **System Administrator** · **Security / Infrastructure Engineer** roles in Tunisia or remote, with French or English-speaking teams.

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jawherxxd&show_icons=true&theme=tokyonight&hide_border=true" height="160"/>
</p>
