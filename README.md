![GNS3 Project](GNS3.jpg)

# Networking Labs
This repository contains a series of hands-on networking laboratories designed to provide practical experience with various networking concepts, protocols, and technologies using GNS3 (Graphical Network Simulator-3).

## Overview
These labs cover fundamental to advanced networking topics, providing hands-on experience with:
- Network simulation using GNS3
- Routing protocols (static and dynamic)
- Network addressing and subnetting
- Network services (DHCP)
- Network security (VLANs, Firewalls)
- Advanced networking concepts (NAT, GRE, IPv6)
- Software-Defined Networking

## Prerequisites
- GNS3 installed and configured on your system
- Basic understanding of networking concepts
- RouterOS knowledge (will be developed throughout the labs)

## Lab Structure
| Lab | Topic | Description |
|-----|-------|-------------|
| 1 | [GNS3 Setup](Lab01-GNS3%20Setup) | Install and configure GNS3 on your computer and setup your first network topology |
| 2 | [Intro to Router OS](Lab02-Intro%20to%20Router%20OS) | Use RouterOS to route between two subnets |
| 3 | [Static Routing](Lab03-Static%20Routing) | Create static routes to inform the router about the location of subnets that are not directly attached |
| 4 | [Dynamic Routing](Lab04-Dynamic%20Routing) | Use dynamic routing protocols to allow the router to automatically learn the location of distant subnets |
| 5 | [Custom Subnets](Lab05-Custom%20Subnets) | Create your own network subnets given some design constraints |
| 6 | [DHCP](Lab06-DHCP) | Enable Dynamic Host Configuration Protocol (DHCP) on subnets to simplify client network configuration |
| 7 | [VLANs](Lab07-VLANs) | Configure VLANs on the switches and router to provide for network isolation between sets of hosts on the same physical network |
| 8 | [Firewalls](Lab08-Firewalls) | Configure a Firewall to restrict network access according to administrative requirements |
| 9 | [Network Address Translation](Lab09-NAT) | Connect your virtual GNS3 topology to the Internet and configure Network Address Translation (NAT) on a router |
| 10 | [GRE and OSPF](Lab10-GRE%20and%20OSPF) | Use a GRE tunnel and OSPF routing to connect a "remote" business office to a "headquarters" business network |
| 11 | [IPv6](Lab11-IPv6) | Configure a dual-stack network to support both IPv4 and IPv6 |
| 12 | [OpenFlow](Lab12-OpenFlow) | Configure a routed network that uses Software-Defined Networking (SDN) over OpenFlow Layer 3 switches |

## Repository Structure
Each lab is contained in its own directory with the following structure:
```
LabX-Topic/
├── README.md         # Lab instructions and requirements
├── topology/         # GNS3 topology files
├── configs/         # Configuration files and scripts
└── screenshots/     # Documentation images
```

## Getting Started
1. Clone this repository:
```bash
git clone https://github.com/majortank/Networking-Labs.git
```

2. Install GNS3 by following the instructions in Lab 1
3. Complete each lab in sequence, as concepts build upon previous labs

## Learning Objectives
By completing these labs, you will:
- Gain practical experience with network simulation tools
- Understand and implement various routing protocols
- Learn to configure and troubleshoot network services
- Develop skills in network security implementation
- Experience modern networking concepts like SDN

## Contributing
Feel free to submit issues and enhancement requests. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)

---

## Resources
- [GNS3 Documentation](https://docs.gns3.com/)
- [RouterOS Documentation](https://wiki.mikrotik.com/wiki/Manual:TOC)
- [OpenFlow Specification](https://opennetworking.org/software-defined-standards/specifications/)
