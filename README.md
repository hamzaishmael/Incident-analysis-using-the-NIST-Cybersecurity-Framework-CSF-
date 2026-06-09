# Incident Report Analysis: ICMP Flood Denial-of-Service (DoS) Attack

## Overview

This project documents the analysis of a Denial-of-Service (DoS) attack that affected a multimedia company's internal network infrastructure. The incident was analysed using the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF), focusing on the five core functions: Identify, Protect, Detect, Respond, and Recover.

The objective of this analysis is to demonstrate incident investigation, risk assessment, and the development of security controls to strengthen organisational resilience against future attacks.

---

## Incident Summary

The organisation experienced a Denial-of-Service (DoS) attack that disrupted network operations for approximately two hours. The attack involved a large volume of Internet Control Message Protocol (ICMP) packets directed at the company's network.

Investigation revealed that an improperly configured firewall allowed malicious ICMP traffic to enter the network without adequate restrictions. The excessive traffic overwhelmed network resources, causing critical network services to become unavailable and preventing employees from accessing internal systems.

The incident response team mitigated the attack by blocking incoming ICMP traffic, temporarily disabling non-essential services, and restoring critical network operations.

---

## NIST Cybersecurity Framework Analysis

### Identify

#### Security Event

* ICMP Flood Denial-of-Service (DoS) attack

#### Root Cause

* Firewall misconfiguration
* Lack of adequate filtering for incoming ICMP traffic

#### Assets Affected

* Internal network infrastructure
* Network services
* Employee access to organisational resources
* Business operations dependent on network connectivity

#### Business Impact

* Network service disruption lasting approximately two hours
* Reduced employee productivity
* Temporary loss of access to critical network resources

---

### Protect

To reduce the likelihood of similar incidents, the following security controls were recommended:

* Implementation of ICMP rate-limiting rules
* Regular firewall configuration reviews
* Source IP verification and anti-spoofing controls
* Network segmentation for critical systems
* Periodic vulnerability assessments
* Security policy enforcement and configuration management
* Ongoing cybersecurity awareness training for IT personnel

---

### Detect

The following monitoring and detection capabilities were identified to improve threat visibility:

* Continuous network traffic monitoring
* Intrusion Detection Systems (IDS)
* Intrusion Prevention Systems (IPS)
* Firewall log analysis
* Security Information and Event Management (SIEM) solutions
* Network baseline monitoring and anomaly detection
* Regular review of security alerts and system logs

---

### Respond

#### Actions Taken

* Blocked incoming ICMP traffic
* Disabled non-critical services
* Restored critical business services
* Investigated the source and method of attack
* Implemented enhanced firewall controls

#### Future Response Strategy

* Activate incident response procedures immediately upon detection
* Isolate affected systems and network segments
* Preserve forensic evidence including logs and traffic captures
* Contain malicious activity through perimeter security controls
* Communicate incident status to relevant stakeholders
* Conduct post-incident reviews and lessons-learned exercises

---

### Recover

#### Recovery Activities

* Restore affected services based on business priority
* Verify operational status of all critical systems
* Validate network integrity before returning systems to production
* Maintain disaster recovery and business continuity plans
* Review and improve security controls following recovery

#### Recovery Resources

* Firewall configuration backups
* Network device configurations
* System and security logs
* Incident response documentation
* Business continuity procedures

---

## Security Improvements Implemented

Following the investigation, the organisation implemented several security enhancements:

* Firewall rule to limit incoming ICMP traffic
* Source IP verification to reduce IP spoofing attacks
* Network monitoring software for traffic analysis
* IDS/IPS deployment to identify and filter suspicious ICMP traffic

---

## Key Lessons Learned

* Firewall misconfigurations can create significant security vulnerabilities.
* Continuous monitoring is essential for detecting abnormal network activity.
* Layered security controls improve organisational resilience against DoS attacks.
* Incident response planning reduces downtime and business impact.
* Regular security assessments help identify weaknesses before they can be exploited.

---

## Skills Demonstrated

* Network Traffic Analysis
* Incident Response
* Security Monitoring
* Risk Assessment
* NIST Cybersecurity Framework Application
* Firewall Security Controls
* Threat Detection and Mitigation
* Cybersecurity Documentation

---

## Framework Reference

This analysis follows the principles of the NIST Cybersecurity Framework (CSF):

1. Identify
2. Protect
3. Detect
4. Respond
5. Recover


**Project Type:** Cybersecurity Incident Report Analysis
**Focus Area:** Network Security and Incident Response
