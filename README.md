# The Long Drive × Garry's Mod

A separate Garry's Mod gamemode is planned to bring The Long Drive's real vehicles and items into Garry's Mod, with player movement and driving tuned toward The Long Drive.

## Intended first version

- Spawn on the Garry's Mod map the player selects.
- Support solo play and two-player sessions.
- Use The Long Drive's real vehicles and items from each player's own Steam installation.
- Tune on-foot and driving physics toward The Long Drive.

## Game requirements

- **Garry's Mod** is the host game.
- **The Long Drive** supplies the real content. Its game files must be read from the player's own Steam installation; its assets will not be included in this repository or a release.

## Status

The repository now has an early Garry's Mod gamemode shell in `gamemodes/tldgm`. It derives from Sandbox, so maps retain their normal spawn points. The shell is not yet integrated with The Long Drive and has not been tested in game.

The Long Drive uses Unity/Mono and Garry's Mod uses Source. The asset conversion path, actual vehicle/item integration, and physics match still need a feasibility prototype. Multiplayer is intended for two players, but capacity controls and joining have not been implemented or tested.

No Melty release is ready: the actual mashup features, one-click launch behavior, and a real gameplay capture still need to be built and checked. The repository does not contain game assets or look-alike replacements.

## License and credits

The project license and remix permission have not been chosen. The Long Drive and Garry's Mod remain their creators' property; this repository includes no assets from either game.
