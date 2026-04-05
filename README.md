# Cisco-Packet-Tracer-project-11-Building-A-SoftwareEngineeringCampus-500-Smartphones-Laptop-Printers-

I’m excited to share my latest Cisco Packet Tracer project – Building A (Software Engineering) – a high‑density network simulation of a modern office building. The topology features:

![image alt](https://github.com/Sameera54321/Cisco-Packet-Tracer-project-11-Building-A-SoftwareEngineeringCampus-500-Smartphones-Laptop-Printers-/blob/main/10.png?raw=true)

## 📌 Summary

Building A – Software Engineering is a Cisco Packet Tracer simulation that models a high‑density office building occupied by a software engineering department. The network includes:

    1 Laptop – used for management, development, or as a test client

    4 Printers – shared printing resources for all employees

    501 Smartphones (Smartphone1 … Smartphone500 + one additional Smartphone) – representing developers, testers, and staff using mobile devices

### The project focuses on:

    Wireless network design – multiple access points (implicitly or explicitly) to handle 500+ concurrent wireless clients

    IP address management – DHCP scope large enough for 500+ devices (e.g., /23 subnet)

    Printer sharing – using a print server or direct IP printing from smartphones and laptop

    VLAN segmentation – separating wireless traffic from wired printers and management

    Performance considerations – broadcast traffic, channel utilisation, and roaming in a dense environment

## ✨ Features

    ✅ 501 smartphones – large‑scale wireless client population

    ✅ 1 laptop – administrative or development endpoint

    ✅ 4 printers – shared network printing services

    ✅ Wireless LAN – supports hundreds of simultaneous connections (simulated)

    ✅ DHCP server (router or dedicated server) – automatic IP assignment for all smartphones

    ✅ Printer access – from both wired (laptop) and wireless (smartphones) clients

    ✅ Scalability testing – observe switch/router performance with many wireless clients

    ✅ Full Packet Tracer file (.pkt) – ready to open and experiment

    ✅ Documentation – wireless configuration, IP plan, VLAN design, printer setup

Suggested IP Addressing:

| Device Type | Subnet | DHCP Range | Gateway |
| :--- | :--- | :--- | :--- |
| Smartphones | 192.168.100.0/23 | 192.168.100.1 – 192.168.101.254 | 192.168.100.1 |
| Laptop | 192.168.10.0/24 | Static or DHCP reserved | 192.168.10.1 |
| Printers | 192.168.20.0/29 | Static | 192.168.20.1 |
| Servers | 192.168.30.0/28 | Static | 192.168.30.1 |

## 🛠️ Built With

    Cisco Packet Tracer – version 8.x

    CLI – router, switch, and wireless access point configurations

    (Optional) Python – if used to generate 500+ smartphone configs or IP lists

## 🤝 Contributing

Contributions are welcome! To extend this lab:

    Fork the repository.

    Add more realistic wireless features – e.g., WPA2 authentication, multiple SSIDs (guest vs corporate).

    Implement Quality of Service (QoS) for voice/video over the dense wireless network.

    Add a radius server for 802.1X authentication.

    Introduce roaming between multiple access points.

    Document the exact number of APs and their placement.

    Open a pull request with a clear description.

## 📜 License

Distributed under the MIT License. See the LICENSE file for more information.
Free to use, modify, and share for educational purposes.
