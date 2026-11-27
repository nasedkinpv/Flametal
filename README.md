# Flametal

A native engine for **Dungeon Keeper II** that plays from your own copy of the game: the original's
levels, creatures, rooms, spells and computer keepers, run by a new game core and drawn by a modern
renderer — no Wine, no original executable.

**You need your own copy of Dungeon Keeper 2** (GOG 1.7 recommended). No game files are included.
On the first start Flametal finds your copy (GOG, Steam, Wine/CrossOver/Lutris installs) or asks
for its folder — the one with `Data` in it — and remembers it. The game's files are only read.

## Platforms

| Platform | Renderer | Status |
|---|---|---|
| macOS 26, Apple silicon | Metal 4 (ray-traced shadows on M3 and later) | plays |
| iPadOS 26 | Metal 4 | plays; not distributed here yet |
| Linux x86_64 | WebGPU over Vulkan (SDL3) | plays |
| Windows 10+ x86_64 | WebGPU over D3D12/Vulkan (SDL3) | builds; not yet tested |
| Browser | WebGPU (Chrome, Edge) | first pass |

Downloads are on the [Releases](../../releases) page. The 0.2.x releases there are the earlier,
Wine-based Mac app.

## Status

Flametal is an independent engine compatible with user-supplied DK2 data. Much of the game is
implemented as first passes checked against the original's data and behaviour; it is not yet a
complete or exact reproduction of Dungeon Keeper II.

## Sources and license

Developed in a separate repository; the releases here are built by its CI.
Flametal's own code and content are licensed under the Apache License 2.0 ([LICENSE](LICENSE)).
Dungeon Keeper II is copyright Electronic Arts; this project grants no rights to the game.
