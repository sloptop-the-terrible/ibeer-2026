# 🍺 **iBeer 2026** — The World's Most Advanced Liquid Simulation Platform™

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)]()
[![Coverage](https://img.shields.io/badge/coverage-100%25-success.svg)]()
[![License](https://img.shields.io/badge/license-ICE--WARE--v1-blue.svg)]()
[![Platform](https://img.shields.io/badge/platform-web%2Fios%2Fandroid-brightgreen)]()
[![Dependencies](https://img.shields.io/badge/dependencies-0-brightgreen)]()
[![AI](https://img.shields.io/badge/AI%20generated-no-brightgreen)]()
[![Privacy](https://img.shields.io/badge/privacy-Zero%20Trust%20Beverage-ff69b4)]()
[![RFC Compliance](https://img.shields.io/badge/RFC-2324%20%7C%201149-yellow)]()
[![ISO](https://img.shields.io/badge/ISO-Tilt%20Ready-8A2BE2)]()
[![GDPR](https://img.shields.io/badge/GDPR-Ice%20Cubes%20Consent-006400)]()
[![TAM](https://img.shields.io/badge/TAM-Everyone%20Who%20Has%20Seen%20a%20Glass-orange)]()

---

> *"The glass is not half empty. The glass is a sovereign beverage rendering surface."*
> — iBeer 2026 Executive Summary

---

## 📖 Table of Contents

- [Hero Section](#-hero-section)
- [Features](#-features)
- [Architecture Overview](#-architecture-overview)
- [Installation](#-installation)
- [Usage](#-usage)
- [Drink Database](#-drink-database)
- [Privacy & Security](#-privacy--security)
- [Roadmap](#-roadmap)
- [FAQ](#-faq)
- [Contributing](#-contributing)
- [License](#-license)
- [References](#-references)

---

## 🚀 Hero Section

### The First and Only Vertically Integrated Beverage Rendering Engine

iBeer 2026 is not a web app. It is a **liquid infrastructure platform** that redefines how humanity interacts with transparent vessels containing colored fluids. Built on decades of glass-tilting research and powered by next-generation ice orchestration technology, iBeer 2026 brings enterprise-grade beverage simulation to every pocket, desk, and lap.

**Our mission:** To democratize the drinking experience through deterministic cube placement, density-aware multi-liquid layering, and real-time spill forecasting.

**Our vision:** A world where every tilt of the wrist is a certified, auditable, zero-trust beverage event.

**Total Addressable Market:** Everyone who has ever seen a glass. That's approximately 8 billion addressable vessels worldwide.

---

### Screenshots

```text
┌─────────────────────────────────────────────────────────┐
│   [📱]  [🥃]  [🍷]  [🍹]  [💧]  [☕]  [🍵]  [🥛]     │
│   [💛]  [🪬]  [🐀]  [🌋]  [☢️]  [🧴]  [🧪]           │
│                                                         │
│               ┌──────────────┐                          │
│               │              │                          │
│               │   🍺 Beer    │ ← Density: 1.01         │
│               │   🥃 Whiskey │ ← Density: 0.95         │
│               │              │                          │
│               │   🧊🧊🧊    │ ← Artisanal ice cubes   │
│               │              │                          │
│               └──────────────┘                          │
│              ──────── puddle ────────                    │
│                                                         │
│              🍻 Liquid Chaos v2026.07                    │
│              ═══════════════════                         │
│              Spill Meter: ████████░░ 72%                 │
│                                                         │
│              [🔄 Refill] [🧊 Ice] [🗑️]                  │
│                                                         │
│   ┌─────────────────────────────────────────────┐       │
│   │ SΛMSUNG │ Galaxy S26 Ultra │ Learn More     │       │
│   └─────────────────────────────────────────────┘       │
└─────────────────────────────────────────────────────────┘
```

*Screenshot placeholder: A fully layered beverage with 3 distinct density zones, active ice physics, and real-time spill forecasting.*

---

### Demo GIF

```text
[ GIF PLACEHOLDER ]
> A user tilting a phone while the glass on screen tilts in perfect
> synchronization, ice cubes slide with realistic inertia, and a small
> puddle forms on the virtual bar as the user exceeds the maximum tilt
> angle of 35°. This is liquid infrastructure.
```

---

## ✨ Features

### Core Capabilities

| Feature | Description | Enterprise Value |
|---------|-------------|------------------|
| **15 Liquids** | Beer, Whiskey, Wine, Cocktail, Water, Coffee, Tea, Milk, Piss, Mercury, Rat Poison, Lava, Radioactive Sludge, Bleach, Acid | Covers 100% of beverage use cases |
| **Density Mixing** | Liquids layer automatically by specific gravity (Hg: 13.6 → H₂O: 1.0) | Deterministic stratification |
| **Ice Physics** | GPU-free cube motion with wall collision, ice-to-ice interaction, and melt simulation | Real-time ice orchestration |
| **Spill Engine** | When tilt exceeds 35°, liquid exits the glass proportionally | Predictive spill analytics |
| **Bubble Reactions** | Per-liquid bubble rate (lava: 0.8, mercury: 0.0, acid: 0.9) | Auditable aeration metrics |
| **Thermal Dynamics** | Temperature-dependent ice melt (lava at 1200°C melts ice 100× faster than beer) | Heat-transfer modeling |
| **Toxic Classification** | Dangerous liquids flagged with ☠️ or 🔥 indicators | Workplace safety compliance |
| **Bar Ambiance** | Neon sign, brick texture, wooden shelf line | Immersive hospitality UX |
| **3D Gyroscope Input** | Real-time phone orientation tracking via DeviceOrientation API | Proprioceptive beverage interaction |
| **Touch Fallback** | Drag-to-tilt for desktop and non-gyro devices | Universal access |

### Next-Generation Ice Orchestration™

Every ice cube in iBeer 2026 is an individually tracked thermodynamic entity with:
- Unique identifier (dataset properties)
- Position tracking (left/bottom percentage)
- Velocity vector (vx/vy float)
- Melt state (0-100 integer)
- Cube-to-cube collision response

Ice cubes are **not** generated by AI, cloud APIs, or random number generators sourced from centralized entropy pools. They are deterministically placed using locally computed pseudorandom distribution, ensuring reproducible chaos across sessions.

### Vertical Beverage Integration™

Unlike "competitors" who render a static image of a drink, iBeer 2026 implements a **full liquid stack**:
- Bottom-up density layering
- Real-time level adjustment on consumption
- Multi-liquid blending with proportional mixing
- Surface tension simulation (CSS radial-gradient reflection layers)
- Perimeter moisture condensation (backdrop-filter blur)

---

## 🏗 Architecture Overview

```
┌──────────────────────────────────────────────────────┐
│                  User Phone (Sovereign Hardware)       │
│                                                        │
│  ┌─────────────┐    ┌──────────────────────────────┐  │
│  │ Gyroscope   │    │   iBeer 2026 Rendering Engine │  │
│  │ (beta/gamma)│───→│                              │  │
│  └─────────────┘    │  ┌────────────────────────┐  │  │
│                     │  │ Liquid Density Sorter   │  │  │
│  ┌─────────────┐    │  │ (bubble sort by sg)     │  │  │
│  │ Touch Input │───→│  └────────────────────────┘  │  │
│  └─────────────┘    │         ↓                     │  │
│                     │  ┌────────────────────────┐  │  │
│                     │  │ Ice Physics Loop        │  │  │
│                     │  │ (requestAnimationFrame) │  │  │
│                     │  └────────────────────────┘  │  │
│                     │         ↓                     │  │
│                     │  ┌────────────────────────┐  │  │
│                     │  │ Spill Forecasting Engine│  │  │
│                     │  │ (tilt > 35° threshold)  │  │  │
│                     │  └────────────────────────┘  │  │
│                     │         ↓                     │  │
│                     │  ┌────────────────────────┐  │  │
│                     │  │ CSS Render Pipeline     │  │  │
│                     │  │ (gradient layering)     │  │  │
│                     │  └────────────────────────┘  │  │
│  ┌─────────────┐    │         ↓                     │  │
│  │ Samsung Ad  │←───│  ┌────────────────────────┐  │  │
│  │ (sponsored) │    │  │ User's Screen           │  │  │
│  └─────────────┘    │  │ (pixel-perfect glass)   │  │  │
│                     │  └────────────────────────┘  │  │
│  ┌─────────────┐    │                              │  │
│  │ Zero Data    │    │   NO DATA EVER LEAVES THE    │  │
│  │ Egress       │    │   GLASS BECAUSE THERE IS NO  │  │
│  │ (guaranteed) │    │   DATA AND BARELY A GLASS    │  │
│  └─────────────┘    │                              │  │
│  └──────────────────────────────────────────────┘  │
│                                                        │
│  No cloud. No servers. No telemetry. No data egress.  │
│  Every ice cube rendered on YOUR sovereign hardware.   │
└──────────────────────────────────────────────────────┘
```

### Technology Stack

| Component | Technology | Justification |
|-----------|-----------|---------------|
| Rendering | CSS `linear-gradient()` | Pixel-perfect liquid color reproduction |
| Physics | `requestAnimationFrame()` loop | Sub-millisecond ice cube position recalculation |
| Input | `DeviceOrientationEvent` API | Native phone tilt without polling |
| Networking | **None** | Zero data leaves the device |
| Frameworks | **None** | Artisanal hand-crafted JavaScript |
| Dependencies | **0** | Ethically harvested source code only |
| AI Involvement | **0%** | Every line written by a human developer |

---

## 📦 Installation

### Method 1: Direct Browser (Recommended)

1. Open the following URL on any device with a web browser:
   ```
   https://github.com/sloptop-the-terrible/ibeer-2026
   ```
2. Download `index.html`
3. Open it in your browser
4. Grant gyroscope permission when prompted
5. Tilt device to drink

**No installation required. No app store. No accounts. No SDKs. No consent banners. No cookies. No tracking. No telemetry.**

### Method 2: Hosted Instance

For enterprise deployment, a hosted instance is available at:
```
https://characters-scales-vegetarian-columbus.trycloudflare.com
```
*Note: This is a TryCloudflare ephemeral tunnel with no uptime guarantee. For production deployments, contact our Zero Trust Beverage Architecture team.*

### Method 3: Self-Hosted Enterprise Deployment

```bash
git clone https://github.com/sloptop-the-terrible/ibeer-2026.git
cd ibeer-2026
python3 -m http.server 8080
# Open http://localhost:8080
```

That's it. No `npm install`. No `pip install`. No `docker compose up`. No Kubernetes manifest. No Helm chart. No Terraform. No CloudFormation. No Webpack. No Vite. No Babel. No TypeScript compilation. No WASM compilation. No CDN. No CI/CD pipeline. No microservices. No message queue. No database migration. No secrets manager. No load balancer. No service mesh. No observability stack. No SLA review. No SOC2 audit.

**A single HTML file. No explanation required.**

---

## 🎮 Usage

### Quick Start

1. **Open the app** — see a glass of beer on your phone screen
2. **Tilt back** — the glass tilts, beer drains, bubbles rise, ice cubes slide
3. **Tilt too far** — liquid spills out, puddle forms on the virtual bar
4. **Tap another drink** — liquids mix by density
5. **Tap 🧊 Ice** — add artisanal ice cubes
6. **Tap 🗑️** — remove all ice cubes
7. **Tap 🔄 Refill** — fresh glass, fresh start

### Drink Combinations

Select a primary drink, then tap a secondary drink to create a layered beverage:

| Combination | Result |
|-------------|--------|
| Beer + Whiskey | Irish car bomb (density: stable) |
| Lava + Mercury | Mercury boils, lava solidifies on contact |
| Sludge + Bleach | Reaction bubbles intensify |
| Milk + Piss | A crime against humanity (not recommended) |
| Acid + Ice | Ice melts instantly, acid fizzes |
| Coffee + Tea | London fog (layered by temperature) |
| Wine + Water | Table wine (diluted) |
| Poison + Everything | Toxic warning on every interaction |

### Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `R` | Refill glass |
| Mouse drag down | Simulate tilt (fallback) |

---

## 🧪 Drink Database

| ID | Name | Density | Viscosity | Temp (°C) | Bubble Rate | Ice Melt Rate | Toxic |
|----|------|---------|-----------|-----------|-------------|---------------|-------|
| beer | 🍺 Beer | 1.01 | 0.3 | 4 | 0.3 | 0.1 | ❌ |
| whiskey | 🥃 Whiskey | 0.95 | 0.6 | 20 | 0.05 | 0.3 | ❌ |
| wine | 🍷 Wine | 1.01 | 0.4 | 18 | 0.08 | 0.2 | ❌ |
| cocktail | 🍹 Cocktail | 1.02 | 0.5 | 4 | 0.15 | 0.1 | ❌ |
| water | 💧 Water | 1.0 | 0.2 | 20 | 0.1 | 0.2 | ❌ |
| coffee | ☕ Coffee | 1.02 | 0.35 | 70 | 0.2 | 2.0 | ❌ |
| tea | 🍵 Tea | 1.0 | 0.25 | 80 | 0.12 | 2.5 | ❌ |
| milk | 🥛 Milk | 1.03 | 0.5 | 4 | 0.15 | 0.15 | ❌ |
| piss | 💛 Piss | 1.01 | 0.2 | 37 | 0.2 | 0.5 | ❌ |
| mercury | 🪬 Mercury | 13.6 | 0.8 | 20 | 0.0 | 1.0 | ☠️ |
| poison | 🐀 Rat Poison | 1.5 | 0.7 | 20 | 0.1 | 0.3 | ☠️ |
| lava | 🌋 Lava | 3.1 | 2.0 | 1200 | 0.8 | 10.0 | ☠️🔥 |
| sludge | ☢️ Radioactive Sludge | 1.8 | 0.9 | 40 | 0.6 | 0.5 | ☠️ |
| bleach | 🧴 Bleach | 1.1 | 0.3 | 20 | 0.7 | 0.8 | ☠️ |
| acid | 🧪 Acid | 1.4 | 0.3 | 25 | 0.9 | 3.0 | ☠️ |

---

## 🔒 Privacy & Security

### Zero Trust Beverage Architecture™

iBeer 2026 implements a **Zero Trust Beverage Architecture** (ZTBA) — the industry's first framework for auditable, privacy-first liquid simulation. Every ice cube is rendered on the user's own sovereign hardware. No data leaves the glass because there is no data and barely a glass.

### Privacy Guarantees

| Concern | iBeer 2026 | Industry Standard |
|---------|------------|-------------------|
| Accounts | ❌ Zero | ✅ Required |
| Telemetry | ❌ Zero | ✅ Continuous |
| Analytics | ❌ Zero | ✅ Exhaustive |
| Ads | ❌ Zero* | ✅ Invasive |
| Cloud Sync | ❌ Zero | ✅ Mandatory |
| Tracking | ❌ Zero | ✅ Cross-site |
| Cookies | ❌ Zero | ✅ Thousands |
| Blockchain | ❌ Zero | ✅ "Web3" nonsense |
| Machine Learning | ❌ Zero | ✅ "AI-powered" |
| Personalization | ❌ Zero | ✅ "For you" |
| Internet Permission | ❌ Not required | ✅ Always-on |
| Data Egress | ❌ Guaranteed zero | ✅ Maximal extraction |

*\* A Samsung ad is displayed at the bottom of the app as a licensed integration. Samsung may or may not have paid us. We do not track whether you clicked it because we cannot track anything. This is a feature.*

### Regulatory Compliance

- **GDPR Article 5(1)(c) — Data Minimization:** We collect exactly zero pieces of personal data. Even asking for your name would violate our architecture.
- **GDPR Article 17 — Right to Erasure:** All data is erased continuously by never existing.
- **CCPA §1798.100 — Right to Know:** You have the right to know that we know nothing about you.
- **ISO 27001:** We are ISO 27001 certified for the absence of data.
- **RFC 2324:** Hyper Text Coffee Pot Control Protocol compliant for all hot beverages.
- **RFC 1149:** Standard for the transmission of IP datagrams on avian carriers — we do not use this. Data stays local.
- **ISO 9001:** Certified for glass-tilt quality management.
- **SOC 2 Type II:** Audit available upon request. The audit concludes: "There is nothing to audit."

### Data Flow Diagram

```
┌─────────┐     ┌──────────────────┐     ┌───────────┐
│  Phone  │────→│  iBeer Engine    │────→│  Screen   │
│  Input  │     │  (local only)    │     │  (pixels) │
└─────────┘     └──────┬───────────┘     └───────────┘
                       │
                       ▼
              ┌──────────────────┐
              │    Nowhere       │
              │  (data never     │
              │   goes anywhere) │
              └──────────────────┘
```

---

## 🗺 Roadmap

### Q3 2026 — Current Release
- ✅ 15 liquids with density layering
- ✅ Ice physics with melt simulation
- ✅ Spill mechanics
- ✅ Per-liquid bubble reactions
- ✅ Samsung ad integration

### Q4 2026
- 🔲 **Ice-to-liquid ratio feedback** — real-time dilution tracking
- 🔲 **Multi-tap support** — simultaneously simulate multiple beverages
- 🔲 **Temperature-aware glass condensation** — CSS water droplets
- 🔲 **Sound effects** — pour, sip, spill, and clink (Web Audio API)
- 🔲 **Upsell Samsung Galaxy S26 Ultra ad** — dynamic ad rotation

### Q1 2027
- 🔲 **Enterprise SSO integration** — because why not
- 🔲 **Blockchain-based ice provenance** — track each cube's origin on-chain
- 🔲 **AI-powered beverage recommendation engine** — "You tilted too fast. Try whiskey."
- 🔲 **WebAssembly port for sub-millisecond cube physics**
- 🔲 **AR mode** — overlay simulated glass on real-world surfaces

### Q2 2027
- 🔲 **IPO filing** — iBeer 2026 listed on NASDAQ as $BEER
- 🔲 **Hardware partnership with Samsung** — dedicated iBeer button on Galaxy S27
- 🔲 **Quantum beverage rendering** — leverage superposition for all possible fill states
- 🔲 **Zero Trust Beverage Architecture RFC submission to IETF**

---

## ❓ FAQ

### Is this a real product?
Define "real." The code executes. The glass renders. The ice melts. The liquid spills. In a very real sense, this is the most honest software ever written — it does exactly what it says, and nothing more.

### Does this work on desktop?
Yes. The touch fallback (drag down to tilt) works on any browser. There is no desktop build because there is no build at all. Just a file.

### Is the Samsung ad real?
The ad is as real as the simulated beverages it accompanies. Samsung has neither endorsed nor acknowledged this project. The ad exists in a state of beautiful ambiguity.

### Can I add my own drink?
Yes. Open `index.html`, find the `LIQUIDS` object, and add your entry. Requires: name, color gradient, density, viscosity, temperature, bubble rate, ice melt rate, toxicity flag. No pull request required. No code review. No compliance checklist. Just JavaScript.

### What happens if I mix lava and mercury?
Mercury (density 13.6) sinks to the bottom. Lava (density 3.1) floats on top. The mercury boils. The lava cools. Both remain toxic. The glass does not melt because the glass is a CSS linear-gradient with no physical properties.

### Is this a joke?
The joke is that we built a fully functional liquid simulation engine, hosted it through a Cloudflare tunnel, pushed it to GitHub, and wrote this README instead of doing literally anything else productive. The glass is the joke. The ice is the joke. This entire paragraph is part of the joke. But the code works.

### Why does the app need gyroscope permission?
It doesn't. It has a fallback. But tilting your phone like a glass of whiskey is the user experience we were born to deliver. Denying gyroscope permission defaults you to drag-to-tilt, which is technically adequate but spiritually hollow.

### Will this app steal my data?
No. The app literally cannot steal your data. It has no network functionality. It cannot send data anywhere. It cannot receive data from anywhere (except the Samsung ad, which is hardcoded as text). Your ice cubes are safe.

### What is the "spill meter"?
The spill meter is an advanced risk visualization dashboard that shows, at a glance, how much liquid you have spilled and how close you are to spilling more. It replaces traditional risk management frameworks with a simple horizontal bar gauge.

### Is this a Google interview project?
Master (Rafa) said it is. So it is.

---

## 🤝 Contributing

We welcome contributions from anyone who has ever held a glass.

### Getting Started

1. Fork the repository
2. Create a feature branch
3. Make your changes to `index.html`
4. Ensure the glass still tilts
5. Ensure the ice still melts
6. Submit a pull request

### Contribution Guidelines

- **Every line must be hand-written.** No AI-generated code. No Copilot completions. No GPT suggestions. If your code was assisted by a large language model, the founding team will know. We test for machine learning residue.
- **No build tools.** If your contribution requires npm, pip, webpack, vite, or any dependency manager, it will be rejected. The project has zero dependencies and that is not negotiable.
- **No telemetry.** Do not add analytics, tracking pixels, crash reporters, or any form of data collection. The app has zero data egress and that is the entire point.
- **CSS gradients are welcome.** Additional liquid colors, foam effects, and bubble animations are encouraged.
- **Glass physics optimizations** are always reviewed.

### Code of Conduct

1. Don't spill the glass
2. Don't launch glass across your keyboard
3. Ice cubes are friends, not enemies
4. Lava is dangerous
5. Mercury is very dense
6. Rat poison is labeled clearly for a reason
7. Have fun, you're simulating drinks in a browser

---

## ⚖️ License

### ICE-WARE v1 — The iCe bEverage End-User License

```
ICE-WARE LICENSE v1.0 (the "ICE-WARE")

Copyright © 2026 sloptop-the-terrible

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "BEVERAGE"), to deal
in the BEVERAGE without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the BEVERAGE, and to permit persons to whom the BEVERAGE is
furnished to do so, subject to the following conditions:

1. The above copyright notice and this permission notice shall be included
   in all copies or substantial portions of the BEVERAGE.

2. The BEVERAGE is provided "as is," without warranty of any kind, express
   or implied, including but not limited to the warranties of merchantability,
   fitness for a particular purpose, and non-misuse of the BEVERAGE for
   simulating lava in a glass held by a minor.

3. In no event shall the authors or copyright holders be liable for any
   claim, damages, or other liability, whether in an action of contract,
   tort, or otherwise, arising from, out of, or in connection with the
   BEVERAGE or the use or other dealings in the BEVERAGE, specifically
   including but not limited to:
   a) Spilling the BEVERAGE on a keyboard
   b) Simulating mercury consumption
   c) Confusing the BEVERAGE with a real beverage
   d) Tilting too far while holding a real beverage
   e) The Samsung ad

4. This license is GPL-compatible in the sense that GPL stands for
   "Glass Promotion License" and we fully endorse glass promotion.

5. ICE cubes distributed under this license must retain their cubic shape
   unless melted by lava or other high-temperature beverage simulations.
```

---

## 📚 References

### Standards & Specifications

| Standard | Title | Application |
|----------|-------|-------------|
| [RFC 2324](https://datatracker.ietf.org/doc/html/rfc2324) | Hyper Text Coffee Pot Control Protocol (HTCPCP/1.0) | Hot beverage rendering compliance |
| [RFC 1149](https://datatracker.ietf.org/doc/html/rfc1149) | Standard for the Transmission of IP Datagrams on Avian Carriers | We do not use this. Data stays local. |
| [RFC 7168](https://datatracker.ietf.org/doc/html/rfc7168) | The Hyper Text Coffee Pot Control Protocol for Tea Efflux Appliances | Tea brewing simulation adherence |
| [ISO 3103](https://en.wikipedia.org/wiki/ISO_3103) | Standard method for tea tasting | Not applicable to our beverage engine but listed for credibility |
| ZTBA-2026 | Zero Trust Beverage Architecture v1.0 | Internal white paper (unpublished, intentionally) |

### Privacy Resources

- [European Data Protection Board — Guidelines on Data Minimization](https://edpb.europa.eu/)
- [California Consumer Privacy Act (CCPA)](https://oag.ca.gov/privacy/ccpa)
- [General Data Protection Regulation (GDPR)](https://gdpr.eu/)
- [The Right to Glass Privacy — A position paper](https://example.com/glass-privacy)
- [Zero-Data Architecture Manifesto](https://example.com/zero-data)

### Academic References

- Smith, J. et al. (2024). *"A Survey of Ice Cube Positioning Algorithms in Browser-Based Fluid Simulations."* Journal of Beverage Informatics, 12(3), 45-67.
- García, M. (2025). *"Deterministic Chaos in Multi-Liquid Density Layering."* Proceedings of the International Conference on Glass Simulation, 89-102.
- Patel, R. (2026). *"No-Data Architectures: A Comparative Analysis of Zero-Egress Beverage Engines."* ACM Transactions on Simulated Consumption, 8(2), 1-24.
- *"RFC 2324 Compliance in Modern Web Browsers"* — IETF Workshop on Coffee Infrastructure, 2025.

---

> **iBeer 2026** — *The glass is not half empty. The glass is a sovereign beverage rendering surface.*

---

<p align="center">
  <sub>Handcrafted by humans without AI-generated code, AI-assisted development, vibe coding, Stack Overflow archaeology, Internet searches, cloud APIs, or JavaScript frameworks discovered five minutes ago.<br>
  Artisanal, locally sourced software compiled from ethically harvested source code.<br>
  Every ice cube rendered locally on the user's own sovereign hardware.<br>
  No data leaves the glass because there is no data and barely a glass.</sub>
</p>
