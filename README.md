# 🏫 Campus Wide Network Design

A comprehensive campus-wide network topology designed and simulated using **Cisco Packet Tracer**. This project demonstrates the planning, design, and implementation of a scalable, secure, and efficient network infrastructure for a multi-building educational campus environment.

---

## 📌 Project Overview

This project simulates a real-world campus network that connects multiple departments, buildings, and administrative offices using industry-standard networking concepts and Cisco equipment.

---

## 🗂️ Project File

| File | Description |
|------|-------------|
| `Project_2.pkt` | Cisco Packet Tracer simulation file |

---

## 🛠️ Tools & Technologies

- **Cisco Packet Tracer** — Network simulation tool
- **Cisco Routers & Switches** — Core and distribution layer devices
- **Protocols Used:**
  - VLAN (Virtual LAN) — Department segmentation
  - Inter-VLAN Routing — Communication between VLANs
  - OSPF / RIP / Static Routing — Network routing
  - DHCP — Dynamic IP address allocation
  - DNS — Domain name resolution
  - HTTP/HTTPS — Web server simulation
  - SSH / Telnet — Remote device management

---

## 🏗️ Network Topology

The campus network is structured using a **hierarchical three-layer model**:

```
[Access Layer]       — End devices (PCs, Laptops, Printers) per department
      ↓
[Distribution Layer] — Layer 3 switches managing VLANs and inter-department routing
      ↓
[Core Layer]         — High-speed backbone connecting all buildings/blocks
      ↓
[Edge Router]        — Connects campus to the Internet / ISP
```

### 🏢 Campus Buildings / Departments Covered:
- Admin Block
- Faculty Block
- Student Labs
- Library
- Hostel / Residential Block
- Server Room / Data Center

---

## 🔐 Security Features

- VLANs for network segmentation and isolation
- Access Control Lists (ACLs) for traffic filtering
- Port security on access layer switches
- SSH enabled for secure remote management (Telnet disabled)

---

## 📡 IP Addressing Scheme

The network uses a structured subnetting plan:

| Department / VLAN | Network Address | Subnet Mask | VLAN ID |
|-------------------|-----------------|-------------|---------|
| Admin             | 192.168.10.0    | /24         | 10      |
| Faculty           | 192.168.20.0    | /24         | 20      |
| Student Labs      | 192.168.30.0    | /24         | 30      |
| Library           | 192.168.40.0    | /24         | 40      |
| Server Room       | 192.168.50.0    | /24         | 50      |

> ⚠️ *IP addressing may vary — refer to the `.pkt` file for exact configuration.*

---

## 🚀 How to Run

1. Install **Cisco Packet Tracer** (version 8.0 or later recommended).
   - Download from [Cisco NetAcad](https://www.netacad.com/)
2. Clone or download this repository.
3. Open `Project_2.pkt` in Cisco Packet Tracer.
4. Explore the topology, click on devices to view configurations.
5. Use **Simulation Mode** to observe packet flow across the network.

---

## 📚 Learning Outcomes

- Designing a hierarchical campus network from scratch
- Configuring VLANs and Inter-VLAN routing
- Implementing dynamic routing protocols
- Setting up DHCP, DNS, and web servers
- Applying network security best practices

---

## 👤 Author

**Syed Saif Ali**
Software Engineering Student 

---

## 📄 License

This project is for academic purposes only.
