# sovereign-bypass-architecture-in-russia-2028
# Baltic Transit 2030

### 🛡️ The Ultimate Anti-Censorship Architecture
This project presents a theoretical and practical framework for maintaining access to the Global Internet in an era of **Total Sovereign Networks** (2026-2030).

## Why this works
Traditional VPNs fail when the government controls the physical cables. This architecture uses a **physical bypass**:
1. **Masking:** Traffic mimics local Russian services (max.ru / gosuslugi.ru) using VLESS+Reality.
2. **Obfuscation:** Internal relay uses `xHTTP` to look like harmless API calls.
3. **Physical Jump:** Traffic is sent via **Starlink** satellite uplink near the border, physically bypassing terrestrial DPI filters (TSPU).
4. **Resilience:** Hysteria 2 (UDP) manages satellite latency and prevents throttling.

## Network Topology
`User` -> `Moscow Node (VLESS+Reality)` -> `Kaliningrad Node (xHTTP)` -> `Satellite Uplink` -> `EU Exit Node (Hysteria 2)` -> `Global Web`

## Instead of max.ru you can bet ads.x5.ru or vk.ru or other similar SNI

## Deployment
See the `/configs` folder for implementation details.

---
*Disclaimer: This is an educational research project on network resilience.*
