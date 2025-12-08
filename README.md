# Enterprise Cybersecurity Home Lab
A comprehensive repository documenting the construction and configuration of an enterprise-grade cybersecurity home lab environment by integrating various procedures, configurations, and technologies to simulate real-world scenarios.

## Overview
- This repository provides a structured, step‑by‑step guide to building and configuring an **enterprise‑grade cybersecurity lab environment**.
- Follows a **5‑phase procedure** to construct and harden the lab environment gradually.

## Project Phases:
- Phase 1: Network Architecture: Implement an isolated, firewalled corporate LAN using pfSense and VMWare networking. (Phase – 1 – Which is covered in this document)
- Phase 2: Core Services: Deploy Windows Server 2022 and configure Active Directory (AD), DNS, and DHCP.
- Phase 3: Logging Pipeline: Deploy Splunk Enterprise (SIEM), Splunk Universal Forwarders, and Sysmon to collect high-fidelity logs from all endpoints.
- Phase 4: Defensive Development: Create and validate Splunk detection rules mapped to MITRE ATT&CK techniques.
- Phase 5: Attack Simulation: Execute realistic attack scenarios using Kali Linux and Metasploit to test the defensive capabilities.

## Repository Contents
- **Documentation** - Detailed guides for each phase in separate documents.
- **Procedures** - Step-by-step instructions for replicating the lab setup.

## Learn More
For detailed instructions and resources, please explore the project files in this repository. Each phase includes comprehensive notes to help you replicate and customize the lab environment.
