# Learn-SecByte-CTF-Labs-Collection-OSINT-Reconnaissance-Nmap-Network-Traffic-Inspection
A curated collection of hands-on cybersecurity CTF labs covering OSINT, Passive/Active Reconnaissance, Nmap Deep Dive, Subdomain Mapping, Web Content Discovery, Wireshark Packet Inspection, Vulnerability Assessment, and Security Scripting from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on Open Source Intelligence (OSINT), passive and active network reconnaissance, Nmap scanning, DNS mapping, web surface discovery, Wireshark packet inspection, vulnerability assessment, and offensive security scripting labs designed for cybersecurity students, CTF players, penetration testers, threat intelligence analysts, and SOC engineers.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Before executing any offensive security assessment or threat hunt, mastering intelligence gathering, network discovery, traffic inspection, and custom automation is critical. Hosted on [Learn SecByte](https://learn.secbyte.org/), this foundational collection of CTF challenge labs provides essential training across the initial phases of the cyber attack lifecycle.

From conducting Open Source Intelligence (OSINT) and passive footprinting to executing advanced Nmap network scans, mapping DNS subdomains, discovering hidden web content, capturing and analyzing raw network packets in Wireshark, setting up virtualized offensive workstations, and automating repetitive tasks with Bash, PowerShell, and Python, these exercises establish core operational readiness.

---

## Lab Collection & Index

Below is the complete, searchable index of all OSINT, reconnaissance, network scanning, packet analysis, and security scripting challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Identity Under Pressure: Authentication, Authorization & Access Control** | Authentication & Web Recon | Broken access control (BBA), session management, privilege escalation, auth bypass | [Access Lab](https://learn.secbyte.org/ctf/identity-under-pressure-authentication-authorization-access-) |
| 2 | **Web Application Reconnaissance: Content Discovery Lab** | Authentication & Web Recon | Content discovery (`ffuf`, `gobuster`, `dirsearch`), hidden directory brute-forcing, file extension fuzzing | [Access Lab](https://learn.secbyte.org/ctf/web-application-reconnaissance-content-discovery-lab) |
| 3 | **HTTP & HTTPS: Modern Web Technologies for Hackers** | Authentication & Web Recon | HTTP request/response headers, status codes, cookies, CORS, TLS/SSL handshake analysis | [Access Lab](https://learn.secbyte.org/ctf/http-https-modern-web-technologies-for-hackers) |
| 4 | **Nmap Deep Dive: Advanced Network Discovery & Enumeration** | Active Recon & Scanning | Timing templates, NSE (Nmap Scripting Engine) scripts, service/version detection, OS fingerprinting | [Access Lab](https://learn.secbyte.org/ctf/nmap-deep-dive-advanced-network-discovery-enumeration) |
| 5 | **Vulnerability Assessment: Scanning & Validation Lab** | Vulnerability Assessment & Traffic | Automated scanners (Nessus, OpenVAS, Nuclei), false positive validation, CVSS scoring | [Access Lab](https://learn.secbyte.org/ctf/vulnerability-assessment-scanning-validation-lab) |
| 6 | **DNS Enumeration & Subdomain Discovery: Attack Surface Mapping** | Passive & Active Recon | Zone transfers (`axfr`), DNS brute-forcing (`dnsrecon`, `amass`), passive DNS, certificate transparency | [Access Lab](https://learn.secbyte.org/ctf/dns-enumeration-subdomain-discovery-attack-surface-mapping) |
| 7 | **Active Reconnaissance: Host Discovery & Service Enumeration** | Active Recon & Scanning | Ping sweeps, SYN/ACK port scanning, banner grabbing, service identification | [Access Lab](https://learn.secbyte.org/ctf/active-reconnaissance-host-discovery-service-enumeration) |
| 8 | **Passive Reconnaissance: Intelligence Gathering** | Passive & Active Recon | Shodan, Censys, Google Dorking, WHOIS data parsing, public data leak searching | [Access Lab](https://learn.secbyte.org/ctf/passive-reconnaissance-intelligence-gathering) |
| 9 | **Open Source Intelligence: Attack Surface Discovery** | Passive & Active Recon | OSINT frameworks, social media intelligence (SOCMINT), domain history, metadata extraction | [Access Lab](https://learn.secbyte.org/ctf/open-source-intelligence-attack-surface-discovery) |
| 10 | **Virtualization Lab Setup: Offensive Security Workstations** | Setup & Security Scripting | Kali Linux / Parrot OS VM installation, network adapter configuration (NAT vs. Bridged), snapshotting | [Access Lab](https://learn.secbyte.org/ctf/virtualization-lab-setup-offensive-security-workstations) |
| 11 | **Bash, PowerShell & Python Scripting: Offensive Security** | Setup & Security Scripting | Socket programming, automation scripts, multi-threaded port scanners, web scrapers | [Access Lab](https://learn.secbyte.org/ctf/bash-powershell-python-scripting-offensive-security) |
| 12 | **Packet Analysis with Wireshark: Network Traffic Inspection** | Vulnerability Assessment & Traffic | PCAP filtering syntax, stream reassembly, protocol breakdown, anomaly detection | [Access Lab](https://learn.secbyte.org/ctf/packet-analysis-with-wireshark-network-traffic-inspection) |

---

## Categories

### 1. Passive Reconnaissance & Open Source Intelligence (OSINT)
Map target organizations without touching infrastructure by leveraging search engines, public datasets, certificate logs, and OSINT frameworks.
- [Open Source Intelligence: Attack Surface Discovery](https://learn.secbyte.org/ctf/open-source-intelligence-attack-surface-discovery)
- [Passive Reconnaissance: Intelligence Gathering](https://learn.secbyte.org/ctf/passive-reconnaissance-intelligence-gathering)
- [DNS Enumeration & Subdomain Discovery: Attack Surface Mapping](https://learn.secbyte.org/ctf/dns-enumeration-subdomain-discovery-attack-surface-mapping)

### 2. Active Reconnaissance & Network Discovery
Probe active network targets, perform host discovery sweeps, execute advanced Nmap scans, and profile running network services.
- [Active Reconnaissance: Host Discovery & Service Enumeration](https://learn.secbyte.org/ctf/active-reconnaissance-host-discovery-service-enumeration)
- [Nmap Deep Dive: Advanced Network Discovery & Enumeration](https://learn.secbyte.org/ctf/nmap-deep-dive-advanced-network-discovery-enumeration)

### 3. Web Technologies, Content Discovery & Access Control
Examine HTTP/HTTPS protocol mechanics, discover hidden web directories and parameters, and audit authentication/authorization logic.
- [HTTP & HTTPS: Modern Web Technologies for Hackers](https://learn.secbyte.org/ctf/http-https-modern-web-technologies-for-hackers)
- [Web Application Reconnaissance: Content Discovery Lab](https://learn.secbyte.org/ctf/web-application-reconnaissance-content-discovery-lab)
- [Identity Under Pressure: Authentication, Authorization & Access Control](https://learn.secbyte.org/ctf/identity-under-pressure-authentication-authorization-access-)

### 4. Vulnerability Assessment, Traffic Inspection & Security Scripting
Analyze network packet captures in Wireshark, perform vulnerability scanning, setup offensive workstations, and build custom automation scripts.
- [Packet Analysis with Wireshark: Network Traffic Inspection](https://learn.secbyte.org/ctf/packet-analysis-with-wireshark-network-traffic-inspection)
- [Vulnerability Assessment: Scanning & Validation Lab](https://learn.secbyte.org/ctf/vulnerability-assessment-scanning-validation-lab)
- [Virtualization Lab Setup: Offensive Security Workstations](https://learn.secbyte.org/ctf/virtualization-lab-setup-offensive-security-workstations)
- [Bash, PowerShell & Python Scripting: Offensive Security](https://learn.secbyte.org/ctf/bash-powershell-python-scripting-offensive-security)

---

## Learning Path

Follow this structured progression path to build foundational expertise in network reconnaissance, threat intelligence, and traffic analysis:

1. **Phase 1: Environment Setup & Scripting Foundations** — Configure security VMs and build custom reconnaissance tooling:
   - [Virtualization Lab Setup: Offensive Security Workstations](https://learn.secbyte.org/ctf/virtualization-lab-setup-offensive-security-workstations)
   - [Bash, PowerShell & Python Scripting: Offensive Security](https://learn.secbyte.org/ctf/bash-powershell-python-scripting-offensive-security)

2. **Phase 2: OSINT & Passive Footprinting** — Gather intelligence without sending direct traffic to the target:
   - [Open Source Intelligence: Attack Surface Discovery](https://learn.secbyte.org/ctf/open-source-intelligence-attack-surface-discovery)
   - [Passive Reconnaissance: Intelligence Gathering](https://learn.secbyte.org/ctf/passive-reconnaissance-intelligence-gathering)
   - [DNS Enumeration & Subdomain Discovery: Attack Surface Mapping](https://learn.secbyte.org/ctf/dns-enumeration-subdomain-discovery-attack-surface-mapping)

3. **Phase 3: Active Network & Web Surface Reconnaissance** — Scan live hosts, profile open services, and discover web endpoints:
   - [Active Reconnaissance: Host Discovery & Service Enumeration](https://learn.secbyte.org/ctf/active-reconnaissance-host-discovery-service-enumeration)
   - [Nmap Deep Dive: Advanced Network Discovery & Enumeration](https://learn.secbyte.org/ctf/nmap-deep-dive-advanced-network-discovery-enumeration)
   - [HTTP & HTTPS: Modern Web Technologies for Hackers](https://learn.secbyte.org/ctf/http-https-modern-web-technologies-for-hackers)
   - [Web Application Reconnaissance: Content Discovery Lab](https://learn.secbyte.org/ctf/web-application-reconnaissance-content-discovery-lab)
   - [Identity Under Pressure: Authentication, Authorization & Access Control](https://learn.secbyte.org/ctf/identity-under-pressure-authentication-authorization-access-)

4. **Phase 4: Vulnerability Validation & Packet Forensics** — Inspect raw network traffic and validate vulnerability scan findings:
   - [Packet Analysis with Wireshark: Network Traffic Inspection](https://learn.secbyte.org/ctf/packet-analysis-with-wireshark-network-traffic-inspection)
   - [Vulnerability Assessment: Scanning & Validation Lab](https://learn.secbyte.org/ctf/vulnerability-assessment-scanning-validation-lab)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario requirements and target domain directives on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy reconnaissance and inspection toolsets (Nmap, Wireshark, Amass, ffuf, Nuclei, Maltego, Python/Bash) within your security workstation.
4. Gather OSINT intelligence, scan network endpoints, filter packet captures, validate vulnerabilities, and retrieve target flags.

---

## Disclaimer

This repository and its linked resources are strictly intended for educational, threat research, and authorized technical training purposes. Never execute network scans, OSINT queries against private individuals, or web content discovery tools against unauthorized infrastructure or production systems.
