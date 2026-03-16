# Honeytrap: A Honeypot for Capturing and Profiling Attacks
![GitHub stars](https://img.shields.io/github/stars/Tarunjadav18/Honeytrap-A-Honeypot-for-Capturing-and-Profiling-Attacks)

![Cybersecurity](https://img.shields.io/badge/Project-Cybersecurity-blue)
![Honeypot](https://img.shields.io/badge/Tool-Honeypot-red)
![ELK Stack](https://img.shields.io/badge/Stack-ELK-green)

## Project Overview

This project implements a **honeypot-based cyber attack monitoring system** using the **Cowrie Honeypot** and the **ELK Stack (Elasticsearch, Filebeat, Kibana)**.

The system captures attacker interactions, logs malicious activity, and visualizes attack patterns through Kibana dashboards.

This helps security analysts understand attacker behavior and improve threat detection.

---

# Architecture

![Architecture](./Honeypot attack flow architecture diagram.png)

Flow of the system:

Attacker → Cowrie Honeypot → Filebeat → Elasticsearch → Kibana Dashboard

---

# Technologies Used

- Cowrie Honeypot
- Filebeat
- Elasticsearch
- Kibana
- Python
- Ubuntu Linux

---

# Features

- Real-time attack monitoring
- Logging attacker commands
- Tracking login attempts
- Visualization of attack activity
- Dashboard-based threat analysis

---

# Project Structure
Honeytrap-A-Honeypot-for-Capturing-and-Profiling-Attacks
│
├── docs/
│ ├── project_documentation.md
│ └── commands_used.md
│
├── Honeypot attack flow architecture diagram.png
├── Design Project review 2.pdf
├── README.md
├── requirements.txt
└── setup_instructions.md

---

# Setup Instructions

Detailed setup instructions are available in:
setup_instructions.md

---

# Commands Used

Commands used for configuring the honeypot and ELK stack are documented in:
docs/commands_used.md
---

# Future Improvements

- Automated attack alerting
- Machine learning based attack detection
- Multiple distributed honeypots
- Advanced threat intelligence integration

---

# Author

**Tarun S Jadav**

Cybersecurity Student  
Alliance University  
Aspiring Cloud Security Engineer
