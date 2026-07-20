# 🛡️ AI-Powered SOC Automation Lab

> Enterprise SOC Home Lab built using **Wazuh SIEM**, **Docker**, **Sysmon**, **Windows 10**, **Kali Linux**, and **n8n Security Automation**.

![License](https://img.shields.io/badge/License-MIT-green)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-SIEM-blue)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-orange)
![Automation](https://img.shields.io/badge/n8n-Automation-red)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

# 📌 Overview

This project demonstrates how to build a complete **Security Operations Center (SOC)** home lab using Dockerized Wazuh SIEM.

The lab simulates a real enterprise security monitoring environment where security events are collected from a Windows endpoint, analyzed by Wazuh SIEM, and automatically processed using n8n workflows.

The project focuses on:

- Security Monitoring
- Threat Detection
- Incident Investigation
- Security Automation
- Docker Deployment
- Threat Intelligence Integration

---

# 🎯 Objectives

- Build a Dockerized SOC Lab
- Deploy Wazuh SIEM
- Monitor Windows Security Events
- Simulate Cyber Attacks
- Detect Threats
- Automate Alert Handling
- Build Security Automation using n8n
- Create a reusable SOC portfolio project

---

# 🏗️ Lab Architecture

```text
                     Kali Linux
                          │
                 Attack Simulation
                          │
                          ▼
             Windows 10 + Sysmon + Wazuh Agent
                          │
                  Windows Event Logs
                          │
                          ▼
                   Wazuh Manager
                          │
                 Detection Rules
                          │
                          ▼
                 Wazuh Dashboard
                          │
                    Webhook Trigger
                          │
                          ▼
                       n8n Workflow
                          │
              Automated Incident Handling
```

---

# ⚙️ Technologies Used

| Category | Technology |
|----------|------------|
| SIEM | Wazuh 4.14 |
| Containerization | Docker |
| Orchestration | Docker Compose |
| Endpoint | Windows 10 |
| Monitoring | Sysmon |
| Attacker Machine | Kali Linux |
| Automation | n8n |
| Scripting | Python |
| Operating System | Linux |
| Threat Mapping | MITRE ATT&CK |

---
