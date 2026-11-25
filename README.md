# gw2drops

[![Latest release](https://img.shields.io/github/v/release/ArmonicPvP/gw2drops?include_prereleases&sort=semver&label=release)](https://github.com/ArmonicPvP/gw2drops/releases/latest)
[![Discord](https://img.shields.io/discord/1571860503561506916?label=Discord&logo=discord&logoColor=white&color=5865F2)](https://discord.gg/ku3jxx48Vh)

gw2drops records what drops from what in Guild Wars 2 and shows it on
[gw2drops.com](https://gw2drops.com). It also collects and displays anonymous drop statistics.

## Install

gw2drops runs as an [arcdps](https://www.deltaconnected.com/arcdps/) extension, a [Nexus](https://raidcore.gg/gw2/nexus) add-on, or on its own.

### arcdps

1. Download `gw2drops_collector.dll` from the
   [latest release](https://github.com/ArmonicPvP/gw2drops/releases/latest).
2. Put `gw2drops_collector.dll` in your Guild Wars 2 folder.
3. Start the game. A small window will ask you to **Link to gw2drops.com**. Nothing is uploaded until you link.

### Nexus

1. Open the Nexus Menu in game.
2. Open `Addons`, click `Library` below the search bar, search for `gw2drops`, and click Install.

### Standalone (no arcdps or Nexus, e.g. Linux)

1. Download `gw2drops_collector.dll` from the
   [latest release](https://github.com/ArmonicPvP/gw2drops/releases/latest) and rename it to `d3d11.dll`.
2. Put `d3d11.dll` in your Guild Wars 2 folder. If arcdps is already there, use the arcdps install instead.
3. Linux only: in Steam, set the launch option `WINEDLLOVERRIDES="d3d11=n,b" %command%`.
   In Lutris, add the DLL override `d3d11` = `n,b`.
4. Start the game. A small window will ask you to **Link** to gw2drops.com. Nothing is uploaded until you link.

### Update and Uninstall

To update, close the game and replace the DLL. To uninstall, close the game and
delete the DLL. Your recordings stay on your PC in `%LOCALAPPDATA%\gw2drops`.

## Help

Join the [Discord](https://discord.gg/ku3jxx48Vh).

You must be 18 or older to create a gw2drops.com account.

## Legal

[Privacy policy](https://gw2drops.com/privacy) | [Terms](https://gw2drops.com/tos) | [Legal notice](https://gw2drops.com/legal)

###### gw2drops is an unofficial fan project, not affiliated with or endorsed by ArenaNet or NCSOFT. Use third-party addons at your own risk.

###### © ArenaNet LLC. All rights reserved. NCSOFT, ArenaNet, Guild Wars, Guild Wars 2, GW2, Heart of Thorns, Path of Fire, End of Dragons, Secrets of the Obscure, Janthir Wilds, Visions of Eternity, and all associated logos, designs, and composite marks are trademarks or registered trademarks of NCSOFT Corporation. All other trademarks are the property of their respective owners.
