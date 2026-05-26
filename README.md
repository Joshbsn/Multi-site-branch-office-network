# Multi-Site Branch Office Network Lab

## Overview
Built a simulated enterprise multi-site network in Cisco Packet Tracer connecting a headquarters office and a branch office over a routed WAN link.

This lab demonstrates VLAN segmentation, router-on-a-stick inter-VLAN routing, static routing between sites, and troubleshooting end-to-end connectivity.

## Network Design
Headquarters:
- HR VLAN 10 (192.168.10.0/24)
- IT VLAN 20 (192.168.20.0/24)

Branch Office:
- Sales VLAN 30 (192.168.30.0/24)
- Support VLAN 40 (192.168.40.0/24)

WAN Link:
- 10.0.0.0/30

## Technologies Used
- Cisco Packet Tracer
- Cisco 1941 Routers
- Cisco 2960 Switches
- VLANs
- 802.1Q trunking
- Router-on-a-Stick
- Static Routing
- IPv4 subnetting
- CLI troubleshooting

## What I Learned
- How to segment departments using VLANs
- How routers route between VLANs using subinterfaces
- How static routing enables communication between remote sites
- How WAN point-to-point addressing works using /30 networks
- How to troubleshoot routing and interface issues using Cisco IOS

## Validation
Verified successful connectivity between:
- HQ HR to Branch Sales
- HQ HR to Branch Support
- Branch Sales to HQ HR
- Branch Sales to HQ IT
