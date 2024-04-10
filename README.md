# SYS-265 Final Project Walkthrough
In this project we will be building a network in a virtual enviroment. This is page serves as a layout of our process, each system will have build documentation that is linked here as well as in the Wiki.

## Milestone 1
The first step in getting out network up and running was building the firewall. Build documentation can be found here for specific instructions on how the firewall is configured: [Firewall Docs](https://github.com/AminDaoudi/Final-Project/wiki/fw)

### Workstatios
Once the firewall is configured, we can start adding hosts and services. To make things simple, the next systems we added the the network were workstations. For now, because we don't yet have a domain, they are stand alone systems. Specific instructions for adding workstations to the network can be seen here: 

 * [Workstation One](https://github.com/AminDaoudi/Final-Project/wiki/w1)
 * [Workstation Two](https://github.com/AminDaoudi/Final-Project/wiki/w2)

### Domain Controller
Now it becomes time to configure the domain. I will start with the dc1 system and install everything through powershell. Commands and more can be found here: [First Domain Controller (core)](https://github.com/AminDaoudi/Final-Project/wiki/dc1)

### Management Server
Now that the domain is created, we can start managing servers through the server manager. Instructions for adding the management server to the domain as well as adding a server to be managed can be found here: [Managment Config](https://github.com/AminDaoudi/Final-Project/wiki/mgmt1)

### Redundant Active Directory
Our final system for milestone one will be a second domain controller to allow for more avalibility. We also need to add the workstations to the domain. Instructions can be found below:

 * [Second Domain Controller (gui Through MGMT)](https://github.com/AminDaoudi/Final-Project/wiki/dc2)
 * [Adding A workstation to the domain](https://github.com/AminDaoudi/Final-Project/wiki/mgmt1)
> For the second link look in the bottom of the page for the header that says "Join the Domain"

### Working with DNS
In order to make our systems resolve on LAN, forward and reverse lookup zones should be configured through the DNS manager on the Management machine. Use the following resource for instructions: [Adding forward and reverse zones in DNS Manager](https://github.com/AminDaoudi/Final-Project/wiki/DNS)

