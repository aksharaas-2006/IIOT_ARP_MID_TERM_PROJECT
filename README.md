# Configuration of Address Resolution Protocol (ARP)

## Aim

To construct a simple Local Area Network (LAN) and understand the concept and operation of Address Resolution Protocol (ARP) using Cisco Packet Tracer.

## Problem Statement

Construct simple LAN and understand the concept and operation of Address Resolution Protocol (ARP) using Cisco Packet Tracer. Utilize PCs, 8 port switch and LAN cable
One of the key protocols in the field of network communications is the Address Resolution Protocol (ARP), which is widely used to connect devices within the same Local Area Network (LAN).
In IIoT, there are various types of devices connected to the network, where they communicate with each other using IP addresses. In order to ensure successful communication, it is critical to know the basics of how the ARP works.
Even though ARP works automatically in any networked environment, it does not give much insight into how it works to ordinary users. Therefore, it is important to conduct an ARP experiment using Cisco Packet Tracer by setting up a LAN with two PCs communicating via the Switch. Thus, we will be able to monitor ARP request and reply messages and learn how IP addresses are translated into MAC addresses in simple scenarios. It should be noted that due to the fact that it is a simplified simulation, it is not designed to cover more complex networking technologies like routers and VLANs.

## Scope of the Solution

This project will attempt to learn the operation of Address Resolution Protocol (ARP) in a basic Local Area Network (LAN). It attempts to create a network with the use of two PCs and a switch with Cisco Packet Tracer. This will be done through configuration of IP addresses and observing how ARP maps IP addresses into MAC addresses.
The outcomes indicate that both ARP Request and ARP Reply are noticeable in this simulation experiment and good communication is achievable via the ping command. But because it is an experiment related to simulation, only simple LAN systems will be considered here without taking into account routers, VLANs, and wireless LANs.

## Architecture of the Solution

PC0----Switch0----PC1

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
