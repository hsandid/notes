---
author: Hsandid
title: Breadth of CCNP ENCOR Network Topics
date: 2025-02-09
description: Quick glance at CCNP ENCOR chapters and topics
---


As I start studying for the CCNP ENCOR / ENARSI certification, I think it's interesting to do a list of the breadth of topics that I will be encountering.

### Section 1 - Packet Forwarding (C1)

Network Device Communication
Layer 2 Forwarding
Collision Domains
Virtual LANs
Access Ports
Trunk Ports
Layer 3 Forwarding
Local Network Forwarding
Packet Routing
IP Address Assignment

Forwarding Architectures
Process Switching
Cisco Express Forwarding
Ternary Content Addressable Memory
Centralized Forwarding
Distributed Forwarding
Software CEF
Hardware CEF
SDM Templates

### Section 2 - Layer 2 (C2-C5)

Spanning Tree Protocol (STP)
IEEE 802.1D STP
802.1D STP Port States
802.1D STP Port Types
Spanning Tree Path Cost
Root Bridge Election

Rapid Spanning Tree Protocol (RSTP - 802.1W)
STP Root Guard
STP Portfast
RSTP Convergence
BPDU Guard
BPDU FIlter

Multiple Spanning Tree Protocol (MST)
Trunk Link Pruning
MST Region Pruning

VLAN Trunks and EtherChannel Bundles
VLAN Trunking Protocol (VTP)
Dynamic Trunking Protocol

EtherChannel Bundle
Dynamic Link Aggregation Protocls
PAgP Port Modes
LACP Port Modes
EtherChannel Configuration
EtherChannel Neighbors

### Section 3 - Routing (C6-C13)

Routing Protocols Overview
Distance Vector Algorithm
Enhanced Distance Vector Algorithms
Link-State Algorithm
Path Vector Algorithm

Path Selection
Prefix Length
Administrative Distance
Metrics
Equal-Cost Multipathing
Unequal-Cost Load Balancing

Static Routing
Static Route Types
Directly Attached Static Routes
Recursive Static Routes
Fully Specified Static Routes
Floating Static Routing
Static Routes to Null Interfaces
IPv6 Static ROutes

Policy-Based Routing
Virtual Routing and Forwarding

EIGRP
Route Summarization

OSPF
Designated Router
Broadcast
Point-to-Point Networks
Loopback Networks

Advanced OSPF
OSPF Areas
Link-State Advertisements
Route Filtering

OSPFv3

BGP
Autonomous Systems
Path Attributes
Loop Prevention
Address Families
Inter-Router Communication
Route Summarization
Multiprotocol BGP for IPv6

BGP Multihoming
Internet/Branch Transit Routing
BGP Conditional Matching with ACLs
Route Maps
BGP Route FIltering
BGP Communities (Well-Known and Private)
BGP Path Selection
MED Discriminator
eBGP vs iBGP

Multicast
L2 Multicast ADdresses
Internet Group Management Protocol (IGMP)
Protocol Independent Multicast (PIM)
### Section 4 - Services (C14-C15)

QoS & QoS Models
Bandwidth
Latency
Jitter
Propagation Delay
Serialization Delay
Processing Delay
Delay Variation
Packet Loss
L7 Classification
MQC Classification
Marking
L2/L3 Marking

Policing and Shaping

Congestion Management and Avoidance

Network Time Protocol
Precision Time Protocol
First-Hop Redundancy Protocol
Hot Standby Router Protocol
Virtual Router Redundancy Protocol (VRRP)

Network Address Translation
Static NAT
Pooled NAT
Port-Address Translation

### Section 5 - Overlay (C16)

Generic Routing Encapsulation Tunnels (GRE)
Recursive Routing challenges

IPsec Fundamentals
Authentication HEader (AH)
Encapsulation Security Payload (ESP)
Transform Sets
Internet Key Exchange (IKEv1, IKEv2)
IPSec VPNs
Site-to-Site (LAN-to-LAN) IPsec VPNs
Cisco Dynamic Multipoint VPN (DMVPN)
Remote VPN Access
GRE over IPsec
VTI over IPsec

Cisco Locator/ID Separation Protocol (LISt)
Proxy ETR / ITR

Virtual Extensible Local Area Network (VXLAN)
### Section 6 - Wireless (C17-C21)

### Section 7 - Architecture (C22-C24)

Hierarchical LAN Design Model
Access Layer
Distribution Layer
Core Layer

High Availability Network Design
SSO, NSF

Enterprise Network Architecture Options
Two-tier Design (Collapsed Core)
Three-Tier Design
L2 Access Layer / STP-based
L3 Access Layer / Routed Access
Software-Defined Access (SD-Access)

Fabric Technologies
Physical Layer, Network Layer, Underlay Network and Overlay Network
Controller Layer
Management Layer

Software-Defined WAN (SD-WAN)

Network Assurance
Network Diagnostic Tools (ping, traceroute)
Debugging tools (SNMP, syslog)
Netflow
Switched Port Analyzer (SPAN)
Remote SPAN (RSPAN)
Encapsulated Remote SPAN (ERSPAN)
IP SLA
### Section 8 - Security (C25-C26)

Network Access Control (NAC)
802.1x
EAP Methods
EAP Chaining
MAC Authentication Bypass (MAB)
Web Authentication (WebAuth)
MACsec (Uplink and Downlink MACsec)

Network Device Access Control and Infrastructure Security
Access Control Lists (ACLs)
Named ACLs, Port ACLs (PACLs), VLAN ACLs (VACLs)

Authentication, Authorization and Accounting
TACACS+
RADIUS
Zone-based Firewall
Control Plane Policing (CoPP)
Device Hardening
### Section 9 - Software-Defined Networking (C27-C29)

Virtualization
Virtual Machines, Containers, Virtual Switching
Network Function Virtualization
Virtualized Infrastructure Manager
OVS-DPDK
PCI Passthrough
SR-IOV

Northbound vs Southbound API
XML, JSON
Data models (YANG, NETCONF, RESTCONF)

Automation Tools
Embedded Event Manager
Agent-Based Automation Tool (Puppet, Chef, SaltStack)
Agentless automation tools (Ansible, Puppet Bolt)


### Additional Glossary
Northbound vs Southbound ([Reference](https://learningnetwork.cisco.com/s/question/0D53i00000Kt419CAB/what-is-the-difference-between-northbound-and-southbound-interfaces))
> North: towards core of data center/internet facing egress of network
> South: towards end-users/VMs/servers

Westbound and Eastbound are towards other SDN controllers..
