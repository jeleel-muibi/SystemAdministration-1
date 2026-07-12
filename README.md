> This repository explores hybrid infrastructure and automation concepts that later informed the HybridOps platform.

# Windows Server and Network Administration with Automation

Built with: Windows Server • Active Directory • Entra ID • Intune • SCCM • Proxmox • EVE-NG

Hybrid infrastructure lab exploring Windows Server administration, hybrid identity architecture, device lifecycle automation and secure multi-site networking.

This repository demonstrates a hybrid Windows infrastructure lab combining on-premise server roles with cloud identity and modern device management services.

The environment explores enterprise administration patterns including hybrid identity, automated device provisioning, infrastructure governance, and secure network architecture.

---

## Video Demonstration

> :arrow_forward: **Watch the video on YouTube**

[<img src="https://img.youtube.com/vi/2B4VF5nqhFs/maxresdefault.jpg" alt="Hybrid identity lab video demonstration" width="720">](https://youtu.be/2B4VF5nqhFs?t=2)

Video link: [https://youtu.be/2B4VF5nqhFs?t=2](https://youtu.be/2B4VF5nqhFs?t=2)

Full demonstration playlist: [Project Demonstration Playlist](https://www.youtube.com/playlist?list=PLe-oTj2F_EnfoljrqXfTc3GbT5vtHFdWq)

---

## Architecture Overview

The lab environment integrates on-premise infrastructure with cloud management tools.

Key components include:

• Windows Server infrastructure with Active Directory  
• Hybrid identity using Microsoft Entra ID  
• Device lifecycle automation using Microsoft Intune and Windows Autopilot  
• Configuration management using System Center Configuration Manager (SCCM)  
• Multi-vendor networking with Cisco, Arista, and pfSense  

---

## Core Capabilities

### On-Premise Infrastructure

• Active Directory user and group management  
• Group Policy configuration and security enforcement  
• Server roles including DHCP, DNS, IIS, file services and print services  
• Failover clustering and load balancing for high availability  

---

### Device Lifecycle Management

• Automated device provisioning using Windows Autopilot  
• Centralised device management using Microsoft Intune  
• Application deployment and compliance enforcement  

---

### Identity and Access Management

• Hybrid identity architecture using Active Directory and Entra ID  
• Single Sign-On (SSO) integration  
• Role-based access control (RBAC)

---

### Networking and Security

• Multi-vendor switching using Cisco and Arista  
• Layer 2 and Layer 3 routing architectures  
• VLAN segmentation and DMZ design  
• Site-to-site connectivity using IPsec tunnels  
• Remote access using OpenVPN  

---

## Lab Environment

The infrastructure is deployed in a virtualised lab environment:

• Network simulations using **EVE-NG**  
• Infrastructure virtualised on **Proxmox**  
• Multi-site architecture with simulated failover scenarios  

---

## Automation and Monitoring

Automation and operational visibility include:

• PowerShell scripting for administrative automation  
• Configuration automation using Ansible  
• Monitoring using Zabbix  
• Network analysis using Wireshark  

---

## Related Platform

These concepts later informed the design philosophy behind the HybridOps platform.

HybridOps Platform Overview  
[HybridOps platform overview](https://hybridops.tech/why)
