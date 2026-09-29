# AI-Driven-Secure-Enterprise-Infrastructure-and-Monitoring

## Overview
This project aims to build a complete, functioning enterprise security environment to address the limitations of traditional, isolated monitoring systems. The project integrates network infrastructure and identity management with active monitoring and deception systems, culminating in an advanced AI-driven detection layer designed to identify anomalous behavior and complex attacks that evade static, signature-based rules.

## Key Features
* **Robust Infrastructure & Centralized Access:** A scalable simulated enterprise network using PNETLab, featuring Firewall policies and centralized access control via Active Directory Domain Services.
* **Centralized Security Monitoring (SIEM):** Aggregation and correlation of logs from servers, endpoints, and firewalls using the Wazuh SIEM platform.
* **Threat Deception (Honeypot):** Deployment of a Honeypot within the network topology to attract, isolate, and log unauthorized malicious activity, gathering early, high-fidelity threat intelligence.
* **AI-Driven Threat Detection:** Development and training of Machine Learning classification models (such as Random Forest or XGBoost) optimized for detecting structural network threats like Brute Force and DoS attacks.
* **Interactive Real-Time Dashboard:** An interactive security dashboard built with the Python Streamlit framework, integrated with the live Wazuh API for real-time attack logging and threat visualization.

## Technologies & Tools
* **Network Simulation:** PNETLab.
* **Identity & Access Management:** Windows Server, Active Directory Domain Services, Group Policy.
* **Cybersecurity & Perimeter Defense:** Wazuh SIEM, Firewall, Honeypot.
* **Attack Simulation:** Kali Linux (Brute Force, DoS).
* **AI & Machine Learning:** Python, scikit-learn, XGBoost, Random Forest Classifier.
* **Datasets:** CSE-CIC-IDS2018, BETH.
* **Visualization:** Streamlit.

## Project Team
This system was developed as a graduation project at the Faculty of Computers and Information Technology, EELU (Fayoum Center) for the 2026-2027 academic year, under the supervision of Dr. Safi Ibrahim and Eng. Rabee Ayman.

**Team Members:**
* Mohamed Karem Ali Salama (Team Leader)
* Youssef Ayed Youssef Ashyry
* Mohamed Ahmed Mohamed Abdullah
* Mohamed Ahmed Mahmoud Elsayed
* Mahmoud Elkhateeb Gomaa
* Ahmed sherif mohamed
* Shaza Mohamed Abdeltawab
* Shahd Hamada Ebrahim
* Kareem Mohammed abouzaid

The 9-member team is organized into three specialized sub-teams to ensure seamless system integration:
* **Infrastructure & Network Engineering:** Responsible for network topology design, Windows Server deployment, and Firewall interface segregation and policies.
* **Cybersecurity & SOC Operations:** Responsible for Wazuh SIEM administration, Honeypot deployment, log engineering, and localized attack simulation using Kali Linux.
* **Artificial Intelligence & Data:** Responsible for dataset preprocessing, ML model pipeline engineering, live SIEM API log retrieval, and building the Streamlit dashboard.
