# Wazuh 5.0 Beta 5

This repository documents my practical work and experiments with **Wazuh 5.0 Beta 5** in a cybersecurity lab environment.

The purpose of this repository is to document real-world configurations, testing procedures, troubleshooting, and security monitoring activities performed within the lab.

---

## Lab Environment

The lab currently includes a Wazuh Manager and multiple Wazuh Agents running different Linux distributions.

| Component | Details |
|---|---|
| Agent 001 | Amazon Linux 2023 |
| Agent 002 | Kali GNU/Linux 2026.2 |
| Agent 003 | Ubuntu 26.04 |
| Agent 004 | Debian GNU/Linux 11 |
| Agent 005 | Ubuntu 26.04 |

---

## Documentation

### Agent Management

- [Remote Agent Upgrade](docs/remote-agent-upgrade.md)

---

## Repository Structure

```text
wazuh-5.0-beta-5/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── docs/
│   └── remote-agent-upgrade.md
│
└── screenshots/
    └── remote-agent-upgrade/
        ├── agent-005-initial-status.png
        ├── agent-005-upgraded.png
        ├── agents-after-upgrade.png
        ├── agents-before-upgrade.png
        ├── all-agents-upgraded.png
        ├── upgrade-task-created.png
        ├── wpk-download.png
        └── wpk-upgrade-directory.png
```