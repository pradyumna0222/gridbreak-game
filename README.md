# GridBreak: Red Team

Browser puzzle-stealth on a **corporate network map**. You are a live payload. Hold access nodes to drop firewalls, fork implant sessions that replay your last path, bait IDS sensors, and reach **C2 EXFIL**.

Play live (GitHub Pages, after deploy): [pradyumna0222.github.io/gridbreak-game](https://pradyumna0222.github.io/gridbreak-game/)

Repo: [github.com/pradyumna0222/gridbreak-game](https://github.com/pradyumna0222/gridbreak-game)

This is a **fictional red-team lab** — security terms are flavor for the puzzle (firewall, MFA, IDS, VLAN, C2). It does not teach real exploits.

---

## How it plays

- **Payload (you)** — WASD / arrows. Reach the green C2 EXFIL node.
- **Access nodes** — stand on MFA, VLAN, RCE, etc. to drop the matching firewall. Implants can hold nodes while you move.
- **Session fork [T]** — persist your last path as a parallel implant before TTL runs out. Dual gates need two bodies at once.
- **IDS cones** — red scanners. **Space** = encrypted burst (dash through a cone). Implants can lure the sensor off you.
- **SIEM alerts** — getting scanned kills the session; reinject with R.

## 12 subnets

1. DNS recon / NGFW  
2. Dual MFA bypass  
3. EDR decoy  
4. Triple exploit chain  
5. MITM packet relay  
6. Kernel / hypercall staging  
7. DPI firewall gauntlet  
8. Air-gapped SOC VLANs  
9. BGP route sync  
10. Split-key cipher  
11. ROP / ASLR / DEP / canary  
12. Quantum root extraction (finale)

## Controls

| Action | Key |
|---|---|
| Move payload | `W A S D` or arrows |
| Encrypted burst | `Space` |
| Fork implant session | `T` |
| Reset subnet | `R` |
| Audio | HUD button |

## Run locally

Open `index.html` in a browser, or:

```bash
python -m http.server 8085
```

Then go to `http://localhost:8085`.

Single file, no npm, no build.
