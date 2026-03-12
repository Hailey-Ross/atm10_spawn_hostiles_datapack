ATM10 Spawn Hostiles datapack

What this pack adds
- Entity type tag: #spawn:hostiles
- Helper functions:
  - /function spawn:kill_32
  - /function spawn:kill_64
  - /function spawn:kill_128

Install
1. Put this folder or zip into world/datapacks/
2. Run /reload
3. Confirm with /datapack list

Use with a command block
- Repeating, Always Active command block near spawn:
  execute positioned 0 64 0 run function spawn:kill_64

Or directly:
  execute positioned 0 64 0 run kill @e[type=#spawn:hostiles,distance=..64]

Notes
- Vanilla hostile mobs are hard-coded in the tag.
- Modded mobs are included as optional entries using "required": false, so the pack still loads if a given mod or entity id is absent.
- ATM10 changes often. If you find one hostile that survives, add its id to:
  data/spawn/tags/entity_type/hostiles.json
