# **General Settings**
These settings apply to our Space Engineers server. If a setting is not mentioned, then it is safe to assume it is the vanilla default for the game.

### Rates:
**Player Inventory** - _5x_
**Block Inventory** - _1x_
**Welder/Grinder Speed** - _2x_
**Assembler/Refinery Speed** - _1x_<br>

**Please use the command `!cleanup` in-game to see the full list of cleanup rules.**

Cleanup is run approximately every hour. Here are the things that will be affected by this cleanup and removed:

1) All Space Pirate grids that aren't trade stations and are at least 10km from any player.
2) All grids owned by Nobody at least 1km from any player. This includes grids built by players that don't have any functional blocks with a control panel.
3) All grids inside a planet (stuck below the ground. Digging into the ground is fine).
4) All NPC ships at least 10km from any player.
5) All grids with the word Grid in its name at least 500m from any player. Every newly created grid has a name like "Small Grid xxxx", and must be renamed or will be purged. Use the chat command "!grids list" to get a list of all your grids.
6) All grids belonging to factions that haven't had any members log in within the past 30 days.
7) All floating objects.