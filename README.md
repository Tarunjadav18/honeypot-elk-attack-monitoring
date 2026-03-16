# Honeypot ELK Attack Monitoring System

## Project Overview
This project implements a honeypot-based cyber attack monitoring system using **Cowrie Honeypot** and the **ELK Stack (Elasticsearch, Logstash/Filebeat, Kibana)**.

The system captures attacker interactions, forwards logs to Elasticsearch, and visualizes attack patterns in Kibana dashboards.

---

## Architecture

![Architecture](Honeypot attack flow architecture diagram.png)

---

## Technologies Used

- Cowrie Honeypot
- Filebeat
- Elasticsearch
- Kibana
- Python
- Linux (Ubuntu)

---

## Features

- Real-time attack monitoring
- Logging of attacker commands and login attempts
- Visualization of attack activity
- Detection of attacker IP addresses
- Dashboard-based security monitoring

---

## Project Structure
honeypot-elk-attack-monitoring
│
├── docs/
│   └── project_documentation.md
│
├── README.md
├── requirements.txt
├── setup_instructions.md
├── Honeypot attack flow architecture diagram.png

---

## Future Improvements

- Automated alerting system
- Machine learning-based attack detection
- Distributed honeypot deployment
- Advanced threat intelligence analysis
