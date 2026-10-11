# Packet Tracer Labs - Enterprise Network Design

A collection of Cisco Packet Tracer labs demonstrating enterprise network design, VLAN implementation, and network security configurations. Includes step-by-step guides, troubleshooting documentation, and verification procedures for professional network engineers.

## Author

**Giningakpio Stephen Paite Justin**  
Network Security Engineer | IT and Operations Manager  
Cybersecurity Professional | Enterprise Network Design Specialist

📧 engineerstephenpaite@gmail.com | 🔗 [LinkedIn](https://linkedin.com/in/giningakpio) | 🐙 [GitHub](https://github.com/paite404)

---

## 📚 Overview

This repository contains practical Cisco Packet Tracer labs demonstrating enterprise network design, configuration, and troubleshooting. Each lab includes step-by-step configuration guides, topology diagrams, and verification procedures for security professionals and network engineers.

These labs cover real-world scenarios for:
- Enterprise network segmentation
- VLAN design and implementation
- Routing protocols and inter-VLAN communication
- Network security and access control
- DHCP and IP address management

---

## 🧪 Lab 1: Basic Enterprise Network

**Objective:** Build a foundational corporate network with department segmentation, automatic IP assignment, and internet connectivity.

### 🔧 Configuration Summary
- **VLAN Implementation:** Sales (VLAN 10), HR (VLAN 20), IT (VLAN 30)
- **Routing:** Router-on-a-Stick configuration for inter-VLAN routing
- **DHCP:** Automatic IP assignment for each department
- **Switching:** Core and access layer switch configuration
- **Security:** VLAN segmentation and access control lists

### 📐 Topology

```
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
```

---

## 🛠️ Configuration Details

### VLAN Configuration
- Sales Department: VLAN 10 (192.168.10.0/24)
- HR Department: VLAN 20 (192.168.20.0/24)
- IT Department: VLAN 30 (192.168.30.0/24)

### Router Configuration
- Router-on-a-Stick for routing between VLANs
- DHCP server configuration for each VLAN
- Default route to simulated internet

### Security Features
- Native VLAN configuration
- Access Control Lists (ACLs)
- Port security on access switches
- VLAN trunking protocols

---

## 📋 Skills Demonstrated

✅ Cisco router and switch configuration  
✅ VLAN segmentation and design  
✅ Dynamic routing (OSPF)  
✅ DHCP configuration and management  
✅ Network security best practices  
✅ Troubleshooting and verification  
✅ Documentation and topology design  

---

## 🎯 Use Cases

- **Network Engineers:** Learn enterprise network design
- **Cybersecurity Professionals:** Understand network segmentation and security
- **IT Managers:** Design secure network infrastructure
- **Students:** Build hands-on networking experience

---

## 📖 How to Use

1. Open Cisco Packet Tracer
2. Load the .pkt file from this repository
3. Follow the step-by-step configuration guide
4. Verify connectivity using ping and tracert commands
5. Test VLAN segmentation and routing

---

## 🔒 Security Considerations

These labs demonstrate security best practices including:
- Network segmentation via VLANs
- Access control policies
- Least privilege principles
- Monitoring and logging

---

## 📞 Contact & Professional Links

- **Email:** engineerstephenpaite@gmail.com
- **LinkedIn:** https://linkedin.com/in/giningakpio
- **GitHub:** https://github.com/paite404
- **Location:** Juba, South Sudan

---

## 📝 License

These labs are provided for educational and authorized security training purposes only.

---

**Security is not a destination — it is a continuous process of vigilance, improvement, and action.**
