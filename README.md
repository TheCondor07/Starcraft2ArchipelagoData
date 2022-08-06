# General
The StarCraft 2 Archipelago Randomizer will randomize when you obtain unit unlocks, armory upgrades, and laboratory
research through the Wings of Liberty campaign. The logic makes sure that each game you play is beatable.

Unlike traditional randomizers, this randomizer does not alter the ROM or .exe of the game. Instead, it loads the game
"normally" and communicates with it using the StarCraft 2 API.

No save files are affected by the randomizer.

Armory upgrades, Labatory research, and Mercenary unlocks will not be purchasable normally.  Instead, these are obtained by doing side objectives on a mission, completing the objective will instantly give you a random unlock/upgrade for the rest of the campaign.

# Installation / Startup

1. Download the latest Starcraft2_Data zip file from the
[release page](https://github.com/TheCondor07/Starcraft2ArchipelagoData/releases).

2. Find your StarCraft 2 installation folder. Do not open it.
   - You can find this folder using the Battle.net program. Open Battle.net and go to StarCraft II. Click on the gear
     button (next to the "Play" button), then click 'Show in Explorer'. A window should appear with the StarCraft II
     installation folder highlighted.

3. Open Starcraft2_Data.zip. Inside is a Maps folder and a Mods folder. Highlight both of them and drag them _directly_
   onto your StarCraft 2 installation folder.

You have finished all StarCraft 2-specific setup.
Read the general setup guides about how to use the website to generate a game and host a server; you still need to
do both of those things before you can connect to that server using ArchipelagoStarcraft2Client.exe and start playing.

# Issues
If you run StarCraft II in a language other then English, then you will be unable to see Archipelago messages in-game.

Sometimes, you may see the message 'Archipelago unable to connect or has lost connection to Starcraft 2' appear in-game.
If this appears at the start of a mission, it is 99% of the time a non-issue, and you can
safely ignore it.
- On some computers, the time it takes for the client to connect to Starcraft 2 makes it think the
  connection failed even though the connection succeeded.

# Game isn't launching when I type /play or click on a mission
You probably have not put the `Maps` and `Mods` folders in the correct spots. They should end up at `StarCraft II\Maps`
and `StarCraft II\Mods`, where `StarCraft II` is the installation folder described in step 2 above. Triple-check that
you have installed those two folders in exactly those two locations.

If you are still having issues, check out `#tech-support` on our [Discord](https://discord.com/invite/8Z65BR2) for help.

# Gameplay changes
* Both versions of each branching mission is available to play and is required to be played to get all items, IE: Havens Fall/Safe Haven.
* Conflicting researches in the laboratory are both available except for the ones outlined within the Starcraft 2 yaml file.
