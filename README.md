# Wazuh SOC Triage Automation

**Automated Security Alert Triage | n8n | Wazuh | Threat Intelligence | AI**

An in-progress Security Operations Center (SOC) automation project integrating Wazuh alerts with n8n workflows to streamline security alert triage, threat intelligence enrichment, AI-assisted analysis, and analyst notifications.

## Project Overview

This project demonstrates how workflow automation can reduce repetitive SOC analyst tasks and improve security alert investigation efficiency.

### Architecture

```text
Wazuh Security Alert
        |
        v
Authenticated n8n Webhook
        |
        v
Webhook Verification
        |
        v
Alert Normalization
        |
        v
Severity-Based Routing
        |
        v
Source IP Validation
        |
        v
Public IP Detection
        |
        v
AbuseIPDB Threat Intelligence
        |
        v
AI-Assisted Analysis (Ollama)
        |
        v
Recommended Response
        |
        v
Discord SOC Notification
```
## Architecture Diagram

![Wazuh SOC Triage Architecture](wazuh-soc-architecture.png)
## Current Features

- Authenticated webhook alert ingestion
- JavaScript-based alert normalization
- Severity-based alert routing
- Source IP extraction and validation
- Public IP detection and routing

## Planned Features

- AbuseIPDB reputation enrichment
- AI-assisted alert analysis using Ollama
- Security investigation summaries
- Recommended incident response actions
- Discord SOC notifications
- End-to-end workflow validation

## Technology Stack

| Technology | Purpose |
|---|---|
| Wazuh | Security monitoring and alert generation |
| n8n | Workflow automation |
| JavaScript | Alert processing and normalization |
| AbuseIPDB | IP reputation intelligence |
| Ollama | AI-assisted security analysis |
| Discord | SOC notifications |

## Security Considerations

- Webhook authentication
- API credential protection
- Input validation
- Safe handling of security alerts
- No automatic destructive response actions

## Project Status

**Status: In Progress — Proof of Concept**

This project is actively being developed and tested.

## Author

Jayant Biswas

Cybersecurity | Cloud Security | SOC Automation | AI Security

# soc-triage-automation
Wazuh SOC alert triage automation using n8n, threat intelligence and AI
