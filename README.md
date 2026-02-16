# CCNA & Network Engineering Portfolio
Welcome to my technical lab portfolio. This repository documents my hands-on journey through the CCNA curriculum and multi-vendor integration (Cisco & Fortinet).

---

## Current Project: Scalable Enterprise Branch
**Goal:** Build a modular branch network from a simple ROAS design to a high-availability enterprise edge.

### Phase 1: Router-on-a-Stick (Completed)
*Implemented basic Inter-VLAN routing and DHCP services.*

* **Key Tasks:** * Configured 802.1Q encapsulation on Cisco 7200 sub-interfaces.
  * Established VLANs 10 (Sales) and 20 (HR) on a vIOS-L3 switch.
* **Verification:** Successfully performed inter-VLAN pings between VPCs.
* [View Phase 1 Configs](./configs/phase1/) | [View Phase 1 Diagram](./images/phase1-topo.png)

---

### Phase 2: Redundancy & High Availability (In Progress)
*Adding Spanning Tree optimization, EtherChannel, and FHRP.*

* **Status:** Currently configuring LACP EtherChannel between distribution switches.
* **Next Steps:** Implement HSRP for gateway redundancy.

---

### 📍 Phase 3: The Secure Edge (Upcoming)
*Integrating OSPF routing and Fortinet Firewall policies.*
