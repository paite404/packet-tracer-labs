# packet-tracer-labs
A collection of Cisco Packet Tracer labs demonstrating enterprise network design, VLAN implementation, and network security configurations. Includes step-by-step guides, troubleshooting documentation, and verification procedures

#  Packet Tracer Lab

##  Author
**Giningakpio Stephen Paite Justin**  
BSc Networking and Cyber Security | ISBAT University  
Roll No: 012230331 | Supervisor: Mr. Shameem  

cybergurus@hotmail.com | 📞 +211 925 791 177  

## 📚 Overview
This repository contains practical Cisco Packet Tracer labs demonstrating enterprise network design, configuration, and troubleshooting. Each lab includes step-by-step configuration guides, topology diagrams, and verification procedures.

## 🧪 Lab 1: Basic Enterprise Network
**Objective:** Build a foundational corporate network with department segmentation, automatic IP assignment, and internet connectivity.

### 🔧 Configuration Summary
- **VLAN Implementation:** Sales (VLAN 10), HR (VLAN 20), IT (VLAN 30)
- **Routing:** Router-on-a-Stick configuration for inter-VLAN routing
- **DHCP:** Automatic IP assignment for each department
- **Switching:** Core and access layer switch configuration

### 📐 Topology
                [Router3]
                     |
                     | Gig0/0.10, .20, .30
                     |
                [MAIN-SWITCH]
                (3560-24PS)
                /      |          \
               /       |           \
      [Sales-SW]   [HR-IT-SW]      [Server]
      (2960-24TT)  (2960-24TT)     (Server-PT)
         |  |         |  |
        PC1 PC2      PC3 PC4
       Sales Sales   HR   IT
