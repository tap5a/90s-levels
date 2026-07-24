# 90s-levels

My Duke Nukem 3D and Quake levels from the 1990s, preserved and playable.

These are original maps I built by hand in 1996 and 1997, back when levels were passed between players through fan communities and BBS archives. Nearly three decades later they still run. This repo is where they live now.

Built by Tapio Haaja, a.k.a. **Tapz** / **Täpz** (these days [@tap5a](https://tap5a.io)).

---

## The maps

### DarkCity (Duke Nukem 3D, 1996)

An original single-player and Dukematch level set across a compact city block. Progress runs through exploration, keycard hunting, alien combat, a boss fight, and a final explosive objective.

| Detail | Info |
|---|---|
| Game | Duke Nukem 3D (v1.3) |
| Released | 20 July 1996 |
| Modes | Single Player, Dukematch, Co-op |
| Difficulty settings | Yes |
| Editor | Build |
| Base | New level from scratch |
| New art / music / CON | No |

**Scent-88 review: 91/100** (reviewed by Puritan, 29 November 2017). The review praised the map's lighting, colored and moving light effects, texturing, trimming, clear navigation, and well-planned locations for its era.

Read the original review: https://www.scent-88.com/reviews/D/darkc/darkc.php
(The direct link can misbehave on its own. If it does, go through the homepage at https://www.scent-88.com/ first.)

### The Place of Two Bases (Quake, 1997)

A 2 to 4 player Capture The Flag level. It shipped on the **PC Zone Complete Quake CD** at Christmas 1997, one of over 500 levels on a single disc.

| Detail | Info |
|---|---|
| Game | Quake |
| Filename | 2base.bsp |
| Released | 29 July 1997 |
| Modes | Capture The Flag, Deathmatch (4 starts) |
| Editor | BSP 0.81b |
| Textures | quake101.wad (id), ctf.wad |
| Build time | About 10 to 15 hours |
| Compiled on | Intel Pentium 133 with 16 MB RAM |

---

## How to play

You need a legitimate copy of the original game for each map. These are level files, not standalone games.

**DarkCity (Duke Nukem 3D)**
1. Drop the map file into your Duke Nukem 3D directory (or an EDuke32 setup).
2. Launch with the user map, for example: `eduke32 -map darkcity.map`
3. Tip from the original readme: play it at a low brightness setting. It was built dark on purpose.

**The Place of Two Bases (Quake)**
1. Place `2base.bsp` in your Quake `id1/maps/` folder.
2. From the console, run: `map 2base`
3. Best enjoyed with a CTF mod and a few friends.

Modern source ports (EDuke32 for Duke, QuakeSpasm or vkQuake for Quake) run both without fuss on current machines, including Apple Silicon Macs.

---

## A note on game assets

The map geometry and layouts here are my own work. The games themselves and their original textures, sounds, and art remain the property of their respective owners (Apogee / 3D Realms for Duke Nukem 3D, id Software for Quake). You need the retail games to play these levels. Nothing in this repo redistributes the original game content.

---

## License and credits

Levels by Tapio Haaja, 1996 to 1997. All rights reserved to the original level design.

Per the original 1997 readme, The Place of Two Bases may be freely distributed as long as its accompanying text file travels with it. The same spirit applies to everything here: share it, play it, keep the credit intact.

Review quotes and score courtesy of **Puritan / Scent-88**.
