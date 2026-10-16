# Credits & licences – Prototype B (Daniel Thomas 2D layout)

**This build contains NO art by Daniel Thomas.** Every tile, plant, tree and animal is a labelled placeholder shape drawn in code at the native 128×128 tile scale of Daniel Thomas's "2D Hand Painted" series. No preview images were used. No generative-AI art or audio.

Checked 2026-10-17: https://danielthomasart.itch.io has no free/sample/name-your-price pack. Everything is paid (the only free item is a web demo of a Unity character asset, which ships no downloadable art). Licence per the artist's itch comments: commercial use allowed; don't redistribute the raw assets.

## What to buy (to drop in)
| Pack | URL | Price (itch) | Use |
|---|---|---|---|
| 2D Hand Painted – Grassland Tileset (245+ 128px tiles, seasonal variants) | https://danielthomasart.itch.io/2d-hand-painted-dungeon-tileset (this is the Grassland page; the URL slug is misleading) | $13 | dirt/grass ground, grass cover, flowers, bushes, large trees |
| 2D Hand Painted – Extra Objects Tileset (2048² sheet, 128px) | https://danielthomasart.itch.io/2d-hand-painted-extra-objects | $9 | rocks, dead trees, plants, small trees |
| Optional: full 7-pack bundle | https://itch.io/s/10610/2d-hand-painted-tileset-pack | $65 | Snowland/Town etc. for later biomes |

Minimum spend: **$22** (Grassland + Extra Objects). Daniel Thomas does **not** sell animals. You'd need a separate, matching painted top-down animal source (still to be picked).

## Drop-in slots (put PNGs in `assets/`; missing files fall back to placeholders)
ground_dirt.png, ground_grass.png (128×128) · grass_cover.png · flowers.png · shrub.png · bigbush.png (128×128) · tree_s.png (128×256) · tree_l.png (256×384) · centre_tree.png (384×576) · dead_tree.png (128×205) · rock.png (128×128) · animal_rabbit/fox/deer.png (96×96, facing right).
Keep `assets/` out of any public repo if the licence forbids redistributing raw files. Ship them only inside the built game.
