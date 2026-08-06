E-Commerce Warehouse Network using Cisco Packet Tracer
📌 Project Overview

This project simulates an E-Commerce Warehouse Network using Cisco Packet Tracer. It connects multiple warehouse departments through a Local Area Network (LAN) to provide secure communication and centralized data management.

❗ Problem Statement

An e-commerce warehouse requires a reliable network to connect all departments, allowing employees to access inventory, order, and customer information from a centralized server for efficient warehouse operations.

🎯 Objectives
Design a warehouse LAN.
Connect all departments using routers and switches.
Configure IPv4 addressing.
Enable communication between all departments.
Verify connectivity using Ping and Simulation Mode.
🏢 Departments
Department	Devices
Inventory	3 PCs
Packing	3 PCs + 1 Printer
Dispatch	2 PCs
Customer Support	2 PCs
Manager Office	1 PC
Server Room	1 Server
💻 Hardware Requirements
Device	Quantity
Cisco 2901 Router	1
Cisco 2960-24TT Switch	2
PCs	11
Printer	1
Server	1
🌐 Network Details
Network Type: LAN (Local Area Network)
Topology: Star Topology
IP Class: Class C (Private)
Subnets
Inventory & Packing: 192.168.10.0/24
Dispatch, Customer Support, Manager & Server: 192.168.20.0/24
🔗 Network Connections
Switch 1
Inventory PCs
Packing PCs
Printer
Switch 2
Dispatch PCs
Customer Support PCs
Manager PC
Server
Router
G0/0 → Switch 1
G0/1 → Switch 2
🛠 Technologies Used
Cisco Packet Tracer
Cisco 2901 Router
Cisco 2960-24TT Switch
IPv4 Addressing
Static Routing
Local Area Network (LAN)
✅ Testing
Ping between departments.
Ping from all PCs to the Server.
Verify packet flow using Simulation Mode.
🎯 Expected Outcome
Successful communication between all departments.
Centralized access to the warehouse server.
Efficient and reliable internal network communication.
🚀 Future Enhancements
VLAN Implementation
DHCP Configuration
Access Control Lists (ACLs)
Wireless Devices
IP CCTV Cameras
Multi-Branch Warehouse Connectivity
