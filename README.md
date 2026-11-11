<div align="center">

# 📍 Find Nearest Uprint Kiosk

### Your nearest printer, one tap away.

A live map of every **[Uprint](https://uprintbd.com)** self-service printing kiosk. It shows real-time status, distance and travel time from where you are, then sends you there.

[![Live Demo](https://img.shields.io/badge/▶_Live_Demo-Find_a_kiosk-FF6B00?style=for-the-badge)](https://uprintbd.com/uprint/nearby-kiosks/)
[![Open 24/7](https://img.shields.io/badge/kiosks-open_24%2F7-2EA44F?style=for-the-badge)](https://uprintbd.com/uprint/nearby-kiosks/)

![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Geolocation API](https://img.shields.io/badge/Geolocation_API-4285F4?style=flat-square&logo=googlemaps&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_4-7952B3?style=flat-square&logo=bootstrap&logoColor=white)

</div>

---

## ⚡ The problem → the fix

> "Is there a working printer near me right now?" Before this, students had no way to know without walking there.

**Find Nearest Uprint Kiosk** answers that in one glance: which kiosks are **online**, how far they are, and how long it takes to get there **on foot or by rickshaw/CNG**.

```mermaid
flowchart LR
    A["📍 Share location"] --> B["🗺️ All kiosks on map"]
    B --> C["🟢 Live status"]
    C --> D["⏱️ Distance + travel time"]
    D --> E["💰 Check print price"]
    E --> F["🧭 Navigate in Google Maps"]
    style A fill:#FFF4EB,stroke:#FF6B00
    style F fill:#FF6B00,color:#fff,stroke:#FF6B00
```

---

## ✨ Features

| | Feature | What it does |
|:-:|---|---|
| 🗺️ | **Live map** | Every Uprint kiosk plotted alongside your current location |
| 🟢 | **Real-time status** | Each kiosk shown as `Online`, `Printer Disconnected` or `Offline` |
| ⏱️ | **Distance & travel time** | Live from your position, per kiosk |
| 🚶 | **Travel modes** | Switch between **Walk** and **Rickshaw / CNG**, built for how Chattogram actually moves |
| 💰 | **Print price** | See each kiosk's rates before you go |
| 🧭 | **Navigate** | One tap opens turn-by-turn directions in Google Maps |
| 🔓 | **Public view** | Anyone sees the map; logging in unlocks personal distance and time |
| 🛠️ | **Admin tools** | Admin and sales set each kiosk's location and preview the map as a user |

---

## 🟢 Status legend

| Status | Meaning |
|---|---|
| 🟢 **Online** | Kiosk and printer ready, go print |
| 🟠 **Printer Disconnected** | Kiosk is up, printer needs attention |
| ⚫ **Offline** | Kiosk not reachable right now |

---

## 🏗️ How it works

```mermaid
flowchart TB
    K["🖨️ Kiosk devices"] -->|"heartbeat"| S["Uprint server"]
    S -->|"locations + live status"| M["🗺️ Kiosk map"]
    U(("👩‍🎓 Student")) -->|"browser location"| M
    M -->|"distance / time"| U
    M -->|"Navigate"| G["Google Maps"]
```

---

## 👨‍💻 My role

- Designed and built the feature end to end: map view, live status, distance and travel-time logic, and admin location tools
- Added local travel modes (Walk, Rickshaw / CNG) to fit how students in Chattogram get around
- Shipped to production at **[uprintbd.com](https://uprintbd.com/uprint/nearby-kiosks/)**

---

<div align="center">

**Part of the Uprint platform:**
[📄 Uprint Lab Sheet Builder](https://github.com/MSSohan/Uprint-Lab-Sheet-Builder) ·
[📍 Find Nearest Uprint Kiosk](https://github.com/MSSohan/Find-Nearest-Uprint-Kiosk) ·
[🛠️ Uprint Kiosk Management](https://github.com/MSSohan/Uprint-Kiosk-Management)

<sub>The production source code is private. This repository is a showcase of the feature.</sub>

</div>
