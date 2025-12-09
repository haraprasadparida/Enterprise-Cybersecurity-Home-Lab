# Enterprise Cybersecurity Home Lab
A comprehensive repository documenting the construction and configuration of an enterprise-grade cybersecurity home lab environment by integrating various procedures, configurations, and technologies to simulate real-world scenarios.

## Overview
- This repository provides a structured, step‑by‑step guide to building and configuring an **enterprise‑grade cybersecurity lab environment**.
- Follows a **5‑phase procedure** to construct and harden the lab environment gradually.

## Project Phases:
- Phase 1: Network Architecture: Implement an isolated, firewalled corporate LAN using pfSense and VMWare networking.
- Phase 2: Core Services: Deploy Windows Server 2022 and configure Active Directory (AD), DNS, and DHCP.
- Phase 3: Logging Pipeline: Deploy Splunk Enterprise (SIEM), Splunk Universal Forwarders, and Sysmon to collect high-fidelity logs from all endpoints.
- Phase 4: Defensive Development: Create and validate Splunk detection rules mapped to MITRE ATT&CK techniques.
- Phase 5: Attack Simulation: Execute realistic attack scenarios using Kali Linux and Metasploit to test the defensive capabilities.

## Software/Tools:
- **Hypervisor:** VMware Workstation Pro 17
- **Operating Systems:**
a.	Windows Server 2022
b.	Ubuntu Server 24.04.3
c.	Windows 10 Enterprise
d.	Ubuntu Desktop 24.04
e.	Kali Linux
f.	pfSense
- **Components:** Active Directory, Sysmon, Splunk Universal Forwarder
- **Analysis Tools:**
a.	Splunk Enterprise: Central SIEM/Logging platform.
b.	Wireshark: Used on the Server and Attack VMs for deep packet inspection.
c.	Nmap: For reconnaissance and port scanning simulations.
d.	Suricata: IDS/IPS
e.	Metasploit: Framework for attack simulation

## Repository Contents
- **Documentation** - Detailed guides for each phase in separate documents.
- **Procedures** - Step-by-step instructions for replicating the lab setup.

## Learn More
For detailed instructions and resources, please explore the project files in this repository. Each phase includes comprehensive notes to help you replicate and customize the lab environment.
