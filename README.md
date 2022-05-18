# General
Starcraft 2 Archipelago Randomizer will randomize when you obtain unit unlocks, armory upgrades, and labatory research through the Wings of Liberty campaign. The logic makes sure that each game you play is beatable.

Unlike traditional randomizers, this randomizer will not alter the rom or exe of the game, instead it loads the game normally and alters its state in memory.
Save files will be loaded & stored in folder different from the normal game so they are not at risk.

Armory upgrades, Labatory research, and Mercenary unlocks will not be purchasable normally.  Instead, these are obtained by doing side objectives on a mission, completing the objective will instantly give you a random unlock/upgrade for the rest of the campaign.

# Installation \ Startup
Download latest Starcraft2_Data zip file from the release page https://github.com/TheCondor07/Starcraft2ArchipelagoData/releases

Locate the file directory of your Starcraft 2 installation, this can be done in the Blizzard Launcher by clicking the gear icon next the play button for Starcraft 2 and then clicking 'Show in Explorer'.

Extract Starcraft2_Data.zip into your Starcraft 2 directory.

Either navigate into the Support64 folder of your Starcraft 2 installation and copy icudt52.dll, icuin52.dll, icuuc52.dll files, pasting them into the lib folder of your Archipelago installation.  These dlls are also available through the release page as well.

The randomizer should now be playable through the Starcraft 2 Client application in your Archipelago installation.

# Gameplay changes
* Both versions of each branching mission is available to play and is required to be played to get all items, IE: Havens Fall/Safe Haven.
* Conflicting researches in the labatory are both available except for the ones outlined within the Starcraft 2 yaml file.
