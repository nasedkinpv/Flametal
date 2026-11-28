# Third-party licenses

What the release packages carry besides Flametal's own code (LICENSE, NOTICE):

| Component | License | In |
|---|---|---|
| SDL3 | zlib | Linux, Windows, web |
| wgpu-native (and the wgpu crates it is built from) | MIT / Apache-2.0 | Linux, Windows |
| Dawn's Emdawnwebgpu | BSD-3-Clause | web |
| Emscripten runtime | MIT / NCSA | web |
| toml11 | MIT | all |
| lodepng | zlib | all |
| dr_mp3 | public domain / MIT-0 | all |

Each text is in this folder. Rebuild them from the pinned versions (tools/native/fetch_wgpu.sh,
fetch_windows_deps.sh, build_sdl3.sh, libs/) when a dependency changes.
