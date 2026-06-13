# Configuration of Address Resolution Protocol (ARP)

## Aim

To construct a simple Local Area Network (LAN) and understand the concept and operation of Address Resolution Protocol (ARP) using Cisco Packet Tracer.

## Problem Statement

Construct simple LAN and understand the concept and operation of Address Resolution Protocol (ARP) using Cisco Packet Tracer. Utilize PCs, 8 port switch and LAN cable

## Scope of the Solution

*Building a simple LAN using Cisco Packet Tracer.
*Configure IP addresses of connected devices
*Look at ARP Request and ARP Reply messages.
*Test communication with the ping command.
*Know how to resolve the IP addresses to MAC address.
*Also check the MAC IP address for correct simulation.

## Architecture of the Solution

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

## Working Principle

1. The MAC address of PC1 is required by computer PC0, therefore computer PC0 will send ARP request.
2. The switch will flood this ARP request to all other computers on the network.
3. This request will be received by computer PC1 and it will respond back to PC0 with ARP reply which will be containing its MAC address.
4. Computer PC0 will receive the MAC address and store it in its own ARP cache.
5. The MAC address of the computer PC1 is found out and both computers PC0 and PC1 will be able to communicate with each other through the MAC address.
6. We need to verify that a conversation is possible between the two computers by the use of the ping command.
7. After using the ping command we also need to check the arp table if the MAC address is correct in order for the simulation to run perfectly.

## Results

The LAN was successfully configured and communication between PCs was established. ARP Request and ARP Reply packets were observed in Simulation Mode, demonstrating the IP-to-MAC address mapping process.

## Conclusion

The Address Resolution Protocol (ARP) was successfully studied and implemented using Cisco Packet Tracer. The project demonstrated how devices in a LAN resolve IP addresses into MAC addresses before communication occurs.
