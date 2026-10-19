# OPNsense SOC Homelab

## Project Overview

This repository documents the design, deployment, and testing of a hands-on network security lab built to develop practical skills relevant to a Security Operations Center (SOC) Tier 1 analyst role.

The project focuses on firewall administration, network segmentation, network traffic analysis, security monitoring, and incident investigation.

## Objectives

- Deploy and configure OPNsense as a network firewall.
- Understand routing, Network Address Translation (NAT), and firewall rules.
- Implement VLAN-based network segmentation.
- Analyze network traffic using Wireshark.
- Investigate security events and network logs.
- Practice systematic troubleshooting and evidence collection.
- Document technical findings and lab exercises in English.

## Hardware

| Component | Specification | Purpose |
|---|---|---|
| Firewall appliance | Intel N150, 8 GB RAM, 1 TB NVMe SSD | Firewall and routing |
| Network interfaces | 8 × Intel i226-V, 2.5 GbE | Network connectivity and segmentation |
| Managed switch | MikroTik CRS326-24G-2S+ | VLAN and switching experiments |
| Main workstation | Windows 11 desktop | Administration and analysis |
| Additional workstation | Laptop running Ubuntu | Linux and security testing |

## Project Status

**Current phase:** Initial installation

- [ ] Prepare the installation USB.
- [ ] Install OPNsense on the internal SSD.
- [ ] Verify the installed version and boot process.
- [ ] Identify the available network interfaces.
- [ ] Configure and test WAN and LAN.
- [ ] Implement VLAN-based segmentation.
- [ ] Perform traffic analysis and security monitoring exercises.

## Documentation Method

Each major lab exercise will record:

1. Objective
2. Environment and prerequisites
3. Procedure
4. Expected results
5. Observed results and evidence
6. Troubleshooting
7. Security relevance
8. Lessons learned

## Security and Scope

All testing will be performed on systems and networks I own or am explicitly authorized to assess.

Credentials, private keys, sensitive configuration exports, and other confidential information will not be published.

## Evidence

Photographs, network diagrams, sanitized command output, configuration examples, and test results will be added as the project progresses.

## Lessons Learned

This section will summarize important technical findings, troubleshooting decisions, and improvements made during the project.
