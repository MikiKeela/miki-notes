# 📡 Miki Notes — IT & Networking Cheat Sheet

A personal mobile-friendly reference app for IT and networking topics.  
Built as a single HTML file — no frameworks, no dependencies, works offline.

🔗 **Live:** [mikikeela.github.io/mikrotik-spikker](https://mikikeela.github.io/miki-notes)

---

## 📱 Features

- **Search** — filter any term instantly across all categories
- **Category tabs** — jump to a specific topic fast
- **🧮 Subnet Calculator** — enter an IP/prefix and get network, broadcast, host range, mask, wildcard, IP class and more
- **Works offline** — service worker caches the page after first load
- **Add to Home Screen** — installable as a PWA on Android and iOS

---

## 📚 Topics Covered — 29 categories, 385+ terms

| Category | What's inside |
|---|---|
| OSI Model | All 7 layers, PDU names, mnemonics, encapsulation |
| TCP/IP & Protocols | TCP vs UDP, 3-way handshake, DNS, HTTP, SSH, SMTP... |
| Subnetting | /8–/32 reference, formulas, private ranges, APIPA |
| Public vs Private IP | RFC 1918 ranges, loopback, APIPA, NAT, IPv4 vs IPv6 |
| Cables & Connectors | Cat5–Cat8, UTP/STP, fiber, RJ45, SFP, PoE, crossover |
| MikroTik – Access | Winbox, WebFig, CLI, SSH, Safe Mode |
| MikroTik – IP & Routing | /ip address, routes, OSPF, BGP, admin distance |
| MikroTik – DHCP | Server, client, IP pool, DORA process |
| MikroTik – NAT | srcnat, dstnat, masquerade, port forwarding |
| MikroTik – Firewall | Chains (input/forward/output), actions, connection states |
| MikroTik – Bridge & VLAN | Bridge ports, VLAN ID, tagged/untagged, MAC flooding |
| MikroTik – Wireless | SSID, modes, WPA2, bands, channel width |
| 802.11 Wi-Fi Standards | a/b/g/n/ac/ax speeds, 2.4 vs 5 GHz channels, WPA/WPA2/WPA3 |
| RouterOS License Levels | L0–L6, CHR licensing, what each level unlocks |
| IP Services & Access Control | /ip service, blocking IPs, input vs forward chain |
| Backup vs Export | Binary vs plain text, what each includes, reboot needed? |
| Queues – Deep Dive | FIFO/SFQ/RED/PCQ, priorities 1–8, first-match rule, PCQ classifiers |
| ARP & MAC Addresses | ARP vs NDP, reply-only, valid/invalid MAC format, full duplex |
| Wireless Advanced | Default Authenticate, Access List, WDS, station-bridge, rate flapping |
| PPP & Tunnels | PPPoE broadcast domain, Secrets, E1/T1 limitation, PPTP |
| Connection States | new/established/related/invalid, TCP states, firewall order |
| RouterOS Packages | system, advanced-tools, routing, wireless — what each includes |
| RouterBOARD Architectures | mipsbe, mipsle, powerpc, x86, arm — which board uses which |
| Common Ports | FTP, SSH, DNS, HTTP, RDP, BGP, Winbox, SNMP and more |
| Kali Linux Commands | ip, ifconfig, nmap, nmcli, iwconfig, dhclient... |
| Network Security | CIA triad, IDS/IPS, DMZ, WPA2, Evil Twin, MITM, DoS |
| CLI Quick Reference | Most-used /ip, /system, /interface commands |
| 🧮 Subnet Calculator | Live calculator + CIDR cheat sheet table |
| Tricky Exam Facts | 30+ common gotchas: Level 1 = infinite, mangle can't DROP, RED vs UDP... |
| More Exam Q&A | Extra Q&A from MTCNA practice tests |

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
