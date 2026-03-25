# TRex-Inc-APT-Tactics-Detection-and-Network-Analysis-Part-b

[View Project File](https://github.com/Viney-Washington/TRex-Inc-APT-Tactics-Detection-and-Network-Analysis-Part-b/blob/main/Viney%20Washington%20_%20Part%20B_%20Simulating%20an%20Advanced%20Persistent%20Threat%20(APT)%20Attack.pdf)

## Project Overview
Analyzed Advanced Persistent Threat (APT) tactics within the BioGenX environment, focusing on command-and-control communication, persistence mechanisms, and network-based indicators of compromise using Wireshark and PCAP analysis.

## APT Tactics Identified
### Command and Control (C2)
- Identified repeated outbound connections to unfamiliar external domains  
- Observed attacker communication using HTTP and DNS protocols  
- Detected potential command-and-control channels used to send and receive data  

### Persistence Mechanisms
- Identified techniques used to maintain long-term access after initial compromise  
- Persistence methods may include scheduled tasks, registry changes, or malicious services  
- Enabled attackers to remain active across system reboots and evade detection  

## Network Traffic Analysis Findings
- Repeated DNS queries to unfamiliar external domains  
- Continuous outbound HTTP communication instead of secure HTTPS  
- Traffic patterns consistent with automated communication rather than user activity  
- Evidence of long-term communication with external systems (APT behavior)  

## Vulnerabilities Identified
- Use of unencrypted HTTP traffic allowing attackers to hide malicious activity  
- Lack of outbound traffic monitoring and filtering  
- Weak network communication controls  
- Manual verification of digital signatures leading to security gaps  

## Root Cause Analysis
- Malware entered the system due to improperly verified digital signatures  
- Reliance on manual verification increased risk of human error  
- Lack of automated validation allowed malicious software to execute  

## Security Recommendations
- Implement automated digital signature verification  
- Enforce HTTPS and encrypted communication policies  
- Deploy DNS monitoring and filtering  
- Implement SIEM, SOAR, and continuous monitoring solutions  
- Strengthen endpoint security (EDR, application control)  
- Apply least privilege and access control policies  

## Real-World Security Insight
- Demonstrated how phishing attacks can bypass human verification  
- Highlighted importance of user awareness and reporting procedures  
- Reinforced need for organization-wide cybersecurity practices  

## Tools & Technologies
Wireshark | PCAP Analysis | DNS Monitoring | Network Traffic Analysis | Threat Detection  

## Skills Demonstrated
APT Detection | Threat Analysis | Network Monitoring | Incident Investigation | Vulnerability Identification | Cybersecurity Operations
