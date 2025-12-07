# 🔐 Security-in-SDN-Project
This project aims to simulate, analyze, and secure a Software Defined Networking (SDN) environment by identifying potential vulnerabilities and implementing attack detection mechanisms.

---
## 📁 Project Structure
```text
Security-in-SDN-Project/
├── scripts/
│   ├── attack_simulation.py            # Simulate attacks in Mininet
│   ├── anomaly_detection.py            # Detect anomalies from the CSV
│   └── traffic.csv                     # Network traffic data (normal + attack)
├── configs/
│   ├── mininet_topology.py             # Define the SDN network topology
│   └── openflow_config.yaml            # OpenFlow configuration (simulation)
└── README.md
```
## 🎯 Project Objectives
-Create a custom SDN topology in Mininet.
-Simulate network attacks (e.g., flow injection, flooding attacks).
-Collect traffic flows and extract features.
-Detect abnormal behaviors using anomaly detection.

## ⚙️ Tools & Technologies
-Mininet: SDN network topology simulation.
-Python: Scripts for simulation and detection.
-OpenFlow: Communication protocol in SDN.
-CSV: For storing and analyzing network traffic data.
