# CCNA & Network Engineering Portfolio (CloudBound Tech.)
Welcome to my technical lab portfolio. This repository documents my hands-on journey through the CCNA curriculum and multi-vendor integration (Cisco & Fortinet).

---

## Current Project: Scalable Enterprise Branch
**Goal:** Build a modular branch network from a simple ROAS design to a high-availability enterprise edge.

### Phase 1: The Startup (Router-on-a-Stick)
*Implemented basic Inter-VLAN routing*
* **The Requirements** *
* The CEO of CloudBound Tech my simulated company has given you these headcounts:
  * Sales Dept: 6 Employees.
  * HR Dept: 4 Employees.
  * Management: 2 IT Admins.
* **Key Tasks:** * Configured 802.1Q encapsulation on Cisco 7200 sub-interfaces.
  * Established VLANs 10 (Sales), 20 (HR) and 30 (IT) on the cisco L3 switch.
  * Assigned IP address for each device
    * Network: 172.16.0.0/16
    * VLSM: 
  * Create a management vlan to separate administrative traffic
* **Verification:** Successfully performed inter-VLAN pings between VPCs.
* [View Phase 1 Configs](https://github.com/JaydenThomas007/CCNA-Network-Portfolio/tree/main/configs/phase1) | [View Phase 1 Diagram](./images/phase1.png)

---
