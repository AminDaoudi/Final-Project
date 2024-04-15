# SYS-265 Final Project
In this project we will be building a network in a virtual enviroment. This is page serves as a layout of our process, each system will have build documentation that is linked here as well as in the Wiki.

## Table of Contents
 * [Linux Systems](https://github.com/AminDaoudi/Final-Project/wiki/Linux-Systems)
 * [Windows Systems](https://github.com/AminDaoudi/Final-Project/wiki/Windows-Systems)
 * [Firewall](https://github.com/AminDaoudi/Final-Project/wiki/fw)

 # Working Network Diagram
 ![Working Diagram](<Images/Working Network Diagram.png>)
 
 ## Roles and Services
 Each system has a unique role in the environment that will be outlined below.

 ### Firewall 
  * The firewall is running PFSense and will act as the connection between the LAN and WAN networks. 

 ### Domain Controllers
  * Domain Controllers manage Active Directory services, these systems are redundant so if one fails, the other can pick up where it left off. 

 ### Workstations
  * Workstations are the windows clients of the network, they are domain joined and can be managed through active directory (WKS1, WKS2).

 ### Management Systems
  * Both the DC1 and DC2 are running windows server core. MGMT01 offers a GUI solution for managing windows systems on the network through Windows Server Manager GUI.
  * MGMT02 picks up the role of managing Linux systems on the network.

 ### DHCP Servers
 * This network deploys two DHCP servers to manage DHCP services. DHCP01 is the main dhcp server while DHCP2 is the secondary server. In the event of an outage, either server can run without connection to the other.

 ### File Systems
  * More on this section in milestone 3

 ### 