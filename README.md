Enterprise Security Network Simulation
This project is a comprehensive simulation of a multi-site enterprise network built in Cisco Packet Tracer. The primary goal was to design a secure and resilient network architecture incorporating modern security principles and networking protocols.

Project Objectives
The main objectives for this simulation were to:

Design and implement a scalable, multi-site network architecture suitable for a small enterprise.
Secure the network perimeter and internal segments using modern firewall technologies and access control policies.
Ensure high availability and network resilience through redundant protocols like HSRP.
Demonstrate a practical understanding of core networking and security concepts in a simulated environment.

Key Features
Multi-Site, Multi-VLAN Configuration: Engineered a network with multiple VLANs to segment traffic between departments.
Secure Routing and Redundancy: Implemented OSPF for dynamic routing and HSRP for high availability.
Firewall and Access Control: Configured ASA firewalls and Access Control Lists (ACLs) to filter traffic and protect critical assets.
Server Deployment: Deployed and secured essential services including DHCP, DNS, and FTP servers.
Hardening: Applied SSH hardening for secure administrative access.

Security Measures Implemented
Security was a core focus of this project. The following measures were put in place:

Perimeter Security: ASA Firewalls were configured to act as the primary barrier between the internal network and external threats. All unsolicited incoming traffic is blocked by default.
Network Segmentation: The network was engineered with multiple VLANs to logically separate departments. This ensures that a compromise in one segment does not easily spread to another.
Access Control: Access Control Lists (ACLs) were configured on routers to filter traffic between VLANs and protect critical assets.
Secure Management: SSH was enabled on all network devices for encrypted administrative access, and less secure protocols like Telnet were disabled.

Network Topology
 ![image](https://github.com/user-attachments/assets/6373172d-ba92-4236-ac39-7e9a27a1df97)


Challenges & Learning Outcomes
Challenge: One of the main challenges was designing an effective IP addressing scheme and an ACL rule set that was both secure and didn't block legitimate business traffic, requiring careful planning and testing.
Learning Outcome: This project significantly strengthened my understanding of practical network security. I gained hands-on experience in firewall policy creation, inter-VLAN routing, and troubleshooting OSPF adjacencies. It highlighted the importance of a defense-in-depth strategy where multiple security layers work together to protect the network.

Technologies Used
Cisco Packet Tracer 
OSI Model & TCP/IP Concepts 
VLANs, OSPF, HSRP, ACLs, Port Security 
Firewall Configuration 
SSH Hardening 
