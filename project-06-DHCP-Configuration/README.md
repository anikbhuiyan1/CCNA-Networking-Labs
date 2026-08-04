# DHCP Configuration Lab

## Question

Configure a DHCP server on the router to automatically assign IP addresses to all client devices in the 192.168.10.0/24 network.

### Requirements

1. Configure Router0 with the IP address 192.168.10.1/24.
2. Configure Router0 as a DHCP Server.
3. Create a DHCP pool for the 192.168.10.0/24 network.
4. Set the default gateway as 192.168.10.1.
5. Configure all end devices to obtain IP addresses automatically.
6. Verify that all devices receive IP addresses from the DHCP server.
7. Test connectivity using the ping command.

---

## Network Topology

![Topology](topology.png)

---

## Devices

- Router0
- Switch0
- PC0
- Laptop0
- Laptop1

---

## Network Information

| Item | Value |
|------|--------|
| Network | 192.168.10.0/24 |
| Default Gateway | 192.168.10.1 |
| DHCP Server | Router0 |

---

## Configuration Steps

1. Configure Router Interface.
2. Configure DHCP Pool.
3. Configure Default Gateway.
4. Exclude Reserved IP Addresses (if required).
5. Set PCs to DHCP Mode.
6. Verify Assigned Addresses.
7. Test Network Connectivity.

---

## Verification Commands

show ip dhcp binding

show ip dhcp pool

show running-config

ipconfig

ping

---

## Technologies Used

- Cisco Packet Tracer
- DHCP
- IPv4
- Router
- Switch
