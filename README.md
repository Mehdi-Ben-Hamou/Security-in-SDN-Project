# 🔐 Security-in-SDN-Project

Ce projet vise à simuler, analyser et sécuriser un réseau SDN (Software Defined Networking) en identifiant les vulnérabilités potentielles et en mettant en œuvre des mécanismes de détection d'attaques.

## 📁 Structure du projet
```text
Security-in-SDN-Project/
├── scripts/
│   ├── attack_simulation.py            # Simulation d’attaques dans Mininet
│   ├── anomaly_detection.py            # Détection d’anomalies à partir du CSV
│   └── traffic.csv                     # Données de trafic (normal + attaque)
├── configs/
│   ├── mininet_topology.py             # Définition de la topologie réseau SDN
│   └── openflow_config.yaml            # Configuration OpenFlow (simulation)
└── README.md
```

## 🎯 Objectifs du projet

- Créer une topologie SDN personnalisée dans Mininet.
- Simuler des attaques réseau (ex. : injection de flux, attaques par inondation).
- Collecter les flux de trafic et extraire les caractéristiques.
- Détecter les comportements anormaux à l’aide de la détection d’anomalies.

## ⚙️ Outils et technologies

- **Mininet** : Simulation de topologies réseau SDN.
- **Python** : Scripts de simulation et détection.
- **OpenFlow** : Protocole de communication dans SDN.
- **CSV** : Pour les données de trafic réseau.
