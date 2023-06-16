# Network-project-using-packet-tracer
configuring a corporate network for a new bank branch
-Divided the 10.1.32.0/22 network into Six subnets.
Subnet0 10.1.32.0/25
Subnet1 10.1.32.128/25
Subnet2 10.1.33.0/24
Subnet3 10.1.34.0/26
Subnet4 10.1.34.64/26
Subnet5 10.1.34.128/26

 1-Network Topology:
The network infrastructure consists of multiple switches interconnected in a hierarchical manner to establish a reliable and scalable network. The network topology is provided in a screenshot


2- Switch Configuration:
Each switch within the network has been configured to support VLAN functionality and ensure efficient traffic routing. The configuration includes the following aspects:
a. VLAN Trunking:
VLAN trunking protocols, such as IEEE 802.1Q, have been implemented to enable the transmission of multiple VLAN traffic over a single physical link between switches.
Trunk ports have been configured to carry traffic from multiple VLANs.
b. VLAN Access Ports:
Access ports have been configured on switches to connect devices directly associated with a specific VLAN, ensuring traffic segregation and security.
c. VLAN Routing:
Inter-VLAN routing has been implemented to allow communication between different VLANs when required. This enables collaboration and data exchange between departments, while maintaining appropriate security boundaries.


3-Switch and Router Security Configuration:
All network devices, including routers and switches, have been configured with enhanced security settings. The following measures have been implemented:
a. Device Access:
Username: Admin
Password: heisenberg
Access to the network devices is restricted to authorized personnel using the provided login credentials.
b. Password Encryption:
All passwords configured on the network devices are encrypted, ensuring an additional layer of security.
c. SSH Version 2:
Secure Shell (SSH) version 2 is used for remote management and configuration of the routers. This cryptographic network protocol provides a secure and encrypted communication channel between authorized users and the routers. [username]:Admin [password]:heisenberg
 
     Subnet and VLAN Configuration:
The network is divided into three different subnets, each corresponding to a separate switch. Within each subnet, VLANs have been created to accommodate various departments. Additionally, the remaining switch interfaces are assigned to a guest VLAN, which is connected to native trunk ports. The following subnets and VLANs have been configured:
Subnet 0:
VLANs:
10 Accounting VLAN
20 Employee VLAN
30 Guest VLAN
Subnet 2:
VLANs:
10 Human Resources VLAN
20 Guest VLAN
Subnet 3:
VLANs:
10 CEO VLAN
20 Guest VLAN

5-All switches within each subnet are connected to a router, and the three routers are interconnected to enable communication between devices in different subnets. This allows devices from different subnets to send packets to each other, facilitating seamless communication between departments. For example, a device in Subnet 1 can ping a device in Subnet 2.

6-User Account Creation:
A user account has been created with the following login credentials:
Username: Admin
Password: heisenberg
This account grants administrative access to the network devices and should only be used by authorized personnel.


Hope this brief report was helpfull :)




