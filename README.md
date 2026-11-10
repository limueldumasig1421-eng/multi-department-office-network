Multi-Department Office Network

About the Project

This is my fifth networking project using Cisco Packet Tracer. I created a network for a small office with four departments: IT, HR, Finance, and Administration.

The goal was to give each department its own network while allowing devices from different departments to communicate with each other.

Devices Used

1 Cisco 2911 Router

2 Cisco 2960 Switches

8 PCs

4 Printers

1 Server

VLAN Configuration

Department

VLAN

Network

IT

10

192.168.10.0/24

HR

20

192.168.20.0/24

Finance

30

192.168.30.0/24

Administration

40

192.168.40.0/24

What I Configured

Created and assigned VLANs for each department.

Configured trunk connections between the switches and router.

Set up inter-VLAN routing using router-on-a-stick.

Configured a central DHCP server in the IT department.

Created DHCP pools for all four departments.

Configured DHCP relay so the other departments could get IP addresses from the server.

Tested connectivity between PCs in different departments.

What I Learned

I got more practice with VLANs, trunking, DHCP, and inter-VLAN routing. I also encountered some configuration issues during the project, especially with VLAN assignments and DHCP. Troubleshooting those problems helped me understand how the different parts of the network work together.

Files

Multi-Department-Office-Network.pkt – Packet Tracer project file
