# PearlyEducate-University-Network-Design-

 Enterprise Campus Network Design (Portfolio Project)

## 📌 Overview
This project presents the design and simulation of a **fully redundant enterprise campus network architecture** for a multi-building university environment.

The network was designed following industry best practices inspired by the enterprise campus model recommended by 0, with emphasis on **high availability, scalability, structured segmentation, and fault tolerance**.

The design was implemented and validated using 1.

---

## 🎯 Project Objectives

### Business Objectives
- Ensure high availability across the campus network
- Support academic, administrative, residential, and operational services
- Enable secure and scalable network expansion
- Centralize monitoring and management
- Support VoIP and CCTV services

### Technical Objectives
- Implement a redundant backbone architecture
- Achieve fast routing convergence
- Provide gateway redundancy
- Enforce VLAN-based segmentation
- Centralize IP address management
- Secure WAN internet access

---

## 🏗️ Network Architecture

The network follows a **three-layer hierarchical campus model**:

### 🔹 Core Layer
- Redundant ring backbone topology
- High-speed Layer 3 switching
- OSPF backbone (Area 0)

### 🔹 Distribution Layer
- Inter-VLAN routing
- HSRP for default gateway redundancy
- Access Control Lists (ACLs) enforcement

### 🔹 Access Layer
- End-user connectivity
- VLAN assignments
- Port security configuration

---

## 🌐 Key Technologies Implemented

- **OSPF** – Dynamic routing protocol for fast convergence  
- **HSRP** – First-hop redundancy for gateway availability  
- **VLANs** – Traffic segmentation and isolation  
- **Centralized DHCP** – IP address management with DHCP relay  
- **NAT Overload** – Internet access at WAN edge  
- **VoIP** – Dedicated voice VLAN and structured dial plan  
- **CCTV Integration** – Centralized monitoring over isolated VLAN  
- **ACLs** – Network security and traffic control  

---

## 📊 VLAN Design Summary

| VLAN ID | Name       | Purpose |
|-------|------------|--------|


---

## 🔁 Redundancy & High Availability

- Ring backbone eliminates single points of failure  
- Dual distribution switches per campus zone  
- HSRP ensures seamless gateway failover  
- Routed links prevents Layer 2 loops  
- Redundant uplinks tested under failure scenarios  

---

## 🔐 Security Architecture

- NAT boundary at WAN edge
- Management VLAN isolation
- Port security at access switches

---

## 🧪 Testing & Validation

The design was tested under simulated failure conditions:

- ✔ End-to-end connectivity verification  
- ✔ HSRP failover testing  
- ✔ OSPF convergence testing  
- ✔ NAT translation verification  
- ✔ Inter-VLAN routing validation  

All tests passed successfully.

---

## 📈 Scalability & Future Expansion

- Modular VLAN expansion
- Easy onboarding of new buildings
- Wireless network integration

---

## 🧠 Key Design Decisions

- **Ring Backbone:** Chosen for resilience and redundancy  
- **Centralized DHCP and DNS:** Simplifies IP management, names resolution, and scaling  
- **VLAN Segmentation:** Enhances performance and security  
- **HSRP:** Guarantees uninterrupted gateway access  

---

## 🛠️ Tools Used

- 2  
- Layer 2 & Layer 3 Switching  
- Enterprise Routing Protocols  
- Structured IP Addressing  

---

## 📌 Author

**Yinka Kolapo**  
Network Engineer | Computer Science Student  
Portfolio Project

---

## 📎 Notes

This project was designed, simulated, and validated as a **portfolio-grade enterprise campus network**, reflecting real-world networking practices and fault-tolerant design principles.
