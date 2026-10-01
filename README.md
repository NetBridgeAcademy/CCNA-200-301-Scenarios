# CCNA 200-301 Scenarios

A collection of **Cisco Packet Tracer hands-on scenarios** designed for practicing and reinforcing the core networking concepts covered by the **Cisco CCNA 200-301** certification.

These scenarios focus on practical configuration, troubleshooting, and verification of Cisco networking technologies commonly encountered in CCNA-level network environments.

---

## Overview

This repository provides ready-to-use `.pkt` scenarios for **Cisco Packet Tracer**.

The goal is to move beyond theoretical learning and provide practical network configuration exercises covering:

* Network fundamentals
* VLANs and trunking
* Inter-VLAN routing
* Spanning Tree Protocol
* EtherChannel
* Static and dynamic routing
* OSPF and EIGRP
* IPv4 and IPv6
* DHCP
* NAT
* ACLs
* First Hop Redundancy Protocol
* IPsec and GRE
* Cisco Discovery Protocol
* Dynamic Trunking Protocol
* VLAN Trunking Protocol
* Wireless networking

Each scenario can be opened directly in Cisco Packet Tracer and used for configuration and troubleshooting practice.

---

## Scenarios

| Scenario | Topic              | File                                                 |
| -------- | ------------------ | ---------------------------------------------------- |
| 01       | VLAN               | [`VLAN.pkt`](./VLAN.pkt)                             |
| 02       | Trunking & VLANs   | [`Trunking VLANs.pkt`](./Trunking%20VLANs.pkt)       |
| 03       | VTP                | [`VTP.pkt`](./VTP.pkt)                               |
| 04       | DTP                | [`DTP.pkt`](./DTP.pkt)                               |
| 05       | STP                | [`STP.pkt`](./STP.pkt)                               |
| 06       | EtherChannel       | [`EtherChannel.pkt`](./EtherChannel.pkt)             |
| 07       | Inter-VLAN Routing | [`InterVlan Routing.pkt`](./InterVlan%20Routing.pkt) |
| 08       | Static Routing     | [`Static Routing.pkt`](./Static%20Routing.pkt)       |
| 09       | OSPF               | [`OSPF.pkt`](./OSPF.pkt)                             |
| 10       | EIGRP              | [`EIGRP.pkt`](./EIGRP.pkt)                           |
| 11       | DHCPv4             | [`DHCPv4.pkt`](./DHCPv4.pkt)                         |
| 12       | NAT                | [`NAT.pkt`](./NAT.pkt)                               |
| 13       | ACL                | [`ACL.pkt`](./ACL.pkt)                               |
| 14       | HSRP               | [`HSRP.pkt`](./HSRP.pkt)                             |
| 15       | IPv6               | [`IPv6.pkt`](./IPv6.pkt)                             |
| 16       | IPsec over GRE     | [`IPsec over GRE.pkt`](./IPsec%20over%20GRE.pkt)     |
| 17       | CDP                | [`CDP.pkt`](./CDP.pkt)                               |
| 18       | Wireless           | [`Wireless.pkt`](./Wireless.pkt)                     |

---

## Topics Covered

### Switching

* VLAN configuration
* Access ports
* Trunk ports
* 802.1Q trunking
* VTP
* DTP
* STP
* EtherChannel
* Inter-VLAN routing

### Routing

* Static routing
* Dynamic routing
* OSPF
* EIGRP
* Default routing
* Route verification and troubleshooting

### IP Services

* DHCPv4
* NAT
* Network connectivity verification

### Network Security

* Standard and extended ACLs
* IPsec
* GRE tunnels
* IPsec over GRE

### High Availability

* HSRP
* Redundant gateway configuration
* Gateway failover and verification

### IPv6

* IPv6 addressing
* IPv6 connectivity
* IPv6 routing fundamentals

### Network Discovery & Management

* CDP
* DTP
* VTP
* Wireless networking fundamentals

---

## Requirements

To use these scenarios, you need:

* **Cisco Packet Tracer**
* Basic understanding of Cisco IOS CLI
* Basic knowledge of IPv4 networking and subnetting

Cisco Packet Tracer can be downloaded through Cisco Networking Academy.

---

## How to Use

1. Clone or download this repository.

```bash
git clone https://github.com/NetBridgeAcademy/CCNA-200-301-Scenarios.git
```

2. Open the desired `.pkt` file with **Cisco Packet Tracer**.

3. Review the topology and identify the devices, interfaces, VLANs, IP addressing, and network requirements.

4. Configure the devices using the Cisco IOS CLI.

5. Verify the configuration using appropriate operational commands.

6. Troubleshoot connectivity or configuration problems when required.

---

## Recommended Practice Method

For each scenario, try to complete the configuration without looking at the solution first.

A practical workflow is:

```text
1. Read the scenario
        ↓
2. Analyze the topology
        ↓
3. Identify requirements
        ↓
4. Create an addressing plan
        ↓
5. Configure devices
        ↓
6. Verify configuration
        ↓
7. Test end-to-end connectivity
        ↓
8. Troubleshoot any issues
```

Useful Cisco IOS verification commands include:

```text
show running-config
show startup-config
show ip interface brief
show interfaces
show vlan brief
show interfaces trunk
show mac address-table
show spanning-tree
show etherchannel summary
show ip route
show ip protocols
show ip ospf neighbor
show ip eigrp neighbors
show access-lists
show ip nat translations
show standby
show cdp neighbors
```

---

## Learning Objectives

After completing these scenarios, you should be able to:

* Configure and troubleshoot VLANs and trunk links.
* Configure inter-VLAN communication.
* Understand and troubleshoot STP.
* Configure EtherChannel.
* Implement static and dynamic routing.
* Configure OSPF and EIGRP.
* Configure DHCP and NAT.
* Implement ACL-based traffic filtering.
* Configure HSRP for gateway redundancy.
* Work with IPv6 addressing and connectivity.
* Understand GRE and IPsec tunnel concepts.
* Use Cisco IOS verification commands effectively.
* Develop a structured approach to network troubleshooting.

---

## CCNA 200-301 Alignment

The scenarios are intended to support practical learning across the major CCNA 200-301 technology areas, including:

* Network fundamentals
* Network access
* IP connectivity
* IP services
* Security fundamentals
* Automation and programmability concepts

The scenarios are **practice material** and are not intended to replace official Cisco CCNA training or examination material.

---

## Repository Structure

```text
CCNA-200-301-Scenarios/
│
├── ACL.pkt
├── CDP.pkt
├── DHCPv4.pkt
├── DTP.pkt
├── EIGRP.pkt
├── EtherChannel.pkt
├── HSRP.pkt
├── IPsec over GRE.pkt
├── IPv6.pkt
├── InterVlan Routing.pkt
├── NAT.pkt
├── OSPF.pkt
├── STP.pkt
├── Static Routing.pkt
├── Trunking VLANs.pkt
├── VLAN.pkt
├── VTP.pkt
├── Wireless.pkt
└── README.md
```

---

## Disclaimer

This repository is an independent collection of networking practice scenarios created for educational purposes.

**CCNA** and **Cisco Packet Tracer** are trademarks of Cisco Systems, Inc. This repository is not affiliated with, sponsored by, or endorsed by Cisco Systems, Inc.

---

## Maintainer

**NetBridge Academy**

Networking and cybersecurity learning resources focused on practical, hands-on technical training.

---

## License

This repository is provided for educational and learning purposes.

If you use or modify these scenarios, please retain appropriate attribution to the original repository.
