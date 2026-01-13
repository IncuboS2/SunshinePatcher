# Sunshine Patcher (Legacy Version)
Legacy Version is a separated version of Sunshine Patcher which is intended for older versions of Windows.

## Features

 - Can install on top of the extremely common (and cheap) 1998 port of Sonic R, providing wider accessibility to the PC version of the game.
 - Runs perfectly on modern Windows installations, with little to no configuration required, unlike the vanilla 1998 port.
 - Installs Sonic R Mod Loader into the game, allowing for robust modding support, as well as several additional features:
	- Removes the need for a disc to be inserted.
	- bass_vgmstream audio support with looping and pausing.
	- properly bordered windowed mode with custom window size options.
	- custom resolution with proper widescreen support.
	- better borderless windowed mode support.
	- improved game frame rate stability for modern hardware.
	- an array of interesting cheat codes.
	- maybe even more as the mod loader is in active development.
 - Downloads the latest version of the Sonic R Mod Loader if possible during installation to make sure you're up to date at the time of install.
 - Includes RemoveStrays, a mod to fix various stray pixels in the Menu and HUD throughout the game.
 - Includes ADX Music, a mod that changes out the 2004 port's default `.son` files for much more space efficient `.ADX` format audio that even loops in some cases when appropriate.
 - Includes Saturn Style Colors, a mod that improves the lighting of the game to further match the Sega Saturn original and makes Radiant Emerald semi-transparent again.
 - Includes EggRobo Texture Fix, a mod that fixes a minor bug involving the texture of EggRobo.

## Usage

1. Install Sonic R from your retail disc or an ISO image on your PC wherever you'd like. (I recommend `C:\Program Files (x86)\Sega\SonicR`, personally.) If you get an error saying "This app can't run on your PC", right click on the disc drive and choose `Open` or `Explore` and double click on `Setup.exe` instead.
2. Do not install DirectX 6 when prompted. You do not need to install the DirectPlay Windows Feature, and ignore any errors that appear after the installation completes from it trying to open the 1998 game. Ignore this step if you by some chance actually have the 2004 port, which also works.
3. Download the latest Sonic R Updater and run it.
4. It should auto-detect the installed location of Sonic R, simply click next or browse to the correct location in the event that it was unable to find the correct path.
5. Proceed with the installation. Leave the box checked if you'd like to get familiar with the Sonic R Mod Manager right away.
6. Shortcuts to `Sonic R`, `Sonic R Mod Manager`, and `Sonic R Help` are all added to your Windows Start Menu, use the shortcuts there to play the game.

