# <div style="text-align: center;">CompTIA Network+ (N10-009) Notes</div>

<!-- Domain 1 -->
## Domain 1.0 – Networking Concepts (23%)

### 1.1 Explain concepts related to the Open Systems Interconnection (OSI) reference model

**OSI Model Layers**

**Layer 1** – Physical: Bits, cables, signals, hubs
**Layer 2** – Data Link: Frames, MAC addresses, switches
**Layer 3** – Network: Packets, IP addressing, routers
**Layer 4** – Transport: Segments, TCP/UDP
**Layer 5** – Session: Session management
**Layer 6** – Presentation: Data formatting, encryption
**Layer 7** – Application: User-facing applications

**TCP/IP Model** (simplified version used in practice)
- Application, Transport, Internet, Network Access

### 1.2 Compare and contrast networking appliances, applications, and functions

**Common Network Devices**
- Router — Connects networks, makes routing decisions
- Switch — Connects devices within a LAN
- Firewall — Security barrier
- Access Point — Wireless connectivity
- Load Balancer — Distributes traffic
- Proxy Server — Intermediary for requests

<!-- Domain 2 -->
## Domain 2.0 – Network Implementation (20%)

### 2.1 Given a scenario, install and configure networking components

**Cabling & Connectors**
- Twisted Pair (Cat5e, Cat6, Cat6a)
- Fiber Optic (Single-mode vs Multi-mode)
- Coaxial (older cable internet)
- Connectors: RJ-45, LC, SC, ST

**Network Devices**
- **Routers** — Connect different networks (Layer 3 - Network)
  - Routing based on IP addresses
  - Connects different networks together
- **Switches** — Connect devices within a LAN (Layer 2 - Data Link)
  - MAC addresses to forward frames
  - Creates separate collision domains
- **Access Points** — Wireless connectivity (Layer 2 - Data Link)
  - Provides wireless connectivity
  - Bridges wired and wireless networks
- **Firewalls** — Security (Layers 3/4 - Network/Transport)
  - Filters traffic based on rules
  - Can operate at higher layers depending on type
- **Load Balancers** — Distribute traffic (Layers 4-7 - Transport to Application)
  - Distributes traffic across servers
- Hub - Broadcasts all incoming traffic to all outbound connections (Layer 1 - Physical)
  - Simple repeater (mostly obsolete)
- NIC - Network Interface Card (Layers 1 & 2)
  - Physical connection and MAC addressing

### 2.2 Compare and contrast routing technologies

**Static vs Dynamic Routing**
- **Static Routing** — Manual route configuration
- **Dynamic Routing** — Protocols automatically update routes

**Common Routing Protocols**
- **OSPF** — Link-state, fast convergence
- **EIGRP** — Hybrid (Cisco)
- **BGP** — Path vector (used on the internet)

### 2.3 Given a scenario, configure and deploy common Ethernet switching features

**Switching Concepts**
- MAC address learning
- VLANs (Virtual Local Area Networks)
- Trunking (802.1Q)
- Spanning Tree Protocol (STP) — prevents loops

### 2.4 Given a scenario, install and configure wireless technologies and appropriate security protocols

**Wi-Fi Standards**
- 802.11ac (Wi-Fi 5)
- 802.11ax (Wi-Fi 6)
- Frequency bands: 2.4 GHz (range) vs 5 GHz (speed)

**Wireless Security**
- WPA3 (recommended)
- WPA2 (still common)
- WEP (obsolete)

<!-- Domain 3 -->
## Domain 3.0 – Network Operations (19%)

### 3.1 Given a scenario, use network troubleshooting tools and commands
**Common CLI Tools**
- ping — Test connectivity
- tracert / traceroute — Path to destination
- ipconfig / ifconfig — IP configuration
- nslookup — DNS lookup
- netstat — Active connections
- arp — MAC address table
- route — Routing table

### 3.2 Explain the purpose of organizational documents and policies

**Key Documents**
- Acceptable Use Policy (AUP)
- Network topology diagrams
- Asset inventory
- Change management documentation
- Incident response plan
- Disaster recovery plan

### 3.3 Explain high availability and disaster recovery concepts

**High Availability**
- Redundancy
- Failover
- Load balancing
- Clustering

**Disaster Recovery**
- Recovery Time Objective (RTO)
- Recovery Point Objective (RPO)
- Backup types (full, incremental, differential)
- Offsite backups
- Cloud backups

### 3.4 Given a scenario, use appropriate network monitoring tools

**Monitoring Tools**
- SNMP (Simple Network Management Protocol)
- SIEM (Security Information and Event Management)
- Syslog
- NetFlow


<!-- Domain 4 -->
## Domain 4.0 – Network Security (14%)

### 4.1 Explain common security concepts

**Core Security Concepts**
- **Confidentiality** — Encryption
- **Integrity** — Hashing, digital signatures
- **Availability** — Redundancy, backups
- **Non-repudiation** — Digital signatures, logging

**Threats**
- Malware, social engineering, DoS, MITM, zero-day attacks

### 4.2 Compare and contrast common types of attacks

**Common Attacks**
- **Social Engineering** — Phishing, vishing, tailgating
- **Password Attacks** — Brute force, dictionary
- **Network Attacks** — DDoS, evil twin, ARP poisoning
- **Wireless Attacks** — Rogue AP, WPS attacks

### 4.3 Given a scenario, apply network security features

**Security Technologies**
- Firewalls (stateful, stateless)
- VPNs (IPSec, SSL/TLS)
- NAC (Network Access Control)
- Port security
- 802.1X authentication

### 4.4 Given a scenario, implement secure network designs

**Network Segmentation**
- VLANs
- DMZ (Demilitarized Zone)
- Honeypots

**Wireless Security**
- WPA3
- MAC filtering
- Guest networks

<!-- Domain 5 -->
## Domain 5.0 – Network Troubleshooting (24%)

### 5.1 Given a scenario, use the appropriate troubleshooting methodology

**CompTIA Troubleshooting Methodology**
1. Identify the problem
2. Establish a theory of probable cause
3. Test the theory
4. Establish a plan of action and implement the solution
5. Verify full system functionality
6. Document findings, actions, and outcomes

### 5.2 Given a scenario, troubleshoot common cable and connectivity issues

**Common Cable Issues**
- Incorrect pinout (straight-through vs crossover)
- Bad connectors
- Cable length exceeded
- Interference (EMI)
- Open/short circuits

**Connectivity Issues**
- No link light
- Intermittent connectivity
- Slow speeds

### 5.3 Given a scenario, troubleshoot common network issues

**Common Network Problems**
- IP configuration issues
- DNS resolution failures
- DHCP failures
- Routing problems
- VLAN misconfiguration
- Broadcast storms

### 5.4 Given a scenario, troubleshoot common performance issues

**Performance Issues**
- High latency
- Jitter
- Packet loss
- High bandwidth usage
- Collisions / Broadcast storms

### 5.5 Given a scenario, use appropriate tools to resolve network issues

**Troubleshooting Tools**
- Cable tester
- Crimper
- Tone generator & probe
- OTDR (fiber)
- Wi-Fi analyzer
- Protocol analyzer (Wireshark)

## Website
[View website](https://frankwjohns13.github.io/)




