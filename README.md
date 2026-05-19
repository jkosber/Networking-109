# Networking-109 — Networking I (NETI 109)

Coursework for **Ivy Tech NETI 109: Networking I**, taken Fall 2025 at Ivy Tech Kokomo. NETI 109 is the first of three courses in the Cisco CCNAv7 curriculum and consists of two Cisco Networking Academy tracks taken back-to-back:

1. **Networking Basics** — 17 modules, taught Aug 27 – Sep 21 (completion certificate earned).
2. **Introduction to Networks (ITN, CCNA v7 Module 1)** — 17 modules, taught Sep 22 – Dec 10 (completion certificate earned).

The course mixed Packet Tracer simulations with hands-on labs on the physical Cisco router and switch gear in the Ivy Tech Kokomo networking lab, and was assessed with module checkpoint exams, two final exams, and a final practical skills assessment on real equipment. This repository archives the ITN module submissions, the in-class Packet Tracer artifacts, weekly class notes, and both completion certificates.

## Course information

| Field            | Detail                                                                |
| :--------------- | :-------------------------------------------------------------------- |
| Course number    | NETI 109                                                              |
| Course title     | Networking I                                                          |
| School / program | Information Technology — Network Infrastructure                       |
| Credit hours     | 3                                                                     |
| Contact hours    | Lecture: 1.5                                                          |
| Prerequisites    | College-level English readiness; TECH / QUANT / STEM Math Path Ready  |
| Term             | Fall 2025 (Aug 27 – Dec 19, 2025)                                     |
| Final grade      | A (Dean's List term)                                                  |

## Catalog description

> Networking I is the first of three courses in the Cisco CCNAv7 curriculum. This course includes activities using Packet Tracer, hands-on lab work, and a wide array of assessment types and tools. The content covers the architecture, structure, functions and components of the Internet and other computer networks. Students achieve a basic understanding of how networks operate and how to build simple local area networks (LAN), perform basic configurations for routers and switches, and implement Internet Protocol (IP).

## Course learning objectives

Upon successful completion of NETI 109 the student is expected to:

1. Configure switches and end devices to provide access to local and remote network resources.
2. Explain how physical and data link layer protocols support the operation of Ethernet in a switched network.
3. Configure routers to enable end-to-end connectivity between remote devices.
4. Create IPv4 and IPv6 addressing schemes and verify network connectivity between devices.
5. Explain how the upper layers of the OSI model support network applications.
6. Configure a small network with security best practices.
7. Troubleshoot connectivity in a small network.

## Topical content

- Cisco IOS
- Protocols
- Integrity and Availability
- Routing
- IP Addressing
- Security
- Local Area Networks (LAN)
- TCP/IP Model
- Network Operating Systems
- Standards and the OSI Model
- Network Hardware
- Transmission Basics and Networking Media
- Troubleshooting

## Tools and technologies

- **Cisco IOS** — hands-on configuration on the physical Cisco router and switch lab gear at Ivy Tech Kokomo.
- **Cisco Packet Tracer** — multi-device topology design and configuration; `.pka`, `.pkt`, and `.pksz` files throughout the repo are Packet Tracer artifacts.
- **Wireshark** — used in Module 3 to view live network traffic.
- Standard networking utilities — `ping`, `traceroute`, `ipconfig` / `ifconfig`.

## Certifications earned

- Cisco Networking Academy — **Networking Basics** ([completion certificate PDF](Networking-Basics-certificate-JKosberg.pdf))
- Cisco Networking Academy — **Introduction to Networks** (CCNA v7 Module 1) ([completion certificate PDF](CCNA-Introduction-to-Networks-certificate-JKosberg.pdf))

## Major assessments

- Checkpoint exams across each module group (Network Access; Internet Protocol; Communication Between Networks; Protocols for Specific Tasks; Basic Network Connectivity; Ethernet Concepts; Communicating Between Networks; IP Addressing; Network Application Communications; Building and Securing a Small Network).
- **Networking Basics Final Exam** (Sep 21).
- **CCNA: Introduction to Networks Course Final Exam** (Dec 10).
- **ITN Practice PT Skills Assessment (PTSA)** (Dec 19) — Packet Tracer practical.
- **ITN Final Skills Exam (Equipment)** (Dec 17) — practical on real Cisco gear in the lab.

## Repository layout

```
Networking109/
  Module-01-NetworkingToday/             Network value, components, security baseline; first Packet Tracer activity
  Module-02-BasicSwitchAndEndDevice/     Initial switch and end-device configuration in Packet Tracer
  Module-03-ProtocolsandModels/          Networking-standards research lab; first Wireshark capture
  Module-04-PhysicalLayer/               Cabling, media, signaling labs
  Module-07-EthernetSwitching/           Ethernet frame structure and switching behavior
  Module-09-AddressResolution/           ARP labs + module-quiz score capture
  Module-10-BasicRouterConfiguration/    Initial Cisco IOS router configuration + in-class equipment build (10.4.3)
  Module-11-IPv4Addressing/              IPv4 subnetting and addressing labs
  Module-12-IPv6Addressing/              IPv6 addressing, identification, configuration
  Module-13-ICMP/                        ICMP behavior labs
  Module-14-TransportLayer/              TCP / UDP transport behavior
  Module-15-ApplicationLayer/            DNS resolution observation lab
  Module-16-NetworkSecurityFundamentals/ Threat-research lab + Packet Tracer security scenarios
  Module-17-BuildASmallNetwork/          End-to-end small-network design, build, and verification (incl. in-class equipment lab)
  NetworkingActivities/                  Standalone Packet Tracer activities and module-quiz files
  NetworkingNotes/                       Seven weekly class-notes files (Aug 27 – Oct 15, 2025)
CCNA-Introduction-to-Networks-certificate-JKosberg.pdf
Networking-Basics-certificate-JKosberg.pdf
```

> Modules 05 (Number Systems), 06 (Data Link Layer), and 08 (Network Layer) had upload assignments in the official course schedule but are not currently archived in this repository — only the modules with submitted artifacts are stored here. The Networking Basics track (the first 17 modules of the course) is represented through the completion certificate and weekly class notes rather than per-module folders; the ITN track was where module-by-module artifacts were uploaded.

## Module guide (Introduction to Networks track)

- **Module 1 — Networking Today.** Why networks matter, components, reliability baseline. Includes the first Packet Tracer activity exploring logical vs physical views, a module quiz (`1.5.5`), and a written lab (`1.9.3`).
- **Module 2 — Basic Switch and End-Device Configuration.** Initial switch CLI and end-device labs (`2.3.7`, `2.5.5`, `2.7.6`, `2.9.1`).
- **Module 3 — Protocols and Models.** Research lab on networking standards (`3.4.4`) and first Wireshark capture lab to view live traffic (`3.7.10`).
- **Module 4 — Physical Layer.** Cabling and media labs (`4.6.5`, `4.7.1`, `4.7.2`).
- **Module 7 — Ethernet Switching.** Frame structure and switching-behavior labs (`7.1.6`, `7.2.7`, `7.3.7`).
- **Module 9 — Address Resolution.** ARP labs and a quiz-score capture (`9.1.3`, `9.2.9`, `9.3.4`).
- **Module 10 — Basic Router Configuration.** Cisco IOS router-configuration labs (`10.1.4`, `10.3.4`, `10.3.5`) plus the in-class equipment lab `10.4.3 Build a Switch and Router Network` (captured as both Packet Tracer and lab-equipment exercises per the course schedule).
- **Module 11 — IPv4 Addressing.** Subnetting and addressing labs (`11.5.5`, `11.6.6`, `11.7.5`, `11.9.3`, `11.10.1`).
- **Module 12 — IPv6 Addressing.** Address identification and configuration labs (`12.4.5`, `12.6.6`, `12.7.4`, `12.9.1`).
- **Module 13 — ICMP.** Echo and unreachable / reachability behavior labs (`13.2.6`, `13.3.1`).
- **Module 14 — Transport Layer.** TCP vs UDP behavior lab (`14.8.1`).
- **Module 15 — Application Layer.** DNS resolution observation lab (`15.4.8`).
- **Module 16 — Network Security Fundamentals.** Research lab on network security threats (`16.2.6`) plus Packet Tracer security scenarios (`16.4.6`, `16.5.1`); the in-class equipment lab `16.5.2 Secure Network Devices` was also part of this module.
- **Module 17 — Build a Small Network.** Capstone module — `17.5.9`, `17.7.6` plus the in-class labs `17.8.1 Design and Build a Small Business Network` and `17.8.3 Troubleshooting Challenge` (`.pkt` and `.pka` files preserved).

## Status

Course completed Fall 2025 with grade **A** (Dean's List). Both Cisco Networking Academy completion certificates earned (Networking Basics, Introduction to Networks). ITN Final Skills Exam on equipment and ITN PTSA both passed. **Pursuing the full CCNA certification next** (NETI 209 / NETI 309 are the remaining two courses in the Ivy Tech CCNAv7 sequence).

## Related

- [CyberOps-115](https://github.com/jkosber/CyberOps-115) — Cisco CyberOps Associate coursework that builds on these foundations
- [CSIA-210-Network-Protocol-Analysis](https://github.com/jkosber/CSIA-210-Network-Protocol-Analysis) — deeper packet-level analysis
- [IntroToCybersecurity-105](https://github.com/jkosber/IntroToCybersecurity-105) — cybersecurity fundamentals
