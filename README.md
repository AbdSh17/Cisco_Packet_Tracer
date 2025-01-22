# Cisco Packet Tracer - ENCS3320 Project #2

This repository contains the network design and configurations for **Project #2** of the ENCS3320 - Computer Networks course at Birzeit University. The project focuses on creating interconnected networks using Cisco Packet Tracer, implementing subnetting, routing, and essential network services.

---

## 📑 Table of Contents

1. [What You Can Find in This Repository](#-what-you-can-find-in-this-repository)
2. [Project Objectives](#project-objectives)
3. [Autonomous Systems Overview](#autonomous-systems-overview)
    - [AS100: Faculty of Engineering and Technology Network](#as100-faculty-of-engineering-and-technology-network)
    - [AS200: Home-ISP Network](#as200-home-isp-network)
    - [AS300: Google Network](#as300-google-network)
4. [Getting Started](#Getting-Started)
5. [Contributors](#contributors)

---

## What You Can Find in This Repository
- Project PDF
- Project Report
- Full project solution (.pkt)


## Project Objectives

1. Design an IP addressing scheme using subnetting.
2. Configure and manage dynamic/static routing protocols (OSPF and BGP).
3. Implement essential network services: Web, Email, DNS, DHCP.
4. Set up wireless LAN with robust security.
5. Develop and simulate interconnectivity between three autonomous systems (AS).

---

## Autonomous Systems Overview

### AS100: Faculty of Engineering and Technology Network
This network includes the departments of Electrical and Computer Engineering (ECE) and Computer Science (CS). Key features:
- **IP Addressing**: Subnets optimized for servers, ECE, CS, and backbone connections.
- **Core Services**: Web, Email, DNS, and DHCP servers.
- **Routing**: OSPF configured for internal routing with multiple areas.

### AS200: Home-ISP Network
Represents a residential ISP network. Key features:
- **Wireless Network**: Configured with WPA2 security and AES encryption.
- **Dynamic NAT with PAT**: Translates private home addresses to public IPs.
- **Routing**: OSPF for intra-AS and BGP for inter-AS communication.

### AS300: Google Network
Serves as a simulated enterprise network with key DNS and Email services. Key features:
- **DNS Server**: Resolves domain names such as `gmail.com` and `it.birzeit.edu`.
- **Email Server**: Configured for SMTP and POP3 protocols with user accounts.
- **Routing**: OSPF for intra-AS and BGP for inter-AS communication.

---
## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/AbdSh17/Cisco_Packet_Tracer.git

## Contributors
- [Abdalraheem Shuaibi](#https://github.com/AbdSh17)
