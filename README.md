[![Discord](https://img.shields.io/discord/428813657816956929?color=7289DA&label=discord)](https://discord.gg/FrBHHCk)
![Uptime Robot ratio (30 days)](https://img.shields.io/uptimerobot/ratio/m787908862-2276b40426acf2ff58677e3f)
![Uptime Robot status](https://img.shields.io/uptimerobot/status/m787908862-2276b40426acf2ff58677e3f)
[![patreon badge](https://img.shields.io/badge/dynamic/json?color=e64413&label=patreon&query=data.attributes.patron_count&suffix=%20patrons&url=https%3A%2F%2Fwww.patreon.com%2Fapi%2Fcampaigns%2F727078)](https://www.patreon.com/DaPorkchop_)
[![Keybase BTC](https://img.shields.io/keybase/btc/DaPorkchop_)](https://www.daporkchop.net/donate)

## In progress
- [FarPlaneTwo](https://github.com/PorkStudios/FarPlaneTwo)
  - **Testing:**
  - **In progress:**
    - Modularize and abstract everything in order to be able to support multiple game versions at once
  - **On hold:**
    - Congestion control for terrain loading (to prevent timeouts when the server loads terrain too fast on a slow connection)
    - Improved mesh scaling
    - Populators in rough generators
    - Rough generators for more world types
    - Handle non-solid blocks correctly
    - Compatibility rendering mode
    - Improved support for OptiFine shaders
- [BuildTheEarth/Terra++](https://github.com/BuildTheEarth/terraplusplus)
  - **In progress:**
    - Generate high-resolution global elevation datasets
    - Generate simplified OpenStreetMap data tiles for use at low zoom levels
  - **On hold:**
    - Make `BVH<>` support arbitrary bounding polygons

## On Hold
- [MCWorldLib](https://github.com/PorkStudios/MCWorldLib): make API completely version-independent
- [SaveSearcher](https://github.com/DaMatrix/SaveSearcher): finish rewrite (waiting on MCWorldLib)

## Planned
- [Pork2b2tBot](https://github.com/PorkStudios/Pork2b2tBot): Plugin API
- [PorkLib](https://github.com/PorkStudios/PorkLib)
  - `:binary` - 64-bit buffers+memory maps
  - `:compression` - better streaming API
  - `:encoding` - revamped config system
  - `:graphics` - native image encoding+decoding
  - `:primitive` - sorted and multidimensional collections

