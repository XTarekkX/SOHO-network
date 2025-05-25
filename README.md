# Branch Office Network Design Project

This project simulates a small-scale branch office network designed to meet the connectivity needs of three separate departments. The network is intended to operate independently with efficient communication, secure segmentation, and wireless access for users in each department.

---

## 🏢 Network Overview

The branch office network consists of:

- **One Cisco Router** acting as the central routing device.
- **One Cisco Layer 2 Switch** providing wired connectivity and VLAN segmentation.
- **Three Departments:**  
  - **Admin / IT**  
  - **Finance / HR**  
  - **Customer Service / Reception**

Each department is logically segmented into its own VLAN for security and traffic management. Additionally, each department has dedicated wireless access via Cisco Access Points, ensuring seamless wireless connectivity for mobile users.

---

## 🌐 Network Requirements

- Separate **VLANs** for each department to isolate traffic.
- Wireless networks configured for each VLAN to provide department-specific Wi-Fi access.
- All host devices configured to obtain IPv4 addresses dynamically through a **Router-based DHCP server**.
- Full communication capability between devices across all VLANs through **Inter-VLAN routing**.
- IP addressing based on the assigned network block: `192.168.1.0/24`.

---

## 🛠️ Technologies Implemented

- Cisco Packet Tracer simulation for topology design and configuration.
- Proper cabling between router, switch, and access points.
- VLAN creation and port assignments to segregate department traffic.
- Subnetting and IP address planning within the 192.168.1.0/24 network.
- Router-on-a-stick configuration for Inter-VLAN routing using a single physical interface on the router.
- Router-based DHCP server setup for automatic IP assignment.
- Configuration of wireless networks on Cisco Access Points aligned with respective VLANs.
- Host device configuration for DHCP IP acquisition.
- Testing and verification of connectivity within and across VLANs, including wired and wireless clients.

---

## 📂 Project Files

SOHO-network/
┣ 📄 README.md ← Project documentation

┣ 📂 project 2.pkt ← Cisco Packet Tracer simulation file


---

## 🚀 How to Use This Project

1. Install **Cisco Packet Tracer** to open `.pkt` files.
2. Load `branchOfficeNetwork.pkt` in Packet Tracer.
3. Review the network topology including VLANs, wireless access points, and device connections.
4. Enter simulation mode to test IP addressing, DHCP operations, and inter-VLAN communication.
5. Verify wireless clients connect properly to their respective VLAN SSIDs.
6. Inspect router and switch configurations to understand VLAN and routing setup.
7. Customize or expand the topology as needed for further testing or learning.

---

## 📢 Notes

- Wireless networks are configured per department VLAN, ensuring traffic segmentation even over Wi-Fi.
- The router handles DHCP and Inter-VLAN routing through a single trunk link to the switch.
- All devices receive IP addresses dynamically, simplifying network management.
- The design emphasizes a scalable, secure, and manageable small office network ideal for branch deployment.

---

This project is designed as a practical introduction to VLANs, Inter-VLAN routing, DHCP, and wireless network configuration in a Cisco environment.
