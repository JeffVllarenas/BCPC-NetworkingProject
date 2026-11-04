# BCPC Network Infrastructure Project

## 📌 Project Overview

The **BCPC Network Infrastructure Project** is a network design and infrastructure simulation developed using Cisco Packet Tracer.

This project demonstrates the implementation of network routing, centralized server services, network monitoring, time synchronization, web hosting, centralized authentication, and secure remote device administration.

The infrastructure is designed to provide reliable network communication, centralized management, and improved network security.

## 🎯 Project Objectives

- Design and simulate a functional network infrastructure.
- Implement static routing between different networks.
- Configure centralized network services.
- Deploy HTTP, Syslog, and NTP servers.
- Implement RADIUS and TACACS+ authentication.
- Configure SSH for secure remote administration.
- Demonstrate network connectivity, monitoring, and security.

## 🏗️ Network Infrastructure and Services

### 1. Static Routing

Implements manually configured routing entries to enable communication between different networks.

**Key Functions:**
- Configure static routes on routers.
- Establish communication between remote networks.
- Define destination networks and next-hop addresses.
- Verify routing paths and end-to-end connectivity.

### 2. HTTP Server (Web Server)

Provides web hosting services within the network, allowing users to access hosted web pages through a browser.

**Key Functions:**
- Host an internal website.
- Provide web-based access to network resources.
- Demonstrate HTTP client-server communication.

### 3. Syslog Server (Network Logging)

Provides centralized logging by collecting system messages and event notifications from network devices.

**Key Functions:**
- Monitor network device activities.
- Collect system logs and event messages.
- Assist in troubleshooting.
- Maintain centralized network event records.

### 4. NTP Server (Network Time Protocol)

Provides centralized time synchronization for network devices.

**Key Functions:**
- Synchronize device clocks.
- Maintain consistent timestamps.
- Improve accuracy of network logs.
- Support network monitoring and troubleshooting.

### 5. RADIUS Server (Remote Authentication Dial-In User Service)

Provides centralized Authentication, Authorization, and Accounting (AAA) services for supported network access devices.

**Key Functions:**
- Centralized user authentication.
- Manage network access credentials.
- Support centralized access control.
- Demonstrate AAA implementation.

### 6. TACACS+ Server (Terminal Access Controller Access-Control System Plus)

Provides centralized AAA services, particularly for administrative access to network devices.

**Key Functions:**
- Centralized administrator authentication.
- Support authorization of administrative commands.
- Improve accountability for network administration.
- Demonstrate centralized device management.

### 7. SSH (Secure Shell)

Implements SSH to provide encrypted remote access to network devices, allowing administrators to securely manage and configure routers and switches.

**Key Functions:**
- Enable secure remote access to routers and switches.
- Configure SSH for encrypted administrative sessions.
- Generate RSA cryptographic keys.
- Configure local usernames and passwords.
- Restrict remote device management through SSH.

**Purpose:**

SSH provides a more secure alternative to Telnet by encrypting communication between administrators and network devices, protecting login credentials and administrative sessions.

## 🛠️ Technologies and Tools Used

| Technology | Purpose |
|---|---|
| Cisco Packet Tracer | Network simulation |
| Static Routing | Inter-network communication |
| SSH | Secure remote administration |
| HTTP | Web hosting |
| Syslog | Centralized logging |
| NTP | Time synchronization |
| RADIUS | Centralized authentication |
| TACACS+ | Administrative AAA |
| IPv4 | Network addressing |
| TCP/IP | Network communication |

## 🖥️ Network Architecture

The simulated infrastructure consists of interconnected routers, switches, servers, and client devices.

Static routing enables communication between different network segments, while dedicated servers provide centralized network services.

SSH provides secure remote administration, and RADIUS and TACACS+ demonstrate centralized authentication and authorization.

### Network Topology

![BCPC Network Topology](topology.png)

## 📂 Project Files

| File | Description |
|---|---|
| `BCPCNetwork.pkt` | Cisco Packet Tracer network simulation |
| `topology.png` | Network topology diagram |
| `README.md` | Project documentation |

## 🧪 Testing and Verification

The following tests can be performed to verify network functionality:

- **Static Routing:** Verify communication between different networks using ping and routing table inspection.
- **HTTP:** Access the hosted website using a client web browser.
- **Syslog:** Verify that network device messages are received by the Syslog server.
- **NTP:** Verify time synchronization on supported network devices.
- **RADIUS:** Test centralized authentication on supported devices.
- **TACACS+:** Test administrator authentication and command authorization where supported.
- **SSH:** Verify encrypted remote access to routers and switches.

## 🔐 Network Security and Management

The project demonstrates centralized authentication, secure remote administration, and network monitoring.

Security and management implementations include:

- SSH for encrypted remote device management.
- RADIUS for centralized authentication.
- TACACS+ for centralized administrative AAA.
- Syslog for network event monitoring.
- NTP for consistent timestamps.

## 🚀 How to Access the Project

1. Download or clone this GitHub repository.
2. Download the `BCPCNetwork.pkt` file.
3. Open Cisco Packet Tracer.
4. Navigate to **File → Open**.
5. Select the downloaded `.pkt` file.
6. Explore the network topology and server configurations.

## 📚 Learning Outcomes

Through this project, the following networking concepts are demonstrated:

- Network infrastructure design.
- Static routing configuration.
- Server deployment and configuration.
- Centralized authentication and authorization.
- Network monitoring and logging.
- Network time synchronization.
- Secure remote device administration.
- Client-server communication.
- Network troubleshooting and administration.

## 👨‍💻 Project Information

**Project Name:** BCPC Network Infrastructure Project

**Platform:** Cisco Packet Tracer

**Category:** Computer Networking / Network Administration

**Project Type:** Network Design and Infrastructure Simulation

---

*This project was developed for educational purposes to demonstrate practical networking, routing, server infrastructure, centralized authentication, and network management concepts.*
