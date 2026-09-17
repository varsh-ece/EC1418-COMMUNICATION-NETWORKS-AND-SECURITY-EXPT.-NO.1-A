# EC1418-COMMUNICATION-NETWORKS-AND-SECURITY
# DATE
# EXPT. NO. 1 a) SIMULATION OF NETWORK TOPOLOGIES - STAR

# AIM 
 To simulate a network with Topology, using Cisco Packet Tracer and to verify the connectivity between computer using ICMP.
# EQUIPMENTS REQUIRED

Desktop computer
Cisco Packet Tracer 5.0 Software.


# PROCEDURE
STEP 1: Open a Packet Tracer Software.
STEP 2: Drag a 2950 Switch from tool bar and drop it in work area. STEP 3: Drag a PC Terminal from tool bar and drop it in work area. STEP 4: Repeat the Step:3 for four terminals.
STEP 5: Select Copper straight-through cable from tool bar and connect each PC Terminal with 2950 switch in different ports.
STEP 6: Click on the PC Terminal, Select the fast Ethernet Interface from configuration table and set IP address and Subnet mask.
STEP 7: Repeat the Step:6 for all the PC Terminals.
STEP 8: click on the PC Terminal and Select Terminal from the Desktop tab to verify the connectivity between the PC Terminals using Ping Command.
STEP 9: Select “add simple PDU” from tool bar and place it in source and destination PC Terminals to verify the connectivity



# IP CONNECTIVITY TABLE
| Device | IP Address  | Subnet Mask   | Default Gateway |
| ------ | ----------- | ------------- | --------------- |
| PC0    | 192.168.1.1 | 255.255.255.0 | —               |
| PC1    | 192.168.1.2 | 255.255.255.0 | —               |
| PC2    | 192.168.1.3 | 255.255.255.0 | —               |
| PC3    | 192.168.1.4 | 255.255.255.0 | —               |


# NETWORK DIAGRAM

<img width="617" height="448" alt="image" src="https://github.com/user-attachments/assets/3211f500-6cf4-431a-b74a-7902e6125ecc" />

# OUTPUT
| Parameter | Calculated Value |
|---|---:|
| Delay | 12.5 ms |
| Average Delay | 10.8 ms |
| Throughput | 7.8 Mbps |
| Packet Loss | 2.8% |

# RESULT

Thus the computers in same network are able to communicate with each other and the communication between them were verified.

