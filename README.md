# Enterprise Network Design using Cisco Packet Tracer

A multi-segment office network designed and configured using Cisco Packet Tracer. The project demonstrates network segmentation, routing, DHCP, wireless connectivity, and simulated internet access.

## Features

- Multi-segment network architecture
- Router-based communication between subnets
- DHCP configuration for automatic IP assignment
- Static IP configuration for printers
- Wireless Access Points with WPA2-PSK security
- Simulated ISP router and Internet Server
- Connectivity verification using ping tests
- Routing table verification using Cisco CLI

## Network Topology

### Segment A
- Network: `192.168.10.0/24`
- 3 Wired PCs
- 2 Wireless Laptops
- 1 Wired Printer
- 1 Switch
- 1 Access Point

### Segment B
- Network: `192.168.20.0/24`
- 2 Wired PCs
- 3 Wireless Laptops
- 1 Wireless Printer
- 1 Switch
- 1 Access Point

Both segments are connected through a central router, which also provides DHCP services and internet connectivity through a simulated ISP.

## Technologies Used

- Cisco Packet Tracer
- IPv4 Addressing
- DHCP
- Static Routing
- Wireless Networking
- WPA2-PSK
- Cisco IOS CLI

## Project Structure

```
.
├── packet-tracer/
│   └── Multi-Segment-Network.pkt
├── screenshots/
│   ├── topology.png
│   ├── dhcp.png
│   ├── wireless-config.png
│   ├── ping-test.png
│   ├── internet-access.png
│   └── routing-table.png
├── README.md
└── LICENSE
```

## Screenshots

### Network Topology

> *(Add a screenshot here.)*

### Connectivity Test

> *(Add a ping test screenshot here.)*

### Routing Table

> *(Add a screenshot of `show ip route` here.)*

## Learning Outcomes

This project demonstrates practical knowledge of:

- Network design
- IP addressing and subnetting
- Router configuration
- DHCP deployment
- Wireless network configuration
- Network troubleshooting
- Connectivity testing

## License

This project is licensed under the MIT License.