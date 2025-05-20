# Network Segmentation and Inter-VLAN Routing Project

## Project Overview
This project demonstrates network segmentation and inter-VLAN routing using Cisco Packet Tracer.
It involves creating multiple VLANs, configuring a router for inter-VLAN routing, and applying Access Control Lists (ACLs) to enforce security policies between departments.

## Network Design
### Departments/VLANs:

- VLAN 10 – Sales (192.168.10.0/24)

- VLAN 20 – IT (192.168.20.0/24)

- VLAN 30 – HR (192.168.30.0/24)

- VLAN 40 – Marketing (192.168.40.0/24)

## Key Devices:

- 1x Cisco Router (Inter-VLAN Routing)

- 5x Cisco Switches (VLAN Management)

- Multiple End Devices (3 PCs in each VLAN)

## Network Topology Image:
![Topology Image](https://github.com/user-attachments/assets/3273cee9-746b-46bd-9c18-96da17bdae8d)



## Configuration Details


### Switch Configuration:

- VLAN creation and port assignment

- Trunk link configuration between switches and router


### Router Configuration:

- Subinterfaces for each VLAN (GigabitEthernet0/0/0.10, .20, .30, .40)

- Encapsulation with dot1Q

- IP addressing for each VLAN


### Security (ACLs):

- Extended ACLs applied inbound on router subinterfaces

- Controlled access between departments (e.g., only IT can be reached by others)


## Technologies Used

- Cisco Packet Tracer

- VLANs and Trunking

- Router-on-a-Stick (Inter-VLAN Routing)

- Extended Access Control Lists (ACLs)

- Basic Networking Principles


## How to Open and Explore

- Download the .pkt file.

- Open it using Cisco Packet Tracer.

- Explore device configurations.

- Test connectivity using ping and tracert commands.

## Project Outcomes

- Gained hands-on experience with VLAN design and segmentation.

- Implemented secure inter-VLAN communication.

- Strengthened understanding of ACL application and traffic control.

- Practiced real-world troubleshooting and network documentation.

## Future Improvements

- Implement DHCP services for dynamic IP addressing.

- Introduce redundancy using EtherChannel.

- Extend ACLs for more granular permissions.

- Simulate external connectivity (e.g., Internet access through NAT).

# Author:
**Sufran Olaniyi**

**Lifelong Learner | Automation Enthusiast**



