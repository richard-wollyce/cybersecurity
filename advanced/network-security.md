---
title: "Network Security"
description: "Advanced concepts in securing network infrastructure."
---

# Network Security

Network security is the practice of preventing and protecting against unauthorized intrusion into corporate networks. As a technical professional, understanding the layers of network defense is critical.

## Firewalls and Traffic Filtering
A firewall establishes a barrier between a trusted internal network and an untrusted external network (like the Internet).
- **Stateless Firewalls:** Inspect individual packets in isolation, usually filtering based on source/destination IP, protocol, and port.
- **Stateful Firewalls:** Track the state of active connections and make decisions based on the context of the traffic flow.
- **Next-Generation Firewalls (NGFW):** Combine traditional firewall technology with application-level inspection, intrusion prevention, and deep packet inspection.

## Network Segmentation
Flat networks are dangerous; if an attacker compromises one device, they can move laterally to any other device.
- **Segmentation** divides a network into smaller, isolated subnetworks (VLANs).
- Organizations typically separate guest Wi-Fi, user workstations, servers, and sensitive databases into different segments.
- Communication between segments is strictly controlled by internal firewalls or Access Control Lists (ACLs).

## Intrusion Detection and Prevention (IDS/IPS)
- **IDS (Intrusion Detection System):** Monitors network traffic for suspicious activity and known threats, sending alerts when anomalous behavior is detected. It is passive.
- **IPS (Intrusion Prevention System):** Sits inline with traffic and can actively drop packets or block connections if malicious activity is identified.

## Virtual Private Networks (VPNs)
VPNs extend a private network across a public network, allowing users to send and receive data as if their computing devices were directly connected to the private network.
- **IPsec:** Operates at the network layer, often used for site-to-site VPNs.
- **TLS/SSL VPNs:** Operate at the transport layer, commonly used for remote user access.
