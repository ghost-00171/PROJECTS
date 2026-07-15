
# Enterprise ISP Network Project

## Overview

This project demonstrates the design and implementation of an Enterprise ISP Network using GNS3. The objective was to simulate a real-world enterprise network that provides secure connectivity between multiple branch networks while implementing routing, firewall protection, and network services.

The project follows a hierarchical network design and includes ISP routers, enterprise routers, internal networks, security devices, and servers.

---

## Objectives

- Design a scalable enterprise network.
- Simulate ISP connectivity.
- Configure dynamic and external routing.
- Implement firewall protection.
- Deploy network services.
- Verify end-to-end communication.
- Improve network security and availability.

---

## Network Topology

The network consists of:

- ISP Routers (R1 & R2)
- Enterprise Routers (R3, R4, R5 & R6)
- Core Network
- Internal LAN
- pfSense Firewall
- Ubuntu Server
- Client PCs
- Internet Cloud

---

## Technologies Used

- GNS3
- Cisco IOS Routers
- Ethernet Switches
- pfSense Firewall
- Ubuntu Server
- VMware Workstation

---

## Protocols Implemented

### OSPF

Configured OSPF for dynamic routing inside the enterprise network to automatically exchange routing information between routers.

### eBGP

Configured External BGP between ISP and enterprise routers to simulate communication between different Autonomous Systems.

---

## Network Services

The Ubuntu Server provides:

- Apache Web Server
- FTP Server
- DNS Services
- Syslog Server

These services were successfully tested from different network segments.

---

## Security Features

- pfSense Firewall
- Access Control Lists (ACLs)
- NAT Configuration
- Traffic Filtering
- Basic Network Segmentation

---

## IP Addressing

The project uses multiple private IP address ranges for different networks.

Examples include:

- 10.0.0.0/30
- 192.168.x.x
- Loopback Interfaces

Each subnet was designed for efficient routing and communication.

---

## Testing Performed

The following tests were completed successfully:

- Router-to-router connectivity
- End-to-end Ping
- OSPF neighbor verification
- BGP neighbor verification
- Server accessibility
- HTTP testing
- FTP connectivity
- Firewall rule verification
- Routing table verification

---

## Skills Learned

- Enterprise Network Design
- ISP Network Architecture
- OSPF Configuration
- eBGP Configuration
- IP Addressing and Subnetting
- pfSense Firewall Configuration
- Ubuntu Server Deployment
- Network Troubleshooting
- ACL Configuration
- Static and Dynamic Routing

---

## Challenges Faced

- Configuring communication between multiple routing domains.
- Troubleshooting routing and connectivity issues.
- Configuring pfSense interfaces and firewall rules.
- Ensuring successful communication between all network segments.
- Testing services across different subnets.

---

## Project Outcome

The project successfully simulated a small enterprise ISP environment where multiple routers, firewall, and servers communicate securely using dynamic routing protocols. The implementation improved my understanding of enterprise networking, routing protocols, firewall configuration, and real-world network troubleshooting.

---

## Future Improvements

- VLAN Implementation
- OpenVPN Remote Access
- DMZ Network
- IDS/IPS Integration (Snort/Suricata)
- High Availability
- Backup Router Configuration
- Network Monitoring (Zabbix/Nagios)
- IPv6 Support

---

## Tools Used

- GNS3
- Cisco IOS
- pfSense
- Ubuntu Server
- VMware Workstation
- Wireshark

---

## Author

**Ali Haider**

Cyber Security Student | AIR University

Network Security Intern
