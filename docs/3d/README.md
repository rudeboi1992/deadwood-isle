# Deadwood Isle 3D map (public copy)

A browser viewer of the Miscreated island Deadwood Isle built from the game's own level files: terrain, every placed
building and prop, roads, water, trees, sewers, mines and bunkers. Open `index.html` from any static web host
(GitHub Pages works) - the page loads three.js from a CDN and reads the data files next to it.

This copy shows places, vendors and the shrine only. Player positions, vehicles, bases, stashes and pins are not included.

Controls: drag to move, right-drag to turn, wheel to zoom. Tap anything to identify it, then "Walk here" to walk the
island at eye level (W A S D, Space jumps, F uses ladders, G flies). "Streets" draws the roads like a paper map.

Data files (about 100 MB): models_hi/lo (meshes), instances.bin (placements), terrain_8m/4m.bin (heightmaps), roads.bin,
water.bin, holes.bin, passages.bin (underground passages), entrances.json, trees.bin, meta.json, data_public.json.
