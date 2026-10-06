# Group 4 COC190 Networking Project: README & Technical Overview

## Introduction

This repository and documentation cover the implementation details for the Group 4 COC190 Networking Project. The objective of this project was to construct a hybrid network comprising physical infrastructure alongside a complete virtual topology, interconnecting them internally and with other groups to facilitate cross-network communication. 

---

## Hardware & Software Infrastructure

The project infrastructure was built across both physical and virtual domains:

* **Physical Hardware:** The physical network was deployed using three old laptops, three old routers, a switch, and a server. 
* **Virtual Side & Emulation:** The virtual side of the network was emulated using Kathara, configuring three virtual routers (`Top`, `Middle`, `Bottom`) and three virtual machines (`u4vm1`, `u4vm2`, `u4vm3`) acting as host endpoints.
* **IP Addressing Strategy:** Distinct blocks were used to separate configurations—IPv4 utilised `56.0.0.0/28` for physical networks and `56.0.1.0/28` for virtual ones, while IPv6 used `2040:D056:0::/64` for physical and `2040:D056:1::/64` for virtual components.
* **Routing Protocols:** Intermediate System-to-Intermediate System (IS-IS) handled dynamic interior routing within Autonomous Systems (AS 4050 for physical, AS 4051 for virtual), while Border Gateway Protocol (BGP) managed exterior routing between the virtual/physical boundaries and external peer groups.

---

## Project Contribution & Individual Effort

* **Overwhelming Contribution:** Despite this being structured as a team project, I authored 14 out of the 15 pages in the report.
* **Complete Technical Ownership:** I independently engineered and executed all of the hardware and software sections of the project.
* **Overcoming Obstacles:** This extra workload was necessitated by team members slacking off and, in some instances, actively sabotaging the project due to a lack of understanding. I put in extra effort and worked overtime to ensure this hit the deadline.
