## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 15-10-2026	

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="1916" height="1078" alt="image" src="https://github.com/user-attachments/assets/bfe5b98e-fb0b-4f41-aaf8-05155121bf4f" />


________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0



________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)



<img width="1915" height="1078" alt="image" src="https://github.com/user-attachments/assets/7315e274-b536-43b5-8f28-62b8176f22c8" />






<img width="1912" height="1067" alt="image" src="https://github.com/user-attachments/assets/34858743-8302-4aa4-9fb4-cae800528ad8" />







<img width="1913" height="1076" alt="image" src="https://github.com/user-attachments/assets/8f341e34-edd4-46fe-bbe5-34656c7ed071" />







________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
