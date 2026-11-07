# 🛡️ SIEM-Based Security Monitoring Home Lab

A personal cybersecurity project focused on deploying and configuring **Wazuh SIEM** to monitor endpoints, collect security logs, detect suspicious activities, and investigate potential security incidents.

## 📌 Project Overview

This project demonstrates the implementation of a virtualized Security Information and Event Management (SIEM) environment using Wazuh. Windows and Kali Linux endpoints are integrated with an Ubuntu Server-based Wazuh environment to provide centralized security monitoring and log analysis.
<img width="1738" height="977" alt="dhash board 01" src="https://github.com/user-attachments/assets/71249300-7eca-418c-820a-e675469193b6" />

## 🏗️ Lab Architecture

**Environment:**
- Ubuntu Server – Wazuh SIEM Server
- Windows – Monitored Endpoint
- Kali Linux – Monitored Endpoint / Security Testing
- Oracle VirtualBox – Virtualization Platform

## 🛠️ Technologies & Tools

| Technology | Purpose |
|---|---|
| Wazuh SIEM | Security monitoring and log analysis |
| Ubuntu Server | SIEM server deployment |
| Kali Linux | Security testing and endpoint monitoring |
| Windows | Endpoint monitoring |
| SSH | Authentication monitoring |
| Oracle VirtualBox | Virtual lab environment |

## ⚙️ Implementation

### 1. Wazuh SIEM Deployment
- Deployed and configured the Wazuh SIEM server.
- Accessed the Wazuh dashboard for centralized security monitoring.

### 2. Endpoint Integration
- Integrated Windows and Kali Linux endpoints.
- Configured Wazuh agents to forward endpoint security events to the server.

### 3. SSH Authentication Monitoring
- Configured SSH authentication.
- Generated failed login attempts to simulate suspicious access activities.
- Monitored authentication-related security events.

### 4. Security Monitoring & Analysis
- Investigated security alerts through the Wazuh dashboard.
- Analyzed endpoint logs and authentication events.
- Practiced identifying suspicious activities using SIEM monitoring techniques.

## 📸 Screenshots

Add your actual lab screenshots here.

Suggested screenshots:
- Wazuh Dashboard
- Connected Wazuh Agents
- Windows Endpoint Monitoring
- Kali Linux Endpoint Monitoring
- SSH Failed Login Alerts
- Security Events and Alert Analysis

  <img width="1738" height="975" alt="dash 02 " src="https://github.com/user-attachments/assets/c22da3aa-8944-4111-aebf-1f50dc8cc985" />




## 🎯 Learning Outcomes

- Understanding SIEM architecture and deployment.
- Hands-on experience with centralized log management.
- Endpoint monitoring using Wazuh agents.
- Investigating SSH authentication failures.
- Identifying and analyzing suspicious security events.
- Building and managing virtualized cybersecurity environments.

## 🚀 Future Improvements

- Integrate additional endpoints.
- Configure custom Wazuh detection rules.
- Simulate brute-force authentication attacks in an authorized lab.
- Implement file integrity monitoring (FIM).
- Explore vulnerability detection and threat hunting.

## 👨‍💻 Author

**Ahamed Aakif**

Cybersecurity | Network Security | SIEM | Linux

---

*This project was developed for educational purposes in a controlled virtual lab environment.*
