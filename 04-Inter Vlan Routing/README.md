# Inter-VLAN Routing and DHCP Lab

## Overview
This lab demonstrates VLAN segmentation and Inter-VLAN Routing using the Router-on-a-Stick method in Cisco Packet Tracer.

## Topology
- 1 Cisco Router
- 1 Cisco 2960 Switch
- 4 PCs

## VLAN Configuration

| VLAN | Name | Network | Default Gateway |
|----|----|-----------------|--------------|
| 10 | HR | 192.168.10.0/24 | 192.168.10.1 |
| 20 | IT | 192.168.20.0/24 | 192.168.20.1 |

## Configuration
- VLAN Creation and Port Assignment
- 802.1Q Trunking
- Router Subinterfaces
- Inter-VLAN Routing
- DHCP Pools for Both VLANs
- Default Gateway and DNS Configuration

## Verification
- `show vlan brief`
- `show interfaces trunk`
- `show ip interface brief`
- `show ip dhcp binding`
- Ping Tests Between VLANs

## Expected Results
- PCs receive IP addresses automatically through DHCP.
- Devices within the same VLAN can communicate.
- Devices in different VLANs can communicate through the router.

## Tools
- Cisco Packet Tracer

## Learning Objectives
Understand VLAN segmentation, trunking, Router-on-a-Stick configuration, DHCP, and connectivity troubleshooting.
