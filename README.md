# Building Real-World Style Networks
![image](https://github.com/k-mcgeary/Networking-Project/assets/129139672/a6b2869c-710c-47e9-bdf9-91f7ddefbf38)


## Introduction

In this project, I built out several network designs in Packet Tracer utilizing the following concepts:

- Router conifgurations
- VLAN creation
- DNS server configuration
- DHCP configuration
- Wired and wireless network setup
- SSH configuration
- Subnetting
- Static routing, RIPv2, and OSPF

## Campus Network
![campusNetworkImage](https://github.com/k-mcgeary/Networking-Project/assets/129139672/db52eeb2-5023-4e68-b673-3d9ed6008053)

## At a glance:
- Externally hosted cloud email server
- Main Campus: 3 building with varying departments in each building
- Smaller Campus: 2 other separated departments
- Each department has its own VLAN
- RIPv2 is used for internal network communication
- Routers configured for remote login via SSH


## Hotel Network
![hotelNetworkImage](https://github.com/k-mcgeary/Networking-Project/assets/129139672/64061b95-9566-49ac-9c00-8b64145ffcc1)

## At a glance:
- 3 floors, each with their own router and switch
- Varying departments on each floor with their own VLAN setup
- Each floor has a password protected wireless access point
- OSPF routing protocol used
- Routers configured for remote login via SSH
- Port security configured for switch connecting to IT computer

## Bank Network
![bankNetworkImage](https://github.com/k-mcgeary/Networking-Project/assets/129139672/cacf8523-20ed-4c32-b8d2-0ae0d302c29b)

## At a glance:
- OSPF routing protocol used
- Routers configured for remote login via SSH
- Routers, layer 3 switches, and layer 2 switches used
- Each department has their own wireless network
- Dedicated server room for web, DHCP, and email

## Conclusion

This project taught me a lot about how much detail goes into setting up a network from scratch. The setup isn't 100% realistic because it seemed redundant to setup up over 100 endpoints but the process of configuring Cisco routers, switches, cabling, DHCP, DNS, and many other base level items needed for a network to function has given me a great insight into building a network. While not as useful as field experience, working in Packet Tracer has given valuable hands-on experience with some widely used technologies.
