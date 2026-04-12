# <span style="color:#3b82f6">Circui</span><span style="color:#f97316">Try</span><span style="color:#22c55e">3D</span> — Illuminating Electricity

> **CircuiTry3D** is a 3D interactive circuit simulation platform that makes electricity visual — from macro current flow all the way down to quantum probability clouds. Build, simulate, and learn by doing.

🌐 **Web App:** [circuitry3d.app](https://circuitry3d.app)  
📱 **Android:** [Google Play](https://play.google.com/store/apps/details?id=com.circuitry3d.app)

---

## About This Repository

This repo hosts the **CircuiTry3D marketing site** — a static HTML/CSS landing page deployed to GitHub Pages. It includes:

| File | Description |
|------|-------------|
| `index.html` | Main landing page — features, pricing, platforms, tech stack |
| `PrivacyPolicy.html` | Full privacy policy for the web and Android app |

---

## What Is CircuiTry3D?

CircuiTry3D is a complete electrical education ecosystem available on web and Android. It goes far beyond a basic circuit simulator:

- **3D Circuit Builder** — Real-time DC circuit sandbox with live W.I.R.E. analysis (Watts, Current, Resistance, Voltage) updated every tick. Supports batteries, resistors, LEDs, switches, junctions, and grounds.
- **Multi-Scale Current Flow** — Zoom from macro wire glow down to the atomic crystal lattice and quantum probability clouds across five depth tiers.
- **FUSE™ Failure Engine** — The proprietary *Failure Understanding Simulation Engine*: 30+ named failure modes across 18 component families (Thermal Runaway, Avalanche Breakdown, Junction Burnout, and more) with particle effects and physics-accurate explanations.
- **Component Arena** — Stress-test components against configurable voltage, temperature, humidity, and duty cycle; run single or A vs B comparisons; export results as JSON.
- **Adaptive Practice** — Surfaces targeted problems for your weakest W.I.R.E. concepts, with an Ohm's Law Triangle, Kirchhoff's Laws reference, and step-by-step solutions.
- **Integrated Textbook** — A full two-year post-secondary EE curriculum built into the app — Year 1 fundamentals through Year 2 advanced analysis.
- **Classroom Mode** — Teacher dashboard with roster management, join codes, assignment scheduling, and real-time analytics. NGSS PS3 and CTE Electronics pathway aligned.
- **Gamification & Arcade** — XP, streak bonuses, badges, leaderboards, and three arcade games (RetroCircuitMaze, OhmsRacer, VoltFighter).
- **Community Hub** — Share circuit exports, post lab notes, browse the circuit gallery. Persists locally for offline use.

---

## Who It's For

| Audience | Highlights |
|---|---|
| 🎓 **Educators & Institutions** | NGSS/CTE aligned; Classroom dashboard; Grade 8 → Higher Ed |
| 🎒 **Students** | Full two-year EE curriculum; adaptive practice; visual electron flow; XP/badges |
| 🏭 **Manufacturers & Retailers** | Feature real datasheets in Component Arena; FUSE™ failure cards credit manufacturer and part number |
| 🙋 **Curious Learners** | Free Sandbox — no account, no cost; drop in a battery and LED and watch it light up instantly |

---

## FUSE™ — Failure Understanding Simulation Engine

Every other circuit simulator shows what happens when a circuit *works*. FUSE™ shows exactly what happens when it **fails** — in real time, in 3D, with physics-accurate descriptions.

| Severity | Status | Example |
|---|---|---|
| 0 | ✅ OK | Operating within rated limits |
| 1 | ⚠️ Stressed | Thermal Overload — temp rising |
| 2 | 🔴 Critical | Avalanche Breakdown — diode |
| 3 | 💀 Destroyed | Junction Burnout — BJT |

Visual effects include: *char, melt, arc, burst, blowout, vent, glow, smoke*. Supports 18 component families including BJTs, MOSFETs, op-amps, relays, motors, and more.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React 19 + TypeScript |
| Build | Vite 7 |
| 3D Rendering | Three.js |
| Mobile | Capacitor 7 |
| Routing | React Router DOM 7 |
| Backend / API | GitHub Actions + Upstash Redis |
| Deployment | GitHub Pages (web) · Google Play Store (Android) |
| Testing | Vitest + Playwright |

---

## Pricing

| Plan | Price | Key Features |
|---|---|---|
| **Free Sandbox** | Free — no account required | 3 active circuits, limited component set, W.I.R.E. preview, FUSE™ severity badge — upgrade anytime for full access |
| **Premium — One-Time Unlock** | $6.99 forever | Everything, always — full component library, FUSE™ full effects, Component Arena, unlimited circuits |
| **Premium — Monthly** | $1.50 / month | Same full access, billed monthly |
| **Premium — Annual** | $14.99 / year *(save ~17%)* | Same full access, billed annually |
| **Educator & Institutional** | [Get in touch](mailto:hello@circuitry3d.app) | Classroom Mode, roster management, SSO, SIS integrations, school board reporting, and priority support — tailored to your school or organization |

---

## Contact & Legal

- **Founder:** Mitchell Lorin McKnight
- **General:** [hello@circuitry3d.app](mailto:hello@circuitry3d.app)
- **Privacy:** [privacy@circuitry3d.app](mailto:privacy@circuitry3d.app)
- **Privacy Policy:** [PrivacyPolicy.html](PrivacyPolicy.html) · [circuitry3d.app/privacy](https://circuitry3d.app/privacy)

© 2026 CircuiTry3D — All Rights Reserved
