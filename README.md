# Configuration of Address Resolution Protocol (ARP)

## Aim

To construct a simple Local Area Network (LAN) and understand the concept and operation of Address Resolution Protocol (ARP) using Cisco Packet Tracer.

## Problem Statement

Design and simulate a simple LAN using PCs, an 8-port switch, and LAN cables. Configure IP addresses and demonstrate the working of ARP in resolving IP addresses into MAC addresses for communication within the network.

## Scope of the Solution

* Build a simple LAN using Cisco Packet Tracer.
* Configure IP addresses for connected devices.
* Observe ARP Request and ARP Reply messages.
* Verify communication using the ping command.
* Understand IP-to-MAC address resolution.

## Overview / Architecture of the Solution

PC0 ---- Switch0 ---- PC1

### IP Configuration

PC0:

* IP Address: 192.168.1.1
* Subnet Mask: 255.255.255.0

PC1:

* IP Address: 192.168.1.2
* Subnet Mask: 255.255.255.0

## Required Components

### Hardware Components

* Personal Computer (Virtual PC)
* 8-Port Switch
* LAN Cable

### Software Components

* Cisco Packet Tracer
* GitHub

## Working Principle

1. PC0 sends an ARP Request to find the MAC address of PC1.
2. The switch broadcasts the ARP Request.
3. PC1 responds with an ARP Reply containing its MAC address.
4. PC0 stores the MAC address in its ARP cache.
5. Communication begins using the MAC address.
6. Successful communication is verified using the ping command.

## Results

The LAN was successfully configured and communication between PCs was established. ARP Request and ARP Reply packets were observed in Simulation Mode, demonstrating the IP-to-MAC address mapping process.

## Conclusion

The Address Resolution Protocol (ARP) was successfully studied and implemented using Cisco Packet Tracer. The experiment demonstrated how devices in a LAN resolve IP addresses into MAC addresses before communication occurs.
