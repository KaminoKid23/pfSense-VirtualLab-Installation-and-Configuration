# pfSense Virtual Lab – Installation & Configuration

This repository contains my hands-on firewall configuration lab completed as part of my college cybersecurity coursework.  
The lab walks through the installation, setup, and basic configuration of **pfSense**, a powerful open-source firewall commonly used in enterprise and small business environments.

---

##  Lab Objective

The goal of this lab was to:

- Install pfSense in a VirtualBox environment  
- Configure WAN and LAN interfaces  
- Assign IPv4 settings and DHCP ranges  
- Establish connectivity between pfSense and Ubuntu  
- Access pfSense web configurator  
- Configure hostname, domain, NTP servers, and time zone  
- Confirm successful firewall operation

This lab demonstrates practical experience with virtualization, firewall management, and network configuration.

---

## Tools & Technologies Used

- **pfSense Firewall**
- **VirtualBox**
- **Ubuntu Desktop VM**
- **DHCP / IPv4 Configuration**
- **NAT & Bridged Network Adapters**

---

## Repository Structure

pfsense-virtual-lab/
│
├── README.md
│   → Project overview, objectives, configuration steps, and lessons learned
│
├── screenshots/
│   ├── 01-pfsense-installation.png
│   ├── 02-virtualbox-network-adapter-setup.png
│   ├── 03-lan-interface-dhcp-configuration.png
│   ├── 04-ipv4-range-configuration.png
│   ├── 05-lan-ip-subnet-configuration.png
│   ├── 06-ubuntu-access-to-pfsense.png
│   ├── 07-hostname-domain-configuration.png
│   ├── 08-ntp-timezone-configuration.png
│   └── 09-final-configuration-summary.png
│
└── troubleshooting/
    ├── bootloader-install-loop-fix.md
    └── nat-adapter-connection-issue.md

