# VLAN Configuration Lab

## Objective

Configure VLANs, assign switch ports, configure trunk links, set up a management VLAN, and verify communication between devices in the same VLAN.

---

## Network Devices

- 3 Cisco Switches
- 6 PCs

---

## VLANs

| VLAN | Devices |
|------|---------|
| 10 | PC1, PC4 |
| 20 | PC2, PC5 |
| 30 | PC3, PC6 |
| 99 | Management VLAN |

---

## IP Addressing

### VLAN 10

PC1 - 172.17.10.21/24

PC4 - 172.17.10.24/24

### VLAN 20

PC2 - 172.17.20.22/24

PC5 - 172.17.20.25/24

### VLAN 30

PC3 - 172.17.30.23/24

PC6 - 172.17.30.26/24

### Management VLAN

S1 - 172.17.99.11/24

S2 - 172.17.99.12/24

S3 - 172.17.99.13/24

---

## Configuration Steps

1. Configure PC IP addresses.
2. Create VLANs on all switches.
3. Assign access ports.
4. Configure Management VLAN.
5. Configure trunk links.
6. Verify VLAN communication.

---

## Verification Commands

show vlan brief

show interfaces trunk

ping

---

## Files

- VLAN-Configuration.pkt
- topology.png
