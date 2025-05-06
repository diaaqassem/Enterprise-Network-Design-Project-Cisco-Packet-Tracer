# Enterprise-Network-Design-Project-Cisco-Packet-Tracer
As part of an in-depth networking training program, I designed and implemented a full enterprise network using Cisco Packet Tracer. This project reflects my understanding of real-world networking environments and configurations



VTP (VLAN Trunking Protocol) enabled (Domain: ITI, Password: 1234)

Enabled Spanning Tree Protocol (PVST) with:

SW2 as root bridge for VLAN 20

SW3 as root bridge for VLAN 40

DHCP setup on R1 to dynamically assign IPs to multiple subnets

🛡️ Security – ACLs:

Extended ACL to block VLAN 20 from accessing the Web Server

Blocked a specific host (host1) from using HTTP and ICMP

🌍 PAT (Port Address Translation):

Configured on R4 to provide Internet access using a single public IP

🖥️ Remote Management:

Enabled remote management on SW5 via Telnet/SSH
