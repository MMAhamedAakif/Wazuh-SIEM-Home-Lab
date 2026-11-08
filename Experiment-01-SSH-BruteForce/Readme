# EXPERIMENT 01: SSH BRUTE-FORCE ATTACK DETECTION USING WAZUH SIEM

**Project:** Enterprise SOC Monitoring and Threat Detection System

**Category:** Blue Team / Security Operations Center

**Experiment ID:** SOC-001

**Platform:** Wazuh SIEM

**Status:** Pending practical verification

## 1. Objective

To simulate an SSH brute-force attack against an Ubuntu Linux server and evaluate the ability of Wazuh SIEM to detect repeated authentication failures, identify suspicious source IP addresses and generate security alerts.

## 2. Lab Environment

| Component | Configuration |
|---|---|
| Attacker | Kali Linux |
| Target | Ubuntu Linux |
| SIEM | Wazuh Manager |
| Attack Tool | THC Hydra |
| Target Service | OpenSSH |
| Monitoring Source | Ubuntu authentication logs |
| Detection Framework | MITRE ATT&CK |

## 3. Tools and Technologies

- Wazuh SIEM
- Kali Linux
- Ubuntu Server
- Hydra
- OpenSSH
- Linux authentication logs
- MITRE ATT&CK

## 4. Methodology

### Phase 1 – Environment Preparation

Verified SSH service availability, network connectivity and Wazuh Manager status.

### Phase 2 – Attack Simulation

Generated eight controlled failed SSH authentication attempts from Kali Linux against the Ubuntu test server using Hydra.

A deliberately nonexistent test username was used to avoid attempting access to a real account.

### Phase 3 – Log Collection

Monitored Ubuntu authentication logs to verify that the failed SSH attempts were recorded.

### Phase 4 – Security Detection

Investigated Wazuh security alerts and evaluated SSH authentication detection rules.

### Phase 5 – Incident Investigation

Examined the source IP address, targeted username, timestamps, detection rule and severity level.

## 5. Detection Information

| Attribute | Expected finding |
|---|---|
| Rule ID | 5712 |
| Rule Description | SSH brute-force attempt using a nonexistent user |
| Severity | Level 10 |
| MITRE Technique | T1110 – Brute Force |
| Attack Source | Kali Linux IP |
| Target | Ubuntu SSH server |

## 6. Results

**Attack simulation:** [Record actual result]

**Authentication log collection:** [Successful / Unsuccessful]

**Wazuh alert generation:** [Successful / Unsuccessful]

**Detected source IP:** [Record actual IP]

**Detection rule:** [Record actual rule ID]

**Investigation outcome:** [Record findings]

## 7. Security Analysis

The experiment evaluates the effectiveness of centralized authentication monitoring and correlation-based security detection.

Repeated failed SSH authentication attempts can indicate password-guessing activity. Investigating the source address, targeted account and event timestamps helps security analysts distinguish suspicious activity from legitimate authentication errors.

## 8. Recommendations

- Enforce strong authentication policies.
- Disable unnecessary password-based SSH authentication.
- Prefer SSH key-based authentication.
- Restrict SSH access to trusted networks.
- Monitor repeated authentication failures.
- Configure controlled automated incident response.
- Regularly review authentication logs and security alerts.

## 9. Conclusion

This experiment demonstrates the practical application of Wazuh SIEM for SSH authentication monitoring and brute-force detection.

It provides hands-on experience with attack simulation, log analysis, security event correlation, alert investigation and incident documentation.

## 10. Evidence

Attach:

1. Kali Hydra execution screenshot.
2. Ubuntu authentication log screenshot.
3. Wazuh Dashboard detection screenshot.
4. Expanded alert details showing the detection rule.
5. Investigation summary and findings.

**Project Repository:** [Insert GitHub repository URL]
