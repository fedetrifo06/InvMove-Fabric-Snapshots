<h1>InvMove (Fabric) - For 1.18 Snapshots<br>
</h1>

### Minecraft Fabric mod that adds the ability to walk around while in inventories

### NOTE: This Fabric version is still a WIP.<br>It is missing the mod compatibilities that the Forge version has.<br>If you come across any problems, please [report them on the issues page](https://github.com/PieKing1215/InvMove-Fabric/issues).<br>
<br>

![](https://raw.githubusercontent.com/PieKing1215/InvMove-Forge/master/demo/demo.gif)

_(this gif is from the Forge version for now but it works the same)_

Allows for moving, jumping, sprinting, etc. from within inventories.

Also disables the darkened background in inventories that don't pause the game.

Both features can be toggled on or off per-inventory in the config menu.

This mod is client-side, but it may raise alarms if used on servers with anticheat.<br>
I take no responsibility if you get banned or something because you used this on public servers.

Made after [I couldn't find an existing mod for this](https://redd.it/egwe8w).

### [Releases](https://github.com/PieKing1215/InvMove-Fabric/releases)

## Config (In-game)
<details>
  <summary>Click to expand.</summary>

![](https://raw.githubusercontent.com/PieKing1215/InvMove-Fabric/master/demo/where_config.png)
<img src="https://raw.githubusercontent.com/PieKing1215/InvMove-Fabric/master/demo/config_screen.png" alt="alt text" width="657" height="528">
### InvMove has an in-game config menu which can be accessed from the mod list using the [Mod Menu](https://www.curseforge.com/minecraft/mc-mods/modmenu) mod.<br>
In the config menu, you can find several options:<br>
#### General:
- Enable: Enable the entire mod
- Debug Display: Enables a debug overlay that can help debug compatibility problems.

#### UI Movement:
- Move In Inventories: Enable movement in inventories
- Allow Sneaking: Allow sneaking in inventories (disabled by default because it's distracting when shift-clicking)
- Allow Jumping: Allow jumping in inventories
- Allow Dismounting: Allow dismounting from mounts in inventories (overrides "Allow Sneaking" while on a mount)
- Text Field Disables Movement: Disable movement when a text field is focused (like search bars or in an anvil)
- (Expandable categories that let you enable/disable movement for certain inventories)

#### UI Background:
- Hide Inventory Backgrounds: Hides the background tint while in inventories.
- (Expandable categories that let you enable/disable the background for certain inventories)
  
</details>

## Compatibility / Mod Support
<details>
  <summary>Click to expand.</summary>

InvMove has specific support for certain mods, <strike>but any GUIs from unrecognized mods are added into the config dynamically and can be manually enabled.</strike> (not ported yet)<br>
<strike>Unrecognized GUIs will only appear in the config once they have been opened/seen in-game.</strike>

Explicitly supported mods have their own sections in the config, and come with tested default settings.

If you find problems with any of the explicitly supported mods, please start a ticket in the [issue tracker](https://github.com/PieKing1215/InvMove-Fabric/issues).<br>
If there's a mod you want to be added, also please start a ticket in the [issue tracker](https://github.com/PieKing1215/InvMove-Fabric/issues), <strike>especially if it doesn't work enabling it from the "unrecognized" section of the config</strike>.

InvMove Fabric explicitly supports the following mods (as of version 0.1.0):
- [Roughly Enough Items Fabric (REI)](https://www.curseforge.com/minecraft/mc-mods/roughly-enough-items) (1.16-1.17)
  
</details>

## Usage

Feel free to use in packs if you wish.

Do not download this mod from anywhere other than the InvMove-Fabric GitHub, Curseforge, or Modrinth page.<br>
This mod may not be reposted to any other third-party websites.<br>
[#StopModReposts](https://stopmodreposts.org)

The mod is licensed under the [GNU Lesser General Public License v3.0](https://github.com/PieKing1215/InvMove-Fabric/blob/master/COPYING)

## Upcoming
Porting the unrecognized GUIs feature from the Forge version
