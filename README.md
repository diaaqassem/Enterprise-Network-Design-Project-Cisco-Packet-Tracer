# Enterprise-Network-Design-Project-Cisco-Packet-Tracer
As part of an in-depth networking training program, I designed and implemented a full enterprise network using Cisco Packet Tracer. This project reflects my understanding of real-world networking environments and configurations


#  Enterprise Network Design Project – Cisco Packet Tracer

This project demonstrates the design and configuration of a multi-subnet enterprise network using **Cisco Packet Tracer**, as part of a practical networking training program.

##  Project Overview

The network is based on the `172.16.0.0/24` address range, and includes the following:

- Multiple subnets 
- VTP domain configuration with password
- VLAN segmentation with PVST for loop prevention
- DHCP setup to assign IP addresses dynamically
- ACLs to restrict specific network access
- NAT/PAT configuration for Internet access
- SSH/Telnet setup for remote switch management

---

##  Technologies & Concepts Used

### 1. **Network Fundamentals**
- OSI & TCP/IP Models
- LAN/WAN design and device roles

### 2. **IP Addressing & Subnetting**
- IPv4 / VLSM / CIDR
- Subnet planning and address allocation

### 3. **Network Access**
- VLANs, Trunking, STP (PVST)
- Port Security, EtherChannel

### 4. **IP Connectivity**
- Static & Dynamic Routing (RIP, OSPF, EIGRP)

### 5. **IP Services**
- DHCP, NAT, DNS

### 6. **Security Fundamentals**
- Access Control Lists (ACLs)
- DHCP Snooping, Dynamic ARP Inspection
- Switch Port Security

### 7. **Network Services**
- FTP, TFTP, DNS, Syslog, NTP, HTTP/HTTPS

### 8. **Troubleshooting**
- Ping, Traceroute, Debug tools
- Structured troubleshooting methodologies

---

## 🛠️ Project Details

- **VTP Domain:** `ITI`  
- **VTP Password:** `1234`  
- **Spanning Tree Protocol (PVST):**
  - SW2: Root bridge for VLAN 20
  - SW3: Root bridge for VLAN 40
- **DHCP:** Configured on R1 for all subnets
- **ACLs:**
  - Block VLAN 20 from accessing the web server
  - Prevent Host1 from accessing web and ICMP
- **PAT:** Implemented on R4 for internet access
- **Remote Access:** Enabled on SW5 via SSH/Telnet

---

##  Network Topology
![image](https://github.com/user-attachments/assets/81d7c0cd-2534-46bf-84f1-99bb07400489)


---



