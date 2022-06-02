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

# Issues
Sometimes you may see the message 'Archipelago unable to connect or has lost connection to Starcraft 2' appear in Starcraft 2.  If this appears at the start of a mission it is 99% of the time a non-issue and you an error that you can safely ignore.  On some computers the time it takes for the client to connect to Starcraft 2 causes it to think connection was lost when it wasn't.

# Game isn't launching when I type /play
If your Starcraft II is not installed at C:/Programs Files(x86)/Starcraft II, there may be issues trying to run your game.  If you run into that issue, the workaround below may help, but if not your only solution for now is to change your install directory to C:/Programs Files(x86)/Starcraft II or wait until we find a solution to the issue.

First check the log file for issues (stored at [Archipelago Directory]/logs/SC2Client.txt. There is sometimes an issue 
where the client can not find Starcraft 2.  Usually Documents/Starcraft 2/ExecuteInfo.txt is checked to find where 
Starcraft 2 is installed. On some computers particularly if you have OneDrive running this may  fail.  The following 
directions may help you in this case if you are on Windows. 

1. Navigate to '%userprofile%'.  Easiest way to do this is to hit Windows key+R type in %userprofile% and hit run or 
type in %userprofile% in the navigation bar of your file explorer. 
2. If it does not exist create a folder in her named 'Documents'.
3. Locate your 'My Documents' folder on your pc.  If you navigate to 'My PC' on the sidebar of file explorer should be a
link to this folder there labeled 'Documents'.
4. Find a folder labeled 'Starcraft 2' and copy it.
5. Paste this Starcraft 2 folder into the folder created or found in step 2.

These steps have been shown to work for some people for some people having issues with launching the game.  If you are 
still having issues check out our [Discord](https://discord.com/invite/8Z65BR2) for help.

# Gameplay changes
* Both versions of each branching mission is available to play and is required to be played to get all items, IE: Havens Fall/Safe Haven.
* Conflicting researches in the labatory are both available except for the ones outlined within the Starcraft 2 yaml file.
