
#  VLANs & Trunking Lab

##  Scenario

A company is deploying multiple switches in a branch office and requires network segmentation to separate departments while maintaining connectivity across switches.

---

## Objectives

* Configure VLANs on multiple switches
* Assign access ports to VLANs
* Configure static and dynamic trunking
* Implement a management VLAN
* Configure a voice VLAN

---

##  VLAN Overview

| VLAN | Name       |
| ---- | ---------- |
| 10   | Admin      |
| 20   | Finance    |
| 30   | HR         |
| 40   | Voice      |
| 99   | Management |
| 100  | Native     |

---

##  Topology

![Topology](topology.png)

---

##  Key Configurations

* VLAN creation and naming
* Access port assignment for end devices
* Static trunk configuration between switches
* Dynamic trunk negotiation using DTP
* Native VLAN configuration to avoid mismatches
* Voice VLAN setup for IP telephony
* Management VLAN (SVI) for switch access

---

##  Configurations

* [SWA Configuration](configs/swa-config.txt)
* [SWB Configuration](configs/swb-config.txt)
* [SWC Configuration](configs/swc-config.txt)

---

## Verification

* Devices within the same VLAN can communicate across switches
* Trunk links successfully carry multiple VLANs
* VLAN segmentation prevents unnecessary broadcast traffic
* No native VLAN mismatches observed

---

##  Key Learnings

* VLANs improve security and reduce broadcast domains
* Trunking allows multiple VLANs over a single link
* DTP enables dynamic trunk negotiation between switches
* Proper native VLAN configuration is critical for stability
* Voice VLANs separate and prioritize voice traffic

---

