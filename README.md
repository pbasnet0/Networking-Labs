# Personal Project 1 – Basic LAN Setup (Cisco Packet Tracer)

 Overview
For this project, I built a small local network in Cisco Packet Tracer to understand how devices communicate through a switch.  
I connected two laptops to a Cisco 3650 switch, gave each one a static IP address, and tested if they could reach each other using ping.  
The goal was simple — to get hands-on experience with Layer 2 switching, Ethernet cabling, and IP addressing.

---

 Network Setup
Here’s what I used:
- **1 Cisco 3650 Switch (S1)**  
- **2 Laptops (Laptop1 & Laptop2)**  
- **Connections:**  
  - Laptop1 (Fa0) → Switch (Gig1/0/1)  
  - Laptop2 (Fa0) → Switch (Gig1/0/2)  
- **Cable Type:** Copper Straight-Through  

Both laptops were placed in the same subnet so they could communicate directly without needing a router.

---

 IP Configuration
**Laptop1**
- IPv4: `192.168.1.1`
- Subnet Mask: `255.255.255.0`

**Laptop2**
- IPv4: `192.168.1.2`
- Subnet Mask: `255.255.255.0`
- Default Gateway: `192.168.1.254` *(not required for same subnet but added for testing)*  

Once both devices had their IPs set, I used the command prompt to ping each other and confirm connectivity.

---

What I Learned
- How switches forward frames using MAC addresses  
- How static IPs work within the same network  
- How to test basic connectivity using `ping` and `ipconfig`  
- The importance of using the right cables and matching port types  

It was a simple project, but it really helped me understand the foundation of how devices talk on a local network.

---

 Screenshots
- **Topology Diagram:** shows both laptops connected through the switch  
- **Laptop1 Config:** IP setup and port status  
- **Laptop2 Config:** IP setup and gateway field  

---

 Tools Used
- **Cisco Packet Tracer 9.0.0**
- **Windows Command Prompt (inside Packet Tracer PCs)**

---

Next Steps
Now that I’ve got basic LAN connectivity down, I plan to:
- Add VLANs for network segmentation  
- Use a router to enable inter-VLAN communication  
- Configure DHCP to assign IPs automatically  

This project was a small step, but it helped me build confidence in using Cisco Packet Tracer and understanding real-world network setups.

