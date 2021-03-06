This project built on:

                   ,---------------------------------------.
                   |   _                     _       ____  |
                   |  (_)___  __ _ _  _ __ _| |_____|__ /  |
                   |  | / _ \/ _` | || / _` | / / -_)|_ \  |
                   |  |_\___/\__, |\_,_\__,_|_\_\___|___/  |
                   |            |_|                        |
                   |                                       |
                   `---------- http://ioquake3.org --------'

# q3now
q3now is an open source Quake 3 Modification project under GPL license.

## Why Quake 3 mod-making?
Quake 3: Arena released at 1999 and a while ago its source codes are made open source.
ioquake3 team still maintains the game engine called idTech 3. The engine also runs on
Linux, MacOS X and Windows platforms.

I personally experienced in mod-making for classic quake, quake 2 and quake 3 engines.
But I never find a chance to focus on releasing a mod due to some restrictions. Apart
from engine and "game media" license issues, I felt dead-end in debugging C code during
chasing some bugs and crashes.

In time, my programming and self-organization skills are improved along with the tools
and platforms. Thanks to source control systems, I can easily revert crashing changes
today.

To derive a product from my old mod codes, I decided to start over my mod-making
adventure on GitHub.

## Concept
q3now is a kind of deathmatch and teamplay mod.

Constructing a new balance with redefined weapons, items and rules is the main focus
of the mod. Things can be annoying during the play, it will be taken care of in time
especially when someone reports it :)

At the same time, I will be looking forward to enrich match and tournament features
in absence of OSP/CPMA.

## Mod Highlights
The major features that implemented so far:
- Challenge Pro Mode physics (enabled default)
- Challenge Pro Mode rules (`+seta g_pro_mode 1`)
- New Health and Armor System
- Proximity Launcher, Nailgun, Chaingun and BFG10K are removed
- New Plasma Gun (called Plasma Rifle)
- New Weapon Balances
- Wall jumps ([youtu.be/RPwSBUZ2Ebw](//youtu.be/RPwSBUZ2Ebw))
- Less falling damage
- New Game Mod: King of the Hill
- New Game Mod: Last Man Standing
- King of the Hill Ghost Mode (`+seta kothflags 1`)
- Offhand Grapple (`+seta g_grapple 1`)
- Instagib mode for instant kills (`+seta g_instagib 1`)
- Excessive mode for speeding up gameplay (`+seta g_excessive 1`)
- Removed redundant concepts (handicap)
- Removed redundant objects (guard, scout, doubler, ammoregen)
- Balanced Rewards
- No player sounds on Cloak (Invisibility)

## Mod TODO list
- Unlagged or ZNudge implementation
- Match and Tournament Improvements
- New Team System
- Spectator Cameras
- New Powerup System
- New Game Mods (Freeze Tag, etc.)
- New Rewards
- New Crosshair
- A modern HUD with new menu system
- New UI fonts
- JUHOX's BrightArena implementation
- Modified shaders
- Armor piercing environment damages (fall, slime, water, lava, etc.)

## Contributing
It is publicly open for any contribution. Bugfixes, new features and extra modules are
welcome. All contributions should be filed on the
[eserozvataf/ioq3](//github.com/eserozvataf/ioq3) repository.

