# Need/Greed Roll System for Erenshor

A BepInEx mod that adds a World of Warcraft–style **Need/Greed/Pass** loot roll to Erenshor.  
When a loot window opens **and you’re in a group**, everyone (player + Sim party members) rolls.  
The winner automatically receives the item; corpses are cleaned up so you can’t re‑loot.

---

## Features

- ⚖️ **Need / Greed / Pass UI** (N, G, P keys – 15s timeout → Greed).
- 🤖 **Auto rolls for Sims** (upgrade-aware; optional loot rules).
  (Fallback injects directly into Sim inventory if their bags are “full”.)
- 🧹 **Corpse cleanup**: Items removed from loot window/corpse after award.
- 🗣️ **Sim chatter**: Random win/lose lines.
- 📏 **LootRules system**: force pass on junk, need on upgrades, can‑use checks, stat-based upgrades.

---

## Installation

1. Install **BepInEx 5** (x64) in your Erenshor folder (same place as `Erenshor.exe`).
2. Drop the compiled `LootRoll.dll` in Bepinex/Plugins Folder
