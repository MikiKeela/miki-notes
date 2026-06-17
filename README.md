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

## 📚 Topics Covered

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
| Common Ports | FTP, SSH, DNS, HTTP, RDP, BGP, Winbox and more |
| Kali Linux Commands | ip, ifconfig, nmap, nmcli, iwconfig, dhclient... |
| Network Security | CIA triad, IDS/IPS, DMZ, WPA2, Evil Twin, MITM, DoS |
| Subnet Calculator | Live calculator + CIDR cheat sheet table |

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
