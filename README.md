# OQUAKE — OASIS-Powered Classic Shooter

**Lightning-Fast Retro Combat · OASIS Omniverse**

OQUAKE is a modified [vkQuake](../vkQuake) build integrated with the OASIS Omniverse. Collect real-world weapons and armour from GPS locations in parks, bring them into the game, and fight everywhere. A seamless blend of retro FPS and real-world AR discovery.

## Core Concept

1. **Collect in the real world** — weapons, armour and power-ups are hidden at GPS locations in parks and public spaces
2. **Fight in-game** — your real-world pickups appear in OQUAKE as playable items
3. **Karma rewards** — fragging enemies, completing levels and finding pickups earns OASIS karma
4. **NFT weapons** — rare weapons are NFTs owned on-chain; tradeable and usable across OASIS games

## OASIS Integration

- **Avatar SSO** — log in with your OASIS avatar from OPORTAL
- **Karma** — in-game achievements award OASIS karma
- **NFT items** — rare weapons are on-chain NFTs usable in ODOOM, Shadow Fighter and other OASIS games
- **GeoHotSpots** — pickup locations registered in STARNET as physical discovery points
- **Leaderboard** — global rankings tied to OASIS karma and avatar profiles

## Related Projects

- [`vkQuake`](../vkQuake) — the Vulkan Quake port OQUAKE is built on
- [`ODOOMSite`](../ODOOMSite) — OASIS-powered Doom (sister project)
- [`OGEngineSite`](../OGEngineSite) — the shared OASIS game engine framework
- [`STARNET`](../STARNET) — the asset and GeoHotSpot registry

## Tech Stack

| Layer | Detail |
|---|---|
| Game Engine | vkQuake (Vulkan Quake 1 port) |
| Site | Single-file `index.html` — inline CSS + vanilla JS |
| OASIS API | `@oasisomniverse/web4-api@2.0.2` via esm.sh |
| Fonts | Orbitron, Rajdhani, Share Tech Mono (Google Fonts) |

## Running the Site Locally

```bash
npx serve .
# or
python -m http.server 8080
```

---

*Part of the [OASIS Omniverse](https://oasisomniverse.one) · Built on vkQuake · Powered by OASIS Web4*
