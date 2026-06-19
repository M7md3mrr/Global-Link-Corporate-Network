# Global-Link Corporate Network

## Project Overview

This project simulates a real-world enterprise network connecting a Corporate Headquarters (HQ) with three regional branches through a four-router ISP transit core.

The network was designed and implemented using Cisco Packet Tracer.

---

## Network Features

- Dynamic Routing using RIPv2
- VLSM Addressing
- Centralized DHCP Server
- DHCP Relay (ip helper-address)
- Multi-site Connectivity
- ISP Transit Backbone
- End-to-End Reachability
- Link Failure Adaptation

---

## Network Topology

![Topology](Documentation/Network-Topology.png)

---

## Components

### Headquarters (HQ)

- HQ Router
- DHCP Server
- End Devices

### Branch A

- Router
- Switch
- PCs

### Branch B

- Router
- Switch
- PCs

### Branch C

- Router
- Switch
- PCs

### ISP Core

- Four interconnected routers acting as a service provider backbone.

---

## Technologies Used

- Cisco Packet Tracer
- RIPv2
- DHCP
- DHCP Relay Agent
- VLSM
- ICMP (Ping & Traceroute)

---

## Verification

### DHCP

All branch devices successfully obtain IP addresses from the centralized DHCP server located at HQ.

### Routing

All routers exchange routes dynamically through RIPv2.

### Connectivity

- Branch A ↔ HQ
- Branch B ↔ HQ
- Branch C ↔ HQ
- Branch A ↔ Branch B
- Branch A ↔ Branch C
- Branch B ↔ Branch C

100% reachability achieved without static routes.

---

## Author

Mohamed Amr

Computer Science Student
