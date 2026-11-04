# BCPC Network Infrastructure Project

## 📌 Project Overview

The **BCPC Network Infrastructure Project** is a network design and infrastructure simulation developed using Cisco Packet Tracer.

The project demonstrates the implementation of network routing, centralized server services, network monitoring, time synchronization, web hosting, and centralized authentication to establish a manageable and functional network environment.

## 🎯 Project Objectives

- Design and simulate a functional network infrastructure.
- Implement static routing between different networks.
- Configure centralized network services.
- Deploy HTTP, Syslog, and NTP services.
- Implement RADIUS and TACACS+ authentication.
- Demonstrate network connectivity, administration, and security.

## 🏗️ Network Infrastructure and Services

### 1. Static Routing
Implements manually configured routing entries to enable communication between different networks.

**Key Functions:**
- Configure static routes on routers.
- Establish communication between remote networks.
- Define destination networks and next-hop addresses.
- Verify routing paths and end-to-end connectivity.

### 2. HTTP Server (Web Server)
Provides web hosting services within the network.

**Key Functions:**
- Host an internal website.
- Allow users to access web pages through browsers.
- Demonstrate HTTP client-server communication.

### 3. Syslog Server (Network Logging)
Collects system messages and event notifications from network devices.

**Key Functions:**
- Centralized network logging.
- Monitor device activities and events.
- Support troubleshooting and network administration.

### 4. NTP Server (Network Time Protocol)
Provides centralized time synchronization.

**Key Functions:**
- Synchronize network device clocks.
- Maintain consistent timestamps.
- Improve accuracy of network logs and troubleshooting.

### 5. RADIUS Server (Remote Authentication Dial-In User Service)
Provides centralized Authentication, Authorization, and Accounting (AAA).

**Key Functions:**
- Centralized user authentication.
- Network access control.
- Credential management for supported devices.

### 6. TACACS+ Server (Terminal Access Controller Access-Control System Plus)
Provides centralized AAA services for network device administration.

**Key Functions:**
- Centralized administrator authentication.
- Command authorization where supported.
- Administrative access control.
- Improved accountability for network management.

## 🛠️ Technologies and Tools Used

| Technology | Purpose |
|---|---|
| Cisco Packet Tracer | Network simulation |
| Static Routing | Inter-network communication |
| HTTP | Web hosting |
| Syslog | Centralized logging |
| NTP | Time synchronization |
| RADIUS | Centralized AAA |
| TACACS+ | Administrative AAA |
| IPv4 | Network addressing |
| TCP/IP | Network communication |

## 🖥️ Network Architecture

The simulated infrastructure consists of interconnected routers, switches, servers, and client devices.

Static routing enables communication between different network segments, while dedicated servers provide centralized network services.

### Network Topology

![BCPC Network Topology](topology.png)

## 📂 Project Files

| File | Description |
|---|---|
| `BCPCNetwork.pkt` | Cisco Packet Tracer network simulation |
| `topology.png` | Network topology diagram |
| `README.md` | Project documentation |

## 🧪 Testing and Verification

The following tests are used to verify network functionality:

- **Static Routing:** Verify communication between different networks using ping and routing table inspection.
- **HTTP:** Access the hosted website using a client web browser.
- **Syslog:** Verify that network device logs are received by the Syslog server.
- **NTP:** Verify time synchronization on supported network devices.
- **RADIUS:** Test centralized user authentication.
- **TACACS+:** Test administrator authentication and command authorization where supported.

## 🔐 Network Security and Management

The project demonstrates centralized authentication, network monitoring, and infrastructure management through RADIUS, TACACS+, Syslog, and NTP services.

Static routing provides controlled communication paths between network segments.

## 🚀 How to Access the Project

1. Download or clone this repository.
2. Download `BCPCNetwork.pkt`.
3. Open Cisco Packet Tracer.
4. Navigate to File → Open.
5. Select the downloaded `.pkt` file.
6. Explore the network topology and server configurations.

## 📚 Learning Outcomes

This project demonstrates practical knowledge of:

- Network infrastructure design.
- Static routing configuration.
- Server deployment and management.
- Centralized authentication and authorization.
- Network monitoring and logging.
- Network time synchronization.
- Client-server communication.
- Network troubleshooting and administration.

## 👨‍💻 Project Information

**Project Name:** BCPC Network Infrastructure Project

**Platform:** Cisco Packet Tracer

**Category:** Computer Networking / Network Administration

**Project Type:** Network Design and Infrastructure Simulation

---

*Developed for educational purposes to demonstrate practical networking, routing, server infrastructure, centralized authentication, and network management concepts.*
