# Deadwood Isle — a Miscreated server

**US-East · PvP · 50 slots · Islands map**

| | |
|---|---|
| Connect | Steam → View → Game Servers → Favorites → add `104.52.38.251:64092` |
| Region | US East |
| Map | Islands |
| Players | 50 |
| Day/night | Stock (nights run 4x faster than days) |
| Mods required | [Admin Chat Commands](https://steamcommunity.com/sharedfiles/filedetails/?id=2217434939), [BMW M4 & Charger Interceptor](https://steamcommunity.com/sharedfiles/filedetails/?id=2005194385) (101 MB) and [Deadwood Isle – Base Limits](https://steamcommunity.com/sharedfiles/filedetails/?id=3797893300) (tiny) — all three download automatically when you join |

## How this server differs from vanilla

Everything below is server-side. You don't need to install anything except the Workshop mods, which Steam handles for you on join.

### Loot
- **2.5x loot.** 50% of item spawners are active (vanilla 20%) and the world holds up to 1,800 items at once (vanilla 750).
- **More guns and ammo.** In every loot table the weapon and ammo share is 1.5x vanilla, with the rest scaled down. Rare and epic weapons are untouched, so they stay rare.

### Vehicles
- **2x vehicles.** Every vehicle category spawns double the stock minimum, so more cars, trucks, boats and bikes on the map.
- Abandoned vehicles respawn in 30 minutes instead of 60. Destroyed vehicles respawn in 1 hour instead of 2.
- **Charger Interceptor** added via the Workshop mod: police car spawns alternate between the stock cop cars and the Charger. Sedan spawns stay stock. The BMW M4 from the same mod does not spawn in the world; it's an admin-only event car.

### Harvesting
- **2x resources from trees, rocks and iron nodes.** Each node gives twice as many hits before it's depleted. Regeneration timers are stock.
- **Every swing yields.** Hatchets no longer miss (vanilla: 25% of swings give nothing). The game caps wood at one log per swing, so the axe wins on speed instead: it swings every 0.9 s against the hatchet's 1.25 s, about 40% faster.

### Base building
- **Wood is 2x tougher.** Every wood part has double health. Walls, foundations, roofs, stairs, walkways and ramps: 20,000 HP. Doors and shutters: 10,000. Gatehouses and watchtowers: 40,000.
- **Plated parts are indestructible.** Nothing damages them — not C4, not sledgehammers, not vehicles, not fire. Plate your walls and your base stays yours.
- Metal, rock and stone parts are stock.
- **Bigger bases.** Plot sign allows 600 parts (vanilla 250), a 50 m build radius (vanilla 30 m) and 40 m of vertical build room (vanilla 8.5 m), so tall builds and floating floors work.
- **Better generators.** The fuel generator runs 10 work lights (vanilla 5), the solar generator runs 30 (vanilla 3) and is silent.
- **No master light switch.** That's the game, not the server: every work light has its own switch and it resets to off on the daily restart. Leave each lamp switched on and use the generator as the master.
- **Prone is enabled.**

### Chat commands for everyone
- `!corpse` lists the coordinates of your nearest bodies so you can go get your gear back.

### Base part HP at a glance

| Part | Vanilla | Here |
|---|---|---|
| Wood wall 3x4 / foundation / roof / stairs / walkway | 10,000 | **20,000** |
| Wood door, shutter, trapdoor | 5,000 | **10,000** |
| Wood gatehouse, watchtower, gallows | 20,000 | **40,000** |
| Plated anything | 22,500 | **cannot be damaged** |
| Metal wall / gate / gatehouse | 37,500 | 37,500 |
| Rock foundation | 22,500 | 22,500 |

Sledgehammer 60 per hit, pickaxe/axe 30, hatchet 22. Wood takes full damage from any tool; only explosives and sledgehammers hurt plated in vanilla, and here nothing does.

### Raiding, for reference
- Stock plated wall: ~113 sledgehammer hits (about 4 minutes solo). Here: cannot be broken.
- A 20,000 HP wood wall takes ~334 sledgehammer hits or ~667 pickaxe hits. Explosives still work on wood.

## Rules
1. No cheating, exploiting or glitching through bases.
2. No hate speech in chat. Trash talk is fine; slurs get you banned.
3. Don't build inside or block spawn points, roads or loot buildings.
4. Admin decisions are final. Admins don't play favorites and don't spawn gear for anyone in normal play.

## Wipes
No schedule. The world wipes only when base clutter hurts performance or new players can't find room, or when a game update forces it. Wipes are announced in the join message at least a few days ahead.

## Known quirks
- **Big vehicles and part swaps.** The game's anti-cheat measures reach to the vehicle's center. On the 5-ton and bus, crouch against the middle of the vehicle's side before swapping wheels or parts, or the server rejects the move.
- Self-hosted servers don't show in the in-game Internet tab. Use Steam Favorites with the address above.
- The server restarts once a day (23 h uptime). Bodies and dropped items don't survive a restart; bases, vehicles and your inventory do.

## Contact
Admin: **Toll Troll** on the server. Issues with this page or the server: open an issue on this repo.

## Changelog
- **2026-09-10** — Axe swings 0.9 s (hatchet 1.25 s); Base Limits mod v7 carries the tool definitions.
- **2026-09-09** — `!corpse` for everyone; light-switch investigation closed (no master switch in the game).
- **2026-09-08** — Loot 2.5x with 1.5x weapon/ammo share; plot sign 600 parts / 50 m / 40 m; generators 10 and 30 lights, solar silent; prone enabled; Base Limits Workshop mod.
- **2026-09-07** — 2x harvest, axe/hatchet rebalance, admin commands mod, BMW & Charger mod (Charger in police spawns), "NEW" tag.
- **2026-09-06** — 2x loot, 2x vehicles, wood 2x HP, indestructible plated, server renamed to Deadwood Isle, 50 slots.
- **2026-09-05** — Server launched.
