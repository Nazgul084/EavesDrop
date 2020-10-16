![MainFrame](eaves1.png)
![MainFrame](eaves2.png)

This is my attempt to get this addon going as I am kind of addicted to it since 2008!

The goal is to make it work under latest game version (currently 9.0)

I haven't yet set this up with Curse/WoWInterface, hence it cannot be downloaded using AddOn tools such as Twitch or [WowUp](wowup.io).

For now you need to install it manually after downloading [a zip file](https://github.com/spamwax/EavesDrop/releases/latest).

These instructions assume you have extracted (or are about to extract)
this .zip file with "Retain directory structure" enabled.

## Installation Instructions

  1. Go into your WoW installation folder
     (e.g. C:\Program Files\World of Warcraft\)

  2. Go into the Interface sub-folder

  3. Go into the AddOns sub-folder (if you dont have one, create it)

  4. Copy/Extract this addon's folder into the AddOns folder.

### Verification

  The following folder paths will exist within your WoW Install directory:

    EavesDrop:
    Interface\AddOns\EavesDrop\
    Interface\AddOns\EavesDrop\libs\
    Interface\AddOns\EavesDrop\locals\

  Look for the following (wrong) files as evidence of common mistakes:

  * If you have Interface\AddOns\EavesDrop.toc
    then you've extracted the zip file's contents without its
        folder structure, or copied the contents without the parent
        folder.
  * If you have Interface\AddOns\EavesDrop\EavesDrop\EavesDrop.toc
    ... then you've extracted the zip file into a folder an extra
        level deep. Move the files and any sub-folders up one level
        and remove the extra folder.


Original addon is on [CurseForge](https://www.curseforge.com/wow/addons/eaves-drop).

***********************************
### Original logs & readme by grayhoof
EavesDrop 2.1 (logs from before moving to github by spamwax)
***********************************

8.0.1 fix: download by clicking "Clone or download" > Download ZIP
              alternatively just copy/paste from EavesDrop.lua over your own version
    ***power gains won't display the type of power in the window***


Website - http://grayhoof.wowinterface.com/

What is it? - A simple combat log that displays events similar to how SCT/D would in a log, using icons to display spells/skills. It seperates incoming events (left side) from out going events (right side) from misc. events (middle).

What all can it show?
- Your hits, spells, misses, heals, etc...
- Incoming damage, spells, heals, buffs, debuffs, etc...
- Power gain
- Honor, Reputation, SKill, and Experience gain
- Mob/People you have slain
- Combat start/stop
- Timestamps and details in tooltips

Where did it come from? - Original idea by Bant. Coding help/samples from Andalia`s SideCombatLog and CombatChat.

How do I use it? - Unzip EavesDrop into your interface\addons directory. For more info on installing, please read install.txt. Now just run WoW and once logged in, you will see the EavesDrop in the middle of your screen. Left click the EavesDrop Tab to drag it. Right click the EavesDrop Tab to see the options menu.

FAQ
My peridoic damage is not showing up in the combat log or on the screen! How do I fix it? - You have turned off periodic damage on the Advanced Options under Interface options. Make sure the "Periodic Damage" check box is checked, even if you have Damage unchecked.

How do I reset EavesDrop or load another users settings? - EavesDrop uses the Ace3 profile system. By default all characters have their own profile. You may change this for each character using the Profile area of the option menu. You can reset the options for the current profile using the Rest option in the menu.

How do I change the fonts? - EavesDrop now supports ShareMedia, so just select your font from the options menu.

Support
Please post all errors and suggestions on http://grayhoof.wowinterface.com/ using the provided forms.

Version History
2.1 - Fix for rep and honor. Fixed posting events to chat. Added item buffs to buff events. Clean up of combat event processing. Cleanup of combat log pasting, xp gain, and pet happiness. Convert to LibShareMedia-3.0.
2.0 - Converted to WoW 2.4 Combat Log. Converted to Ace3. Added SharedMedia support for font. Tons of code cleanup and performance changes. Moved options menu to WoW 2.4 Addons Menu.
1.5 - Separated out Buff and Debuff fading events. Added tooltip Anchoring options. Added ability to hide Tab. Added new options for opening/closing frames.
1.41 - Fixed bug regarding summary calculations and some skills.
1.4 - Added Waterfall as optional way to view options, Shift+Right Click on tab. Changed to use SpecialEventsLib for buffs/debuffs. Added new optional Combat Summary when combat stops. Added new way to scroll text by combat flags, ctrl+click or ctrl+mouse wheel. Added buff and debuff names that can be shortened using abbreviation or truncation. Added shift+click to add events to Chat Edit Box. Added ability to change Spell School Colors. Cleaned up Drain/Leech events.
1.3 - Added new high value skill stat tracking (incoming/outgoing damage/heals per character). New highs flagged with !'s. Open full history with icon near main tab. Added pet portrait to texture for pet events. Fixed overhealing issue. Changed table update methods. Removed Compost.
1.2 - Converted to WoW 2.0 standards. Converted to using AceLocale 2.2 and BabbleLib 2.2. Minor random tweaks.
1.1 - Upped history count by more than double. Fixed HOT's when in party. Added Frame Fade option. Added Skill events. Added Time Stamp option. Cleaned up pet events for better performance and to account for totems/summoned pets. Added Heal and Mana filers.
1.01 - Library update
1.0 - Initial Release

