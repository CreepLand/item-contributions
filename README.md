# Item contributions
Contribute to assigning a rarity or adding/removing/modifying attributes to each vanilla item.
## Valid rarities
The valid rarities are the following: `COMMON`, `UNCOMMON`, `RARE`, `EPIC`, `LEGENDARY`, `SPECIAL`. If a item has no rarity specified to it, it will be `COMMON` by default. The `SPECIAL` rarity is reserved for items like the Debug Stick, Command Blocks, End Frames, etc.
## Valid materials
You can get a list of valid materials in Minecraft 1.16.5 from [here](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html)
## Contributing to attributes
If you feel that an attribute specified in one of the files is not balanced, incorrect or it's not defined, feel free to change it as long as the changes made make sense. 
The attributes that we currently use are: `damage`, `attack_speed`, `health`, `defense`, `cooldown` and `feeds`. The `feeds` attribute is reserved for the amount of food points that a comestible item regenerates. See [the Minecraft wiki](https://minecraft.fandom.com/wiki/Hunger). We may add a `saturation` attribute later, but it will not be shown in-game in order to make lores cleaner and easier to understand.
