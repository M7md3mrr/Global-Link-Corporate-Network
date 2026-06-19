🌐 Global-Link Corporate Enterprise Network

CCNA Enterprise Networking Project

A scalable enterprise network designed and implemented using Cisco Packet Tracer, connecting a Headquarters (HQ) with three regional branches through an ISP transit backbone. The project demonstrates dynamic routing, centralized DHCP services, and end-to-end connectivity across multiple sites.

---

📋 Project Overview

This project simulates a real-world corporate infrastructure where multiple branches communicate through a service provider network while obtaining IP addresses from a centralized DHCP server located at the Headquarters.

The objective was to build a scalable and maintainable network architecture using industry-standard networking technologies and best practices.

---

🚀 Network Features

- Dynamic Routing using RIPv2
- Centralized DHCP Server
- DHCP Relay Agent (ip helper-address)
- Multi-Site Enterprise Connectivity
- ISP Transit Backbone
- End-to-End Reachability
- Inter-Branch Communication
- Scalable Network Design
- Network Verification & Troubleshooting

---

🏗️ Network Topology

"Network Topology" (Documentation/Network-Topology.png)

---

🖥️ Network Components

Headquarters (HQ)

- HQ Router
- DHCP Server
- End Devices

Branch A

- Router
- Switch
- PCs

Branch B

- Router
- Switch
- PCs

Branch C

- Router
- Switch
- PCs

ISP Core

- Four interconnected routers acting as the service provider backbone.

---

🛠️ Technologies Used

- Cisco Packet Tracer
- IPv4 Addressing
- DHCP
- DHCP Relay Agent
- RIPv2
- ICMP (Ping)
- Traceroute
- Router Configuration
- Switch Configuration
- Network Troubleshooting

---

✅ Verification

DHCP

All branch devices successfully obtain IP addresses from the centralized DHCP server located at HQ.

Routing

All routers exchange routes dynamically through RIPv2.

Connectivity

- Branch A ↔ HQ
- Branch B ↔ HQ
- Branch C ↔ HQ
- Branch A ↔ Branch B
- Branch A ↔ Branch C
- Branch B ↔ Branch C

100% reachability achieved without static routes.

---

📊 Verification Results

Test| Status
DHCP Assignment| ✅ Passed
RIP Route Exchange| ✅ Passed
End-to-End Connectivity| ✅ Passed
Branch-to-Branch Communication| ✅ Passed

Ping Verification

"Ping Test" (Screenshots/ping-test.png)

Routing Table Verification

"Routing Table" (Screenshots/show-ip-route.png)

RIP Protocol Verification

"RIP" (Screenshots/rip-core.png)

Routing Protocol Details

"Protocols" (Screenshots/show-ip-protocols.png)

---

🎯 Learning Outcomes

Through this project, the following networking concepts were applied and validated:

- Enterprise Network Design
- Dynamic Routing with RIPv2
- DHCP Deployment
- DHCP Relay Configuration
- VLSM Subnetting
- Network Troubleshooting
- Connectivity Verification
- Cisco Router & Switch Configuration

---

👨‍💻 Author

Mohamed Amr

Computer Science Student

CCNA Candidate
