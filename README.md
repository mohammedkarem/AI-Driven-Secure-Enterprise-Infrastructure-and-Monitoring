# AI-Driven-Secure-Enterprise-Infrastructure-and-Monitoring

## Overview
This project aims to build a complete, functioning enterprise security environment to address the limitations of traditional, isolated monitoring systems[cite: 1]. The project integrates network infrastructure and identity management with active monitoring and deception systems, culminating in an advanced AI-driven detection layer designed to identify anomalous behavior and complex attacks that evade static, signature-based rules[cite: 1].

## Key Features
* **Robust Infrastructure & Centralized Access:** A scalable simulated enterprise network using GNS3 or PNETLab, featuring Firewall policies and centralized access control via Active Directory Domain Services[cite: 1].
* **Centralized Security Monitoring (SIEM):** Aggregation and correlation of logs from servers, endpoints, and firewalls using the Wazuh SIEM platform[cite: 1].
* **Threat Deception (Honeypot):** Deployment of a Honeypot within the network topology to attract, isolate, and log unauthorized malicious activity, gathering early, high-fidelity threat intelligence[cite: 1].
* **AI-Driven Threat Detection:** Development and training of Machine Learning classification models (such as Random Forest or XGBoost) optimized for detecting structural network threats like Brute Force and DoS attacks[cite: 1].
* **Interactive Real-Time Dashboard:** An interactive security dashboard built with the Python Streamlit framework, integrated with the live Wazuh API for real-time attack logging and threat visualization[cite: 1].

## Technologies & Tools
* **Network Simulation:** GNS3, PNETLab[cite: 1].
* **Identity & Access Management:** Windows Server, Active Directory Domain Services, Group Policy[cite: 1].
* **Cybersecurity & Perimeter Defense:** Wazuh SIEM, Firewall, Honeypot[cite: 1].
* **Attack Simulation:** Kali Linux (Brute Force, DoS)[cite: 1].
* **AI & Machine Learning:** Python, scikit-learn, XGBoost, Random Forest Classifier[cite: 1].
* **Datasets:** CSE-CIC-IDS2018, BETH[cite: 1].
* **Visualization:** Streamlit[cite: 1].

## Project Team
This system was developed as a graduation project at the Faculty of Computers and Information Technology, EELU (Fayoum Center) for the 2026-2027 academic year, under the supervision of Dr. Safi Ibrahim and Eng. Rabee Ayman[cite: 1].

**Team Members:**
* Mohamed Karem Ali Salama (Team Leader)[cite: 1]
* Youssef Ayed Youssef Ashyry[cite: 1]
* Mohamed Ahmed Mohamed Abdullah[cite: 1]
* Mohamed Ahmed Mahmoud Elsayed[cite: 1]
* Mahmoud Elkhateeb Gomaa[cite: 1]
* Ahmed sherif mohamed[cite: 1]
* Shaza Mohamed Abdeltawab[cite: 1]
* Shahd Hamada Ebrahim[cite: 1]
* Kareem Mohammed abouzaid[cite: 1]

The 9-member team is organized into three specialized sub-teams to ensure seamless system integration[cite: 1]:
* **Infrastructure & Network Engineering:** Responsible for network topology design, Windows Server deployment, and Firewall interface segregation and policies[cite: 1].
* **Cybersecurity & SOC Operations:** Responsible for Wazuh SIEM administration, Honeypot deployment, log engineering, and localized attack simulation using Kali Linux[cite: 1].
* **Artificial Intelligence & Data:** Responsible for dataset preprocessing, ML model pipeline engineering, live SIEM API log retrieval, and building the Streamlit dashboard[cite: 1].
