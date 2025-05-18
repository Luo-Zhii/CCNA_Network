# CCNA_Network
#  Introduction
 SmileHaha, a UK-based company in the banking and insurance sector, is expanding its operations to Hanoi, Vietnam. The company has acquired a 4-story building  and needs a complete network infrastructure setup. This project simulates the network using Cisco Packet Tracer.

# Project Requirements
    12 departments across 4 floors, each with ~60 users (wired + wireless).

    Each department: 20 PCs, 4 printers (except Guest Area and Server Room).

    Server Room: 3 servers (DHCP, HTTP, Email) + 2 Admin PCs.

    Each department must have a separate VLAN and subnet.

    All devices must receive dynamic IPs from a dedicated DHCP server located in the Server Room.

    Hierarchical Network Design model: Core – Distribution – Access layers.

    Use OSPF as the routing protocol.

    Implement switch security (port-security) and enable SSH for remote router access.

# Technologies and Configuration Used
    Cisco Packet Tracer simulation

    VLAN and Inter-VLAN Routing (router-on-a-stick)

    Separate wireless networks per department

    Subnetting based on the base network: 192.168.10.0/24

    DHCP server for automatic IP assignment

    SSH and port-security configuration

    OSPF routing protocol

    HTTP and Email server setup

    Network communication testing and DHCP binding verification

# Basic Device Configuration
    Set hostname

    Configure console and enable passwords

    Add MOTD banner

    Disable DNS lookup

    Encrypt all passwords (service password-encryption)

    Configure SSH and port-security (violation mode: shutdown, sticky MAC address)

# Implementation Notes
    Avoid using ip helper-address if the device is also the DHCP server.

    All devices must communicate across VLANs and access internal services (HTTP/Email).

    Let me know if you also want this in .md file format or need help generating subnet tables!








