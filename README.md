X-COM: UFO Defense was such a perfect game. Twenty years ago, when I was a teen, I played this game so much and I loved it so hard. Even though a lot of people and companies tried to embody ideas of this game in their creations, the original plot of UFO Defense has never been improved. Today I am happy, because [a group of people](https://github.com/SupSuper/OpenXcom/graphs/contributors) is reproducing the original plot and the original graphics of this game with great possibilities for mod makers. The name of this project is [OpenXcom](https://github.com/SupSuper/OpenXcom) and fortunately it can be run on Linux. Despite the fact that OpenXcom is awesome I would like to introduce my collection of changes for this game plot and graphics.

##Awesome Guns

This is an awesome modification of the [OpenXcom game](http://openxcom.org).    
Current state: released     
Current plans: rolling-release     
WEB: [https://canadianbeaver.github.io/AwesomeGuns](https://canadianbeaver.github.io/AwesomeGuns)

###Why am I doing it?

Original gameplay of X-COM: UFO Defense has a big problem in the middle and in the end of game. The game can make you feel bored. There are a steam of small UFOs, the monotonous and repetitive missions, the heavy plasma has no alternative...  My suggestion to improve this situation is to make more efficient conventional weapons. Let the soldiers use different pistols, rifles, even grenade launchers and more different types of guns. Also, let the soldiers use different armours with different colours and possibilities. Moreover, let be more explosives in in the battles, more incendiary weapons and more smoke.

I observed [a lot of mods](http://www.openxcom.com/mods) for OpenXcom and found that there are two types of mods. Main ones are simple and perfect, but they do not combine together nicely. Another mods are like a dump of different mods that will never work. Unfortunately, a lot of mods were made for night game's release and do not work for the stable game's release.

I prefer the [Debian](https://www.debian.org/). It is stable, it is simple and it is a minimum necessary. I would like to make a mod with the same ideas. It should be stable, it should work for the stable game release, it should be simple and it should make only necessary changes.

If you have the same preferences, I would like to invite you to create it together.

###How do I make it?

- Primary, I am used to working with the [Debian and Mate](https://wiki.debian.org/Mate). I hope this mod will work fine on other platforms without problems.
- Secondary, I used to work with the [Geany](https://www.geany.org/). Unfortunately, this text editor is not good for yaml structures. Now, I'm used to working with [Sublime Text](https://www.sublimetext.com/) without purchasing a license. This text editor is OK, but it disturbs me a hundred times per day due to the purchase of a license. Please feel free to offer me if you know another great text editor for yaml structures.
- I am used to working with the [Gimp](https://www.gimp.org/) for correct images. I am not a good painter. Therefore, I take images from [ufopaedia.org](http://ufopaedia.org/index.php/Ruleset_Vanilla_IDs_(OpenXcom)) or from another mods and improve each of them. I spend a lot of time to do a better visualization.
- I correct prepared images in [GrafX2](http://pulkomandy.tk/projects/GrafX2), because the [GIMP damages palette in *.png* files](http://openxcom.org/forum/index.php?topic=2676.0) and do not set the 0 value for background in indexed *.gif* files.
- The [LibreOffice](http://www.libreoffice.org/) and [Dia](https://wiki.gnome.org/Apps/Dia/) for creating text and diagrams.
- And at final, of course I use [Git](https://git-scm.com/) and GitHub. This is my first experience with Git and my first project on GitHub.

###How to install it?

* Download the [OpenXcom game](http://openxcom.org/downloads-milestones/) version 1.0 (June 13, 2014) and install it. Be aware, OpenXcom game requires a vanilla version of the original [UFO: Enemy Unknown](https://en.wikipedia.org/wiki/UFO:_Enemy_Unknown). If you don not own a copy, you can buy it from [one of these retailers](http://ufopaedia.org/index.php/Where_to_Get_the_Games).
* Download the [.zip](https://github.com/CanadianBeaver/AwesomeGuns/zipball/master) or the [.tar.gz](https://github.com/CanadianBeaver/AwesomeGuns/tarball/master) archive of the Awesome Guns modification and extract files and folders.
* Copy the extracted *Ruleset/AwesomeGuns.rul* file into your *openxcom/data/Ruleset* folder.
* Copy the extracted *Resources/AwesomeGuns* folder into your *openxcom/data/Resources* folder.

###Compatible mods and special thanks

I avoid to make changes in alien's missions or UFOs. There are a few mods for this and they work fine with my creation. I recommend to use these mods:
- [Lukes Expanded Terror Mission](http://www.openxcom.com/mod/lukes-expanded-terror-mission)
- [Solar's New UFOs](http://www.openxcom.com/mod/solar-039-s-new-ufos) (be aware, only version 1.1 is for stable game's release)

Awesome Guns modification can be incompatible with previous saved files, because inventory is redone. To avoid problems with previous saved files your soldiers should be stripped before saving, at least the right shoulder, right leg, left shoulder, left leg, and belt must be empty.

I got images and ideas from many mods, but I never copy these without adaptation. Basic of them are:
- Weapon Rework/Expansion
- XenoOperations
- Robin's Extra Weapons
- Improved Hand Objects
- Lukes Inventory Images
- Advanced_Medikit
- NewTUReserveUI
- 2012DeathSounds
- CraftMissleSound
- Doom_Skill_Levels
- Laser Rifle Recolor
- GrenadeLauncher
- Incendiary grenade
- EqualTerms1.03
- WolframLance
- Ryskeliini_GunsNGadgets_1st_pack_v12
- OpticalEleriumV0-94b
- Raven
- Air Combat Rebalanced
- Railgun
- Better look personal armor
- Grey armored vest
- Scout Power Armor
- Quick-Draw Hip Slot
- Reproduction
- FastRamp
- HQSounds_FinalModPack
- Stun Grenade
- The X-Com Files 
- Final Mod Pack
- *If I have forgotten someone, please let me know.*

###Contacts

I would appreciate hearing your opinion on this. Please feel free to contact me by email: [ontariobeaver@gmail.com](mailto://ontariobeaver@gmail.com)
