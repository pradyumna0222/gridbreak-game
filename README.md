# GridBreak: Operator Signal

![GridBreak Banner](banner.jpg)

> **Tactical Top-Down Cyberpunk Stealth Operations**  
> Infiltrate classified corporate black-sites, evade sweeping CCTV spotlights and heavy enforcer patrols, disarm laser security grids, and extract sensitive neural payloads.

---

## 🎮 Features

- **Top-Down Stealth Action**: Smooth 8-directional movement, dynamic vision cone raycasting, and obstacle line-of-sight occlusion.
- **Realistic Tiered Alarm Engine**:
  - `0% – 20%` **SECURE**: Standard patrolling routines.
  - `20% – 55%` **CAUTION [?]**: Peripheral detection triggers investigation; guards stop, face disturbance, and search for 2.5s.
  - `55% – 99%` **INTRUSION ALERT [!]**: Visual lock confirmed; enforcers actively pursue and sirens sound.
  - `100%` **FACILITY LOCKDOWN**: Total sector lockdown and emergency turret response.
- **Radial Threat Direction Indicator**: Dynamic on-player threat arc pointing directly at detecting enemies.
- **5 Progression Sectors**:
  - **Level 1**: Perimeter Breach (`SEC-01`)
  - **Level 2**: Surveillance Array (`SEC-02`)
  - **Level 3**: Enforcer Intercept (`SEC-03`)
  - **Level 4**: The Core Vault (`SEC-04`)
  - **Level 5**: Neural Apex Core (`SEC-05`)
- **4 Hack Abilities**:
  - `[1]` **EMP Stun** (3 Energy): Paralyzes enforcers for 5.0s.
  - `[2]` **Jam Optics** (2 Energy): Jams camera video feeds for 6.0s.
  - `[3]` **Bypass Gate** (5 Energy): Overrides active laser firewall barriers.
  - `[4]` **Stealth Cloak** (4 Energy): 3.5s optical camouflage invisibility.
- **Tactical Dash**: Press `Spacebar` for high-speed evasion through laser gaps and sensor blindspots.
- **Procedural Web Audio Synthesizer**: 100% self-contained sound engine with dynamic stealth-to-alert synth transitions, footstep clicks, and emergency sirens.
- **100% Self-Contained**: Runs directly in any modern web browser without dependencies, npm install, or build steps.

---

## 🕹️ Controls

| Action | Key / Control |
|---|---|
| **Move Operative** | `W`, `A`, `S`, `D` or `Arrow Keys` |
| **Tactical Dash** | `Spacebar` |
| **EMP Stun** | `1` Key / Button `[1]` |
| **Jam Optics** | `2` Key / Button `[2]` |
| **Bypass Gate** | `3` Key / Button `[3]` |
| **Stealth Cloak** | `4` Key / Button `[4]` |
| **Interact / Hack Terminal** | `E` Key / Proximity |
| **Audio Toggle** | `🔊 AUDIO ON/OFF` |
| **Synth Music Toggle** | `🎵 SYNTH ON/OFF` |
| **CRT Scanlines** | `⚡ CRT FX` |

---

## 🚀 Quick Start

Simply open `index.html` in any web browser:

```bash
# Or serve locally using python
python -m http.server 8085
```

Navigate to `http://localhost:8085` and commence infiltration!
