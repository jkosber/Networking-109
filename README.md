# Networking-109 — NETI 109 Networking I (Cisco CCNA Part 1)

My Fall 2025 coursework at Ivy Tech Kokomo. Grade: A (Dean's List). NETI 109 is the first of three courses in the Ivy Tech CCNAv7 sequence, and it's actually two Cisco Networking Academy courses stacked back-to-back:

1. **Networking Basics** — 17 modules, Aug 27 – Sep 21. Completion certificate earned.
2. **Introduction to Networks (ITN, CCNA v7 Module 1)** — 17 modules, Sep 22 – Dec 10. Completion certificate earned.

The semester mixed Packet Tracer simulations with real Cisco routers and switches in the Ivy Tech Kokomo networking lab, weekly checkpoint exams, two final exams, and a final practical on lab gear. This repo holds the ITN module submissions, in-class Packet Tracer files, weekly class notes, and both completion certificates.

## Tools

- **Cisco IOS** — actual Cisco router and switch gear in the Ivy Tech Kokomo lab.
- **Cisco Packet Tracer** — every `.pka`, `.pkt`, and `.pksz` file in the repo is from Packet Tracer.
- **Wireshark** — first live capture happens in Module 3.
- Standard utilities — `ping`, `traceroute`, `ipconfig` / `ifconfig`.

## Certificates earned

- Cisco Networking Academy — **Networking Basics** ([PDF](Networking-Basics-certificate-JKosberg.pdf))
- Cisco Networking Academy — **Introduction to Networks** ([PDF](CCNA-Introduction-to-Networks-certificate-JKosberg.pdf))

## Big assessments

- Module-group checkpoint exams (Network Access; Internet Protocol; Communication Between Networks; Protocols for Specific Tasks; Basic Network Connectivity; Ethernet Concepts; Communicating Between Networks; IP Addressing; Network Application Communications; Building and Securing a Small Network).
- Networking Basics Final Exam — Sep 21.
- CCNA Introduction to Networks Course Final Exam — Dec 10.
- ITN Final Skills Exam (Equipment) — Dec 17, on real Cisco gear.
- ITN Practice PT Skills Assessment (PTSA) — Dec 19.

## Repository layout

```
Module-01-NetworkingToday/             Network value, components; first Packet Tracer activity
Module-02-BasicSwitchAndEndDevice/     Initial switch / end-device config in Packet Tracer
Module-03-ProtocolsandModels/          Networking-standards research; first Wireshark capture
Module-04-PhysicalLayer/               Cabling, media, signaling labs
Module-07-EthernetSwitching/           Frame structure and switching behavior
Module-09-AddressResolution/           ARP labs + quiz-score capture
Module-10-BasicRouterConfiguration/    Cisco IOS router config + in-class equipment build (10.4.3)
Module-11-IPv4Addressing/              IPv4 subnetting and addressing
Module-12-IPv6Addressing/              IPv6 addressing, identification, configuration
Module-13-ICMP/                        ICMP behavior labs
Module-14-TransportLayer/              TCP / UDP transport behavior
Module-15-ApplicationLayer/            DNS resolution observation
Module-16-NetworkSecurityFundamentals/ Threat-research lab + Packet Tracer security scenarios
Module-17-BuildASmallNetwork/          Small-network design, build, verify (incl. in-class equipment lab)
NetworkingActivities/                  Standalone Packet Tracer activities and module-quiz files
NetworkingNotes/                       Seven class-notes files (Aug 27 – Oct 15, 2025)
CCNA-Introduction-to-Networks-certificate-JKosberg.pdf
Networking-Basics-certificate-JKosberg.pdf
```

## Module walkthrough (ITN track)

- **Module 1 — Networking Today.** Why networks matter, components, reliability. First Packet Tracer activity (logical vs physical view), module quiz (`1.5.5`), and a written lab (`1.9.3`).
- **Module 2 — Basic Switch and End-Device Configuration.** First switch CLI work and end-device labs (`2.3.7`, `2.5.5`, `2.7.6`, `2.9.1`).
- **Module 3 — Protocols and Models.** Networking-standards research (`3.4.4`) and the first Wireshark capture lab (`3.7.10`).
- **Module 4 — Physical Layer.** Cabling and media labs (`4.6.5`, `4.7.1`, `4.7.2`).
- **Module 7 — Ethernet Switching.** Frame structure and switching-behavior labs (`7.1.6`, `7.2.7`, `7.3.7`).
- **Module 9 — Address Resolution.** ARP labs (`9.1.3`, `9.2.9`, `9.3.4`) and a quiz-score screenshot.
- **Module 10 — Basic Router Configuration.** Router IOS config labs (`10.1.4`, `10.3.4`, `10.3.5`) plus the in-class equipment lab `10.4.3 — Build a Switch and Router Network` (done as both Packet Tracer and on real gear).
- **Module 11 — IPv4 Addressing.** Subnetting and addressing labs (`11.5.5`, `11.6.6`, `11.7.5`, `11.9.3`, `11.10.1`).
- **Module 12 — IPv6 Addressing.** Address identification and configuration labs (`12.4.5`, `12.6.6`, `12.7.4`, `12.9.1`).
- **Module 13 — ICMP.** Echo / unreachable / reachability behavior labs (`13.2.6`, `13.3.1`).
- **Module 14 — Transport Layer.** TCP vs UDP behavior lab (`14.8.1`).
- **Module 15 — Application Layer.** DNS resolution observation lab (`15.4.8`).
- **Module 16 — Network Security Fundamentals.** Threat-research lab (`16.2.6`) plus Packet Tracer security scenarios (`16.4.6`, `16.5.1`); the in-class `16.5.2 — Secure Network Devices` equipment lab was also part of this module.
- **Module 17 — Build a Small Network.** Capstone — `17.5.9`, `17.7.6` plus the in-class labs `17.8.1 — Design and Build a Small Business Network` and `17.8.3 — Troubleshooting Challenge` (`.pkt` and `.pka` files preserved).

## Outcome

Passed both the ITN Final Skills Exam on equipment and the PTSA. Next up: the rest of the Ivy Tech CCNAv7 sequence (NETI 209, NETI 309) and the full CCNA.

## Related repos

- [CyberOps-115](https://github.com/jkosber/CyberOps-115) — Cisco CyberOps Associate, builds on this foundation.
- [CSIA-210-Network-Protocol-Analysis](https://github.com/jkosber/CSIA-210-Network-Protocol-Analysis) — deeper packet-level work.
- [IntroToCybersecurity-105](https://github.com/jkosber/IntroToCybersecurity-105) — cybersecurity fundamentals.
