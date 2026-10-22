# Network Labs

Hands-on networking labs built in Cisco Packet Tracer 9.0 – topologies, addressing, device configs and verification steps.

| # | Lab | Topics |
|---|---|---|
| 01 | [Basic router configuration](01-basic-config/) | IOS modes, interface addressing, saving config |
| 02 | [Routing between two networks](02-two-networks/) | Default gateway, directly connected routes |
| 03 | [Troubleshooting](03-troubleshooting/) | Fault finding with `show`, `ping`, `tracert` |
| 04 | [VLANs and inter-VLAN routing](04-vlan/) | VLANs, access ports, 802.1Q trunk, router-on-a-stick |
| 05 | [Router-on-a-stick (minimal build)](05-router-on-a-stick/) | Subinterfaces, `encapsulation dot1Q` |
| 06 | [DHCP for multiple VLANs](06-dhcp/) | DHCP pools, excluded addresses, DORA, APIPA |
| 07 | [SSH and router hardening](07-ssh/) | SSH, local users, enable secret, login block-for, banner |
| 08 | [SSH management of a switch](08-ssh-switch/) | SVI, default gateway, VTY 0–15, requirements-based task |

Each lab folder contains:
- `README.md` – goal, topology, addressing, key config, verification
- `configs/` – full `running-config` of every Cisco device (passwords redacted)
- `*.pkt` – the Packet Tracer file

Author: [Rafał Klyszcz](https://github.com/KlyszczRafal)
