Flametal v0.3.3 - a native engine for Dungeon Keeper II
https://github.com/nasedkinpv/Flametal

You need your own copy of Dungeon Keeper 2 (GOG 1.7 recommended); no game files are included.
On the first start Flametal looks for it (GOG, Steam, Wine/CrossOver/Lutris installs) or asks for
its folder - the one with Data in it - and remembers it. The game's files are only read.

Serve this folder over http(s) (python3 -m http.server) and open index.html in a browser with WebGPU (Chrome, Edge).

Your settings, saves and own mods: the browser's storage for this page
Another copy of the game later: start it with --choose-game.
