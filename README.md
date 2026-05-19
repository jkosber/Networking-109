# Networking-109 — Introduction to Networking (CCNA Part 1)

Coursework completing the first track of the CCNA pathway through **Cisco Networking Academy: Networking Basics + Introduction to Networks**, taken as **Ivy Tech NETI 109** at Ivy Tech Kokomo in Fall 2025. The repository captures hands-on lab work with Cisco IOS on physical routers and switches, Packet Tracer topology design and configuration, written labs, and weekly class notes.

## Topics covered

- TCP/IP and OSI network models
- Switching and end-device fundamentals
- Network protocols and reference models
- Physical layer — cabling, signaling
- Ethernet switching
- Address resolution (ARP)
- Basic Cisco router configuration via IOS CLI
- IPv4 and IPv6 addressing and subnetting
- ICMP behavior and troubleshooting
- Transport-layer protocols (TCP, UDP)
- Application-layer protocols (HTTP, DNS, DHCP, etc.)
- Network security fundamentals
- Designing and building a small network

## Tools and technologies

- **Cisco IOS** — hands-on configuration on physical lab routers and switches in the Ivy Tech Kokomo networking lab
- **Cisco Packet Tracer** — multi-device topology design and configuration (`.pka`, `.pkt`, `.pksz` files throughout the repo)
- **Wireshark** — used in Module 3 to view live network traffic
- Standard networking utilities (`ping`, `traceroute`, etc.)

## Certifications earned

- Cisco Networking Academy: **Networking Basics** — completion certificate ([PDF in repo root](Networking-Basics-certificate-JKosberg.pdf))
- Cisco Networking Academy: **Introduction to Networks** (CCNA v7 Module 1) — completion certificate ([PDF in repo root](CCNA-Introduction-to-Networks-certificate-JKosberg.pdf))

## Repository layout

```
Networking109/
  Module-01-NetworkingToday/             Network value, components, security baseline; first Packet Tracer activity
  Module-02-BasicSwitchAndEndDevice/     Initial switch / end-device configuration in Packet Tracer
  Module-03-ProtocolsandModels/          Networking standards research; first Wireshark capture
  Module-04-PhysicalLayer/               Cabling, media, signaling labs
  Module-07-EthernetSwitching/           Ethernet frame structure and switching behavior
  Module-09-AddressResolution/           ARP; module-quiz score capture
  Module-10-BasicRouterConfiguration/    Initial Cisco IOS router configuration
  Module-11-IPv4Addressing/              IPv4 subnetting and addressing labs
  Module-12-IPv6Addressing/              IPv6 addressing, identification, configuration
  Module-13-ICMP/                        ICMP behavior labs (echo, unreachable)
  Module-14-TransportLayer/              TCP / UDP transport behavior
  Module-15-ApplicationLayer/            DNS resolution observation lab
  Module-16-NetworkSecurityFundamentals/ Threat research lab + Packet Tracer security scenarios
  Module-17-BuildASmallNetwork/          End-to-end small-network design, build, and verification
  NetworkingActivities/                  Standalone Packet Tracer activities and module-quiz files
  NetworkingNotes/                       Weekly class notes (Aug 27 – Oct 15, 2025)
CCNA-Introduction-to-Networks-certificate-JKosberg.pdf
Networking-Basics-certificate-JKosberg.pdf
```

> The Cisco CCNA v7 *Introduction to Networks* curriculum contains seventeen modules. The repo includes the labs and Packet Tracer files that were submitted for credit — Modules 05, 06, and 08 were lecture-only weeks with no submission artifacts, which is why their folders are absent.

## Module guide

- **Module 1 — Networking Today.** Why networks matter, components, and reliability; first Packet Tracer activity exploring logical vs physical views.
- **Module 2 — Basic Switch and End-Device Configuration.** Initial switch CLI and end-device labs in Packet Tracer (`2.3.7`, `2.5.5`, `2.7.6`, `2.9.1`).
- **Module 3 — Protocols and Models.** Research lab on networking standards; first Wireshark capture lab to view network traffic.
- **Module 4 — Physical Layer.** Cabling and media labs (`4.6.5`, `4.7.1`, `4.7.2`).
- **Module 7 — Ethernet Switching.** Frame structure and switching-behavior labs (`7.1.6`, `7.2.7`, `7.3.7`).
- **Module 9 — Address Resolution.** ARP labs and a module-quiz score capture.
- **Module 10 — Basic Router Configuration.** First Cisco IOS router-configuration labs (`10.1.4`, `10.3.4`, `10.3.5`, `10.4.3`).
- **Module 11 — IPv4 Addressing.** Subnetting and addressing labs (`11.5.5`, `11.6.6`, `11.7.5`, `11.9.3`, `11.10.1`).
- **Module 12 — IPv6 Addressing.** Address identification and configuration labs (`12.4.5`, `12.6.6`, `12.7.4`, `12.9.1`).
- **Module 13 — ICMP.** Echo / unreachable / reachability behavior labs.
- **Module 14 — Transport Layer.** TCP vs UDP behavior lab.
- **Module 15 — Application Layer.** DNS-resolution observation lab.
- **Module 16 — Network Security Fundamentals.** Research lab on network security threats plus Packet Tracer scenarios.
- **Module 17 — Build a Small Network.** Capstone module — design, build, and verify a small multi-device network end-to-end.
- **NetworkingActivities/** — Standalone Packet Tracer activities (MAC and IP address identification, simple network creation, client interaction, checkpoint quizzes).
- **NetworkingNotes/** — Seven weekly class-notes files spanning Aug 27 – Oct 15, 2025.

## Status

Course completed Fall 2025 with grade **A** (Dean's List). Both Cisco Networking Academy completion certificates earned. **Pursuing the full CCNA certification next.**

## Related

- [CyberOps-115](https://github.com/jkosber/CyberOps-115) — Cisco CyberOps Associate coursework
- [CSIA-210-Network-Protocol-Analysis](https://github.com/jkosber/CSIA-210-Network-Protocol-Analysis) — deeper packet-level work building on these foundations
- [IntroToCybersecurity-105](https://github.com/jkosber/IntroToCybersecurity-105) — cybersecurity fundamentals context
