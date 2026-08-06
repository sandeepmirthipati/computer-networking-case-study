# 🛒 E-Commerce Warehouse Network using Cisco Packet Tracer

## 📌 Project Overview

This project demonstrates the design and implementation of an **E-Commerce Warehouse Local Area Network (LAN)** using **Cisco Packet Tracer**. The network connects multiple warehouse departments through routers and switches, enabling secure communication and centralized access to warehouse data.

The network follows a **Star Topology** and uses **IPv4 Class C Private Addressing** to ensure reliable communication between departments.

---

## ❗ Problem Statement

An e-commerce warehouse requires a secure and efficient network to connect all departments, allowing employees to access centralized inventory, order, and customer information. The network should support smooth communication and improve overall warehouse operations.

---

## 🎯 Objectives

- Design a Warehouse LAN using Cisco Packet Tracer.
- Connect all departments using routers and switches.
- Configure IPv4 addressing.
- Enable communication between all departments.
- Verify network connectivity using **Ping** and **Simulation Mode**.

---

## 🏢 Warehouse Departments

| Department | Devices |
|------------|----------|
| Inventory | 3 PCs |
| Packing | 3 PCs + 1 Printer |
| Dispatch | 2 PCs |
| Customer Support | 2 PCs |
| Manager Office | 1 PC |
| Server Room | 1 Server |

---

## 💻 Hardware Requirements

| Device | Quantity |
|---------|----------|
| Cisco 2901 Router | 1 |
| Cisco 2960-24TT Switch | 2 |
| PCs | 11 |
| Printer | 1 |
| Server | 1 |

---

## 🌐 Network Details

| Parameter | Details |
|-----------|---------|
| Network Type | Local Area Network (LAN) |
| Topology | Star Topology |
| IP Addressing | IPv4 |
| IP Class | Class C (Private) |

### IP Addressing Scheme

| Department(s) | Network |
|---------------|---------|
| Inventory & Packing | `192.168.10.0/24` |
| Dispatch, Customer Support, Manager & Server | `192.168.20.0/24` |

---

## 🔗 Network Connections

### Router
- **GigabitEthernet0/0** → Switch 1
- **GigabitEthernet0/1** → Switch 2

### Switch 1
- Inventory PCs
- Packing PCs
- Printer

### Switch 2
- Dispatch PCs
- Customer Support PCs
- Manager PC
- Server

---

## 🛠 Technologies Used

- Cisco Packet Tracer
- Cisco 2901 Router
- Cisco 2960-24TT Switch
- IPv4 Addressing
- Static Routing
- Local Area Network (LAN)

---

## ✅ Testing

The network was tested to ensure successful communication between all devices.

- Ping between all departments.
- Ping from every PC to the Server.
- Packet flow verification using Simulation Mode.

---

## 🎯 Expected Outcome

- Successful communication between all warehouse departments.
- Centralized access to the warehouse server.
- Reliable and efficient internal network communication.
- Proper connectivity between both subnets.
