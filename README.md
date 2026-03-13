# ATM10 Hostile Mobs Data Pack

**Author:** [Hailey-Ross](https://github.com/Hailey-Ross/)  
**Version:** 0.0.1  
**Minecraft Version:** __NEOFORGE__ 1.21.1  
**Modpack:** [All The Mods 10](https://www.curseforge.com/minecraft/modpacks/all-the-mods-10)

---

## Overview

Adds a `#spawn:hostiles` entity type tag covering all hostile mobs from vanilla Minecraft and All The Mods 10, enabling easy and consistent command targeting across mods.

---

## Features

- Defines the `#spawn:hostiles` entity tag for all hostile mobs
- Covers **vanilla Minecraft** and the following ATM10 mods:
  - Twilight Forest
  - The Aether
  - Ice & Fire
  - Cataclysm
  - Deeper & Darker
  - The Undergarden
  - The Bumblezone
  - Iron's Spellbooks
  - EvilCraft
  - Friends & Foes
  - Naturalist
  - All The Modium
  - Ars Nouveau
  - Occultism
  - Eternal Starlight
  - Mahoutsukai
- All mod entities use `"required": false` so the datapack works even if a mod is not installed

---

## Included Functions

| Command | Description |
|---|---|
| `/function spawn:kill_32` | Kills all hostile mobs within 32 blocks |
| `/function spawn:kill_64` | Kills all hostile mobs within 64 blocks |
| `/function spawn:kill_128` | Kills all hostile mobs within 128 blocks |

---

## Installation

1. Download the datapack `.zip`
2. Place it in your world's `datapacks` folder:
   ```
   saves/<world_name>/datapacks/
   ```
3. Run `/reload` in-game or restart the server

---

## Usage

Target all hostile mobs in a command using the entity tag:

```
kill @e[type=#spawn:hostiles]
@e[type=#spawn:hostiles,distance=..64]
```

Or use the built-in functions for quick cleanup:

```
/function spawn:kill_32
/function spawn:kill_64
/function spawn:kill_128
```

---

## Compatibility

- Designed for **All The Mods 10** on **NeoForge 1.21.1**
- All non-vanilla entries are marked `"required": false` and will be safely ignored if the corresponding mod is absent

---

## License

This project is open source. Feel free to use, modify, and distribute with credit.
