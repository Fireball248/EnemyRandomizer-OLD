# EnemyRandomizer
A working version of Kerr1291's Enemy Randomizer mod for Hollow Knight.

## Installation
If you can find it, move the EnemyRandomizer.dll file into `<Path-To-Hollow Knight>\Hollow Knight\hollow_knight_Data\Managed\Mods\`.

Otherwise, either:

Download the mod installer from the HK discord and use that to install it, although it may not be up-to-date.

OR

Find the .dll file on the modding drive from the HK discord.

This mod requires both the modding API and ModCommon, both of which can be found on the discord.

## Usage
Click the [LOAD ENEMY RANDOMIZER] button in the top-left of the main menu to load the randomizer.

By default, the randomizer will change each enemy type into another random type, and this will remain constant between rooms. This behaviour can be changed, as below.

## Settings
 - Chaos Mode - Each enemy will be fully randomized with no restrictions when you enter a new room. Enemies of the same type can be changed into different things.
 - Room Mode - Each enemy type will be re-randomized each time you enter a new room, but it will still change every enemy of that type.
 - Randomize Geo - Randomizes amount of geo dropped by enemies
 - Custom Enemies - Allows custom enemies to be added to the randomizer
 - Godmaster Enemies - Allows enemies from the Godmaster expansion to be included in the randomizer. This includes Absolute Radiance, Pure Vessel, Winged Nosk, Mato, Oro, Sheo, Sly and Eternal Ordeal enemies.
 - (Cheat) No Clip - Turns on no clip - to be used in case of a bug that blocks progression by normal means, e.g. a door not opening after a boss has been killed.

## Known Bugs
Certain bosses will not spawn if they have been killed elsewhere, such as Flukemarm, but their item drops will still function as normal and be found in the empty boss arena.

Trial of the Fool is broken - don't do it.

If you have any other problems, feel free to ping me (@Fireball248) on the HK discord.

## Development
If you load the project file into an IDE, you will get many missing reference errors. To fix, add `<Path-To-Hollow Knight>\Hollow Knight\hollow_knight_Data\Managed\` to the project's references.

If you still have issues, ensure that the modding API and ModCommon are installed in your HK directory.

## Credits
Original Code - Kerr1291 (https://github.com/Kerr1291/EnemyRandomizer)

Fixes and Current Developer - Fireball248

Fixes to the Modding API that allow this to work with certain other mods - 56 (https://www.twitch.tv/5fiftysix6)
