# Modern Hotel Network Design and Implementation

This project is a personal learning exercise to design and implement a Hotel network using Cisco Packet Tracer.

---

## 🏨 --Project Scenario--

Modern Hotel has:
- **Three floors**:
- **First floor**: Reception, Store, Logistics
- **Second floor**: Finance, HR, Sales/Marketing
- **Third floor**: IT and Admin

---

## 🔧 **Technologies Implemented**

✅ **Network Topology Creation**  
✅ **Hierarchical Network Design**  
✅ **Router and Switch Cabling**  
✅ **VLANs and Port Assignments**  
✅ **Subnetting and IP Addressing**  
✅ **Inter-VLAN Routing (Router on a Stick)**  
✅ **DHCP Server Configuration (on routers)**  
✅ **OSPF Routing Protocol**  
✅ **SSH Configuration for Remote Login**  
✅ **Switchport Security (Sticky)**  
✅ **Wireless LANs (WIFI for laptops/phones)**  
✅ **Host Device Configuration**  
✅ **Testing and Verifying Communication**

---

## 🔒 **Security and Management**

- **SSH** configured on all routers for secure remote management.
- **Port security** on the IT department switch port `fa0/1` for the `Test-PC`, using sticky MAC address learning and violation mode set to shutdown.

---

## 🧪 **Testing and Verification**

- **Test-PC** in the IT department (port `fa0/1`) used to test SSH access to all routers.
- DHCP verified to dynamically assign IPs to all devices.
- End-to-end connectivity verified for inter-departmental communication.
- Wireless network configured for laptops and phones on each floor.

---

## 🎥 **Resources**
This project was inspired by a Gurutech Networking Training to help understand and practice networking concepts.

---

## 📂 **Project Files**

- `.pkt` file: Contains the complete network topology in Cisco Packet Tracer.
- This README.md file: Project summary.
---
## 🚀 **How to Open**

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/yourrepo.git
