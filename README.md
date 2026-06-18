# 📡 Miki Notes — IT & Networking Cheat Sheet

A personal mobile-friendly reference app for IT and networking topics.  
Built as a single HTML file — no frameworks, no dependencies, works offline.

🔗 **Live:** [mikikeela.github.io/miki-notes](https://mikikeela.github.io/miki-notes)

---

## 📱 Features

- **Search** — filter any term instantly across all categories
- **Category tabs** — jump to a specific topic fast
- **🧮 Subnet Calculator** — enter an IP/prefix and get network, broadcast, host range, mask, wildcard, IP class and more
- **Works offline** — service worker caches the page after first load
- **Add to Home Screen** — installable as a PWA on Android and iOS

---

## 📚 Topics Covered — 36 categories, 469+ terms

| Category | What's inside |
|---|---|
| OSI Model | All 7 layers, PDU names, mnemonics, encapsulation |
| TCP/IP & Protocols | TCP vs UDP, 3-way handshake, DNS, HTTP, SSH, SMTP... |
| Subnetting | /8–/32 reference, formulas, private ranges, APIPA |
| Public vs Private IP | RFC 1918 ranges, loopback, APIPA, NAT, IPv4 vs IPv6 |
| Cables & Connectors | Cat5–Cat8, UTP/STP, fiber, RJ45, SFP, PoE, crossover |
| RouterOS Essentials | Default IP 192.168.88.1, release types, upgrade methods, RouterBOOT, SSH keys |
| MikroTik – Access | Winbox, WebFig, CLI, SSH, Safe Mode |
| MikroTik – IP & Routing | /ip address, routes, OSPF, BGP, admin distance |
| MikroTik – DHCP | Server, client, IP pool, DORA, ARP reply-only |
| MikroTik – NAT | srcnat, dstnat, masquerade, port forwarding |
| MikroTik – Firewall | Chains, actions, connection states, address lists |
| MikroTik – Bridge & VLAN | Bridge ports, VLAN ID, tagged/untagged, MAC flooding |
| MikroTik – Wireless | SSID, modes, WPA2, bands, channel width |
| 802.11 Wi-Fi Standards | a/b/g/n/ac/ax speeds, 2.4 vs 5 GHz channels, WPA/WPA2/WPA3 |
| Wireless Channels & DFS | Non-overlapping channels, DFS radar, NStreme, CCQ, pseudobridge |
| RouterOS License Levels | L0–L6, CHR licensing, what each level unlocks |
| IP Services & Access Control | /ip service, blocking IPs, input vs forward chain |
| FastTrack & Connection Tracking | FastTrack bypass, address lists, connection state details |
| Backup vs Export | Binary vs plain text, what each includes, reboot needed? |
| Queues – Deep Dive | FIFO/SFQ/RED/PCQ, priorities 1–8, first-match rule |
| QoS – Burst & Guaranteed | burst-limit/time/threshold, limit-at, torch, graphing |
| ARP & MAC Addresses | ARP vs NDP, reply-only, valid/invalid MAC format |
| Wireless Advanced | Default Authenticate, Access List, WDS, station-bridge, rate flapping |
| PPP & Tunnels | PPPoE, L2TP, PPTP, SSTP, E1/T1 limitation |
| HotSpot | Login page, IP Bindings, Walled Garden, users |
| Connection States | new/established/related/invalid, TCP states, firewall order |
| Routing – Details | DAC flags, check-gateway, longest prefix match |
| RouterOS Packages | system, advanced-tools, routing, wireless |
| RouterBOARD Architectures | mipsbe, mipsle, powerpc, x86, arm — which board uses which |
| RouterOS Tools & Monitoring | The Dude, Netwatch, Torch, SNMP, Email, Logging, Graphs |
| Common Ports | FTP, SSH, DNS, HTTP, RDP, BGP, Winbox, SNMP and more |
| Kali Linux Commands | ip, ifconfig, nmap, nmcli, iwconfig, dhclient... |
| Network Security | CIA triad, IDS/IPS, DMZ, WPA2, Evil Twin, MITM, DoS |
| Tricky Exam Facts | 30+ gotchas: Level 1 = infinite, mangle can't DROP, RED vs UDP... |
| More Exam Q&A | Extra Q&A from MTCNA practice tests |
| 🧮 Subnet Calculator | Live calculator + CIDR cheat sheet |

---

## 🚀 Install on Phone

**Android (Chrome)**
1. Open the live URL in Chrome
2. Tap ⋮ → *Add to Home Screen*

**iPhone (Safari)**
1. Open the live URL in Safari
2. Tap the share icon → *Add to Home Screen*

After installing, the app works fully offline.

---

## 🛠️ Tech

- Pure HTML + CSS + vanilla JavaScript
- No build step, no npm, no frameworks
- PWA with service worker for offline support
- Single file: `index.html`