As time goes on, Sonic R Mod Loader may be updated, and thus, the one you installed will become out of date. You can update Sonic R Mod Loader by running Sonic R Updater again, or you can [download it manually](http://mm.reimuhakurei.net/misc/SonicRModLoader.7z) and drop the archive contents into your Sonic R Installation folder.

## Usage (Steam Deck)

__Prerequisites:__
 - GE-Proton9-27. (I recommend using Wine Cellar to do this.)
 - Protontricks. (I recommend obtaining it from the Discover Store.)

1. Copy the contents of the root directory of your retail disc into a folder named `SonicR` and transfer it to your Steam Deck using whatever means you'd like.
2. Move the `SonicR` folder wherever you like to put sideloaded Windows games on your Steam Deck. **It needs to be a place you can navigate to within a file browser opened by a program running under Protontricks.**
3. Right click on `sonicr.exe` and choose `Add to Steam`. Navigate to this entry in Steam and open it's `Properties` menu. Change the name to "Sonic R" and then click on the `Compatibility` section. Tick the box to enable forcing a specific proton build, and set it to GE-Proton9-27.
4. Close properties and attempt to run Sonic R from Steam. It will fail to run, but will generate the needed prefix for Protontricks.
5. Download the latest Sonic R Updater and run it under the `Non-Steam shortcut: Sonic R` prefix with Protontricks.
6. Click `Browse...` and navigate to the folder where your `sonicr.exe` is located. If you cannot find it, then you probably need to put your `SonicR` folder somewhere accessible from this menu. After that, click next and complete the installation.
7. Open `SonicRModManager.exe` under the `Non-Steam shortcut: Sonic R` prefix with Protontricks.
8. From this menu, you can manage mods, edit graphics settings. On Steam Deck, under graphics, I suggest unchecking "Windowed" and checking "Windowed Fullscreen" and setting the resolution to 1067 x 800 for 4:3, or 1280 x 800 for 16:10.
9. Click Save once you've made your changes.

The Steam Deck runs Sonic are perfectly, as you might imagine, but you might run into issues with the controls. By default, the L3 (Left Stick Click) is mapped to "Start". Use this to get into the Options menu and configure the controls properly. I also suggest editing the controls within Steam to make playing more comfortable as desired.

## Troubleshooting &  Issues
**Problem:** When I go to install Sonic R I get a "This app can't run on your PC" error.

**Solution:** As stated above, the Sonic R (1998) _autorun_ program cannot run on 64-bit Windows due to being a 16-bit executable. To work around this, right click on the disc drive and choose "Open" or "Explore" and double click on `Setup.exe` instead. This should allow you to install Sonic R properly.

## Uninstall

What's that? You don't like this patch? You have issues with the latest versions? Want to update?

Well, in any case, to remove the patch, you basically need to uninstall Sonic R:
Open up `Control Panel`, then `Programs` → `Uninstall a Program` → `SonicR`, and then, after the Uninstall has finished, navigate to the Sonic R folder and delete any remaining leftover files. You may as well leave behind the `save` and `ghost` folders if you wish to avoid losing any save games expectially when you want to update or reinstall Sunshine Patcher. Also, you should keep the `mods` folder as well if you've developed any mods and wanted to keep working on them.

Lastly, the Start Menu shortcuts can be removed by right clicking one of them in the Start Menu, and going to `More` → `Open file location`, followed by clicking the Up One Level button (↑) and deleting the `SonicR` folder in `Sega`. If you don't have any other Sega games installed, you may also want to delete the `Sega` folder to remove it from your Start Menu as well.

## F.A.Q.

**Q:** Is this speedrun legal?

**A:** No, but [CheatFreak did requested it](https://www.speedrun.com/Sonic_R/thread/zc91h) in the original project.
A speedrun category could be made, but it hasn't thus far. Technically, neither ADX Music or RemoveStrays are code based mods, and thus have no effect on how the game performs or behaves in any way, outside of extremely minor, nearly unnoticeable cosmetic differences in UI Textures and Audio Quality.


**Q:** 2004 port? Why haven't I heard of this before?

**A:** Even though it's treated as a reprint of the 1998 port, it's a different version, which does remove some features but it makes it a bit more friendly with modern versions of Windows. Sadly, it was only released in certain regions like the UK and in Australia and also in limited quantities, making it both obscure and quite rare to find. In addition, it's much more confusing when trying to track down a copy of it, as the boxes of this version aren't labeled properly, making it pretty difficult to distinguish these 2004 port copies with the more common 1998 port copies.



**Q:** How do I play in network multiplayer mode?

**A:** The short answer is you can't. The long answer is that the 2004 port of Sonic R this is based on removed all network play from the game for whatever reason. It's theroretically possible for it to be modded back or for someone to create an online multiplayer mod, similar to [SA2 Battle Network](
https://github.com/michael-fadely/sa2-battle-network), but that's probably not going to happen, since there seems to be little interest in modding Sonic R generally. Please do let me know if you make that mod though, I'd love to include it if it ever comes to exist.



**Q:** How to Compile the source?

**A:** Clone the repository and install the two dependencies; Inno Setup first and Inno Download Plugin (which should be installed in the same directory as Inno Setup's directory or it won't work!). You might also opt to install Inno Script Studio which was used heavily during development of the original project. Anyway, just compile the ISS script file and you're golden.

## Credits
	
#### CheatFreak
 - Sonic R Updater project leader
 - InnoSetup Script Writer
 - Pascal Code Writer 
 - ADX Music Mod
 - RemoveStrays Mod

#### Carlmundo
 - Pascal Code Writer
 - Lead Coder of BetterSADX and Tomb Raider AutoPatch, which some of the Pascal code in this project is based on
 - Special Thanks, for being a good friend
 
#### MainMemory
 - Sonic R Mod Loader Programmer
 - Special Thanks, without them this project couldn't exist
 
#### InvisibleUp
 - Saturn Style Colors Mod
 - EggRobo Texture Fix Mod
 - Widescreen support in the Sonic R Mod Loader
 - Special Thanks, for making some cool Sonic R mods

## Legal Junk
Sonic R Updater, along with it's source are provided without a license of any kind, and are distributed as-is. All resources included are used without permission.

The included game resources may be removed from the repository at a later date- replaced with a list of the intended resources in this readme instead. It's not decided if/when this will happen, but it may eventually.
Legacy Version
