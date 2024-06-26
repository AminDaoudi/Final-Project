# SYS-265 Final Project
In this project we will be building a network in a virtual enviroment. This is page serves as a layout of our build process, each system will have build documentation that is linked here as well as in the Wiki.

## Table of Contents
 * [Linux Systems](https://github.com/AminDaoudi/Final-Project/wiki/Linux-Systems)
 * [Windows Systems](https://github.com/AminDaoudi/Final-Project/wiki/Windows-Systems)
 * [Firewall](https://github.com/AminDaoudi/Final-Project/wiki/fw)

 **Network Diagrams**

 * [Milestone 1](Images/milestone1_diagram.png)
 * [Milestone 2](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
 * [Milestone 3](<Images/Working Network Diagram.png>)

 # Working Network Diagram
 ![Working Diagram](image.png)
 > Created using plantuml -> [Working Diagram](Working_Network_Diagram.plantuml)
 
 ## Role and Service Information
Summary: 
```
 * Firewall             -> 1x PFSense Firewall
 * Domain Controllers   -> 2x Domain Controllers
 * Workstations         -> 2x Workstations (Domain Joined)
 * Management Systems   -> 1x Windows Server Manager, 1x Linux Server Manager
 * DHCP systems         -> 2x DHCP Servers 
 * File Systems         -> 2x Windows DFS
 * Docker               -> 1x Docker System for Wiki deployment
 ```
> **All systems can be controlled via Ansible from MGMT02 except for the following: [wks01](https://github.com/AminDaoudi/Final-Project/wiki/w1), [wks02](https://github.com/AminDaoudi/Final-Project/wiki/w2), and [fw01](https://github.com/AminDaoudi/Final-Project/wiki/fw)**

 ## RVTM and Deliverables
  * RVTM can be found here: [RVTM](https://github.com/AminDaoudi/Final-Project/wiki/RVTM)
