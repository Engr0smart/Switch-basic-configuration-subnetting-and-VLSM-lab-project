# Switch-basic-configuration-subnetting-and-VLSM-lab-project
INTRODUCTION

This repository contains the configuration files and documentation for a network topology created using Cisco Packet Tracer. The topology includes subnetting, Variable Length Subnet Masking (VLSM), basic switch configuration, and basic router configuration.

OVERVIEW

The network topology consists of the following components:
  
  * Switches
  
  * Router
  
  * End devices (PCs/Laptops)
  
  * Home Router

STEPS

1. Topology Design: 
I designed the network topology using Packet Tracer, including the placement of switches, routers, and end devices.

2. Subnetting and VLSM (Variable Length Subnet Masking): 

I choose 192.168.0.0/24 address for the project. However, I segmented the network into two: LAN1 and LAN2. LAN1 is meant to have 12 hosts while LAN2 is to have 5 hosts. The most appropriate subnet for LAN1 is 255.255.255.240 which gives 16 hosts. For LAN2, 255.255.255.248 is the appropriate subnet as it gives 6 hosts.

To optimize the IP address allocation and minimize wastage of IP addresses, I implemented VLSM. The first segment (LAN1) which requires 12 host is on 192.168.0.0/28 network (which gives 14 usable hosts) while second segment is on 192.168.0.16/29 network (which gives 6usable hosts).

3. Switch Basic Configuration: 

I configured the switches with hostnames, MOTD banners, physical and remote CLI access, prevent unwanted domain lookups, VLANs, and basic security features.

4. Router Basic Configuration: 

I configured the router with hostname, MOTD banner, physical and remote CLI access, prevent unwanted domain lookup, interface IP address, and basic security features.

ADDITIONAL NOTES

This project is intended for educational purposes to demonstrate network configuration concepts using Packet Tracer.

The packet tracer (.pkt) file containing the network topology, diagrams and configuration text file are all included in this repository.

Feel free to explore and modify the topology to further enhance your understanding of networking principles.
