# 🚀 Advanced SOC Automation Lab using Wazuh, Docker, Sysmon & n8n

A complete Security Operations Center (SOC) home lab built using Docker, Wazuh SIEM, Kali Linux, Windows 10, and n8n Automation.

This project demonstrates how to detect attacks, automate incident response, and enrich alerts with Threat Intelligence services.

---

# 📌 Project Overview

This lab simulates a real SOC environment.

The environment consists of:

- Wazuh Manager
- Wazuh Dashboard
- Wazuh Indexer
- Windows 10 Endpoint
- Wazuh Agent
- Kali Linux Attacker
- Docker Compose
- n8n Automation

The goal is to monitor a Windows endpoint, simulate cyber attacks from Kali Linux, generate security alerts inside Wazuh, and automatically forward them to automation workflows.

---

# 🏗 Architecture

Kali Linux

↓

Windows 10 Endpoint

↓

Wazuh Agent

↓

Wazuh Manager (Docker)

↓

Detection Rules

↓

Webhook Integration

↓

n8n Automation

↓

Threat Intelligence

↓

Telegram Notifications

↓

Incident Report

---

# ⚙ Technologies Used

- Docker
- Docker Compose
- Wazuh SIEM 4.14
- Windows 10
- Kali Linux
- n8n
- Python
- Webhooks
- JSON
- Linux
- Bash

---

# 🔥 Features

✅ Dockerized SOC Lab

✅ Windows Endpoint Monitoring

✅ Real-time Log Collection

✅ Attack Detection

✅ Webhook Integration

✅ Security Automation

✅ Threat Intelligence Integration

✅ AI-ready Workflow

---

# 📂 Lab Topology

Kali Linux

↓

Windows 10 + Wazuh Agent

↓

Docker Host

├── Wazuh Manager

├── Wazuh Dashboard

└── Wazuh Indexer

↓

n8n Automation

---

# ⚔ Attack Simulation

The following attacks were simulated:

- ICMP Ping Sweep
- Nmap Scan
- Port Scanning
- Brute Force (Hydra)
- Windows Log Monitoring

---

# 🚨 Detection Flow

Attack

↓

Windows Event Logs

↓

Wazuh Agent

↓

Wazuh Manager

↓

Rule Matching

↓

Alert Generated

↓

Webhook

↓

n8n

↓

Notification

---

# 🤖 Automation Workflow

When Wazuh generates an alert:

1. Send Alert to Webhook

2. Trigger n8n Workflow

3. Parse Alert

4. Enrich Alert

5. Send Notification

6. Generate Incident Report

---

# 🌍 Future Integrations

- VirusTotal API

- AbuseIPDB API

- Telegram Bot

- Discord Alerts

- Email Notifications

- Slack Notifications

- AI Incident Summaries

- MITRE ATT&CK Mapping

- IOC Extraction

- SOAR Integration

---

# 📊 Screenshots

## Wazuh Dashboard

(images/dashboard.png)

## Active Agent

(images/agent.png)

## n8n Workflow

(images/n8n.png)

## Architecture

(images/architecture.png)

---

# 📁 Project Structure

SOC-Automation-Lab/

│

├── README.md

├── LICENSE

├── docker-compose.yml

├── images/

├── docs/

├── n8n/

├── scripts/

├── wazuh/

├── integrations/

└── threat-intelligence/

---

# 🛠 Installation

Clone Repository

git clone https://github.com/yourusername/SOC-Automation-Lab.git

Start Docker

docker compose up -d

Open Dashboard

https://localhost

Deploy Windows Agent

Generate Alerts

Run n8n

---

# 📈 Future Improvements

- Multi-Agent Environment

- Linux Monitoring

- Active Response

- SOAR Integration

- AI Threat Hunting

- Automated Incident Response

---

# 📖 Lessons Learned

During this project I learned:

- Docker Networking

- SIEM Deployment

- Windows Log Analysis

- Linux Administration

- Security Automation

- Webhook Integration

- Incident Detection

- Threat Intelligence

- Troubleshooting Complex Deployments

---

# 📄 License

MIT License

---

# 👨‍💻 Author

Ahmed Osama

SOC Analyst | Blue Team | Network Security

