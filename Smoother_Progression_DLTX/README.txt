
Smoother Progression addon version 1.0 for Anomaly 1.5.1
by KronQ
(2021-07-19)


1. Description
2. Installing
3. Important notes
4. Compatibility
5. Full outfit/weapon list
6. Changelog
7. Credits


````````````````````````````````````````````````````````````````````


1. Description

	Do you hate the current tool RNG but also don’t like mods that just straight up hand the tools to you on a silver platter?

	Do you hate how expensive it is to do ANYTHING at the technicians, to the point where the only viable tactic is to hoard money until you get better equipment?

	Then this mod is for you.

	The main idea behind this addon is to make the early to mid-game way more fun by giving the player more options with his equipment. Hoarding money and rushing to find tools should no longer be the only way to progress.

	GET MCM TO ACCESS FULL FUNCTIONALITY OF THE MOD
	https://www.moddb.com/mods/stalker-anomaly/addons/anomaly-mod-configuration-menu

	Upgrade pricing is now a lot more customizable with the use of MCM.

	List of changes:

	-	Upgrade price now depends heavily on its tier (by default 0.5x, 1.1x and 1.5x respectively, each can be changed via MCM)
	-	Every technician is now able to do tier 1 upgrades without any tools
	-	Basic and advanced toolkits now unlock different tier 2 upgrades
	-	Any Exoskeleton sprint upgrade requires advanced tools minimum (to offset the aforementioned changes)
	-	Many starter weapons/outfits can be fully upgraded without any tools (full list in Readme)
	-	Rebalanced outfit upgrade prices based on how useful they actually are – passive healing is now properly expensive while some minor buffs not so much (remove upgrade_presets.ltx if you prefer vanilla values)
	-	Halved upgrade prices for weapons to make them reasonable and encourage people to try out different shooters (can be changed via MCM)
	-	Less drastic changes in prices for completing tool tasks (compared to vanilla you’ll pay less early game but more during end game)
	-	Fixed bugged technicians and changed few things to reduce cheese strategies:
		– Spleen can no longer do tier 3 upgrades, can’t upgrade exos to sprint, charges a lot
		– Dazhbog’s upgrades are locked behind tool quests like other technicians
		– Nitro is no longer ridiculously expensive for no reason
		– Cardan now gives discount after receiving tools as he should, so now Nitro is initially cheaper, but Cardan gets better than him as you deliver tools
		– Forester can’t upgrade exos to sprint

	I tried to balance the mod to make it reminiscent of how the upgrade economy was in the original Stalker games.

	Now you can decide - do you want to keep upgrading your old suit, or do you want to start investing into something new? Maybe you’d rather fully upgrade your old, trusty Mosin, instead of instantly dropping it for that fancy, expensive AWSM you might not have the tools for yet? 

	Vanilla Anomaly has abysmal upgrade pricing policy. Basic Makarov and TOZ-34 upgrades shouldn’t cost thousands of rubles. A 10% fire rate increase should not cost as much as the weapon itself. Upgrading your jacket should not cost as much as a straight up better suit. And with this mod they no longer do. 

	Low tier suits should be overall cheaper to upgrade while high-end stuff remained more or less the same. To have a fully upgraded weapon you are going to spend about half of what you used to, so you can play around with more pew-pews without burning a hole in your pocket.

	Keep in mind that various technicians have different prices. You also get discounts for completing tool quests. For obvious reasons prices were balanced mostly with default medium difficulty in mind. 




2. Installing

	Paste the gamedata folder into the main game directory.
	
	


3. Important notes

	If you change the values in MCM you have to save and load the game for the prices to change.

	This mod affects only technicians. Vices and other stuff remains as they were.

	Mod incorporates two different addons that got tweaked further:
	https://www.moddb.com/mods/stalker-anomaly/addons/gradual-upgrades-pricing-100-clean
	https://www.moddb.com/mods/stalker-anomaly/addons/early-upgrades-upgrade-your-starting-equipment-u4h8rc22

	If you are using any of them, remove them before installing.
	
	I tried to test it with my limited time, report bugs on moddb, plz.




4. Compatibility	

	The mod operates on its own scripts, however any other mod modifying inventory_upgrades.script might break something because it serves as a basis.

	The upgrade_presets.ltx can be freely removed/replaced, it only affects pricing of specific outfit upgrades, the game will simply revert to vanilla values.

	I don’t expect many other mods to touch on stalkers_upgrade_info.ltx or anything inside the upgrade_infos folder, however if it does, some things might not work correctly.

	Conflicts are unlikely, however let me know if you encounter any. I can't check every mod out there myself.



5. Full upgrade/weapon list


	Here's more or less complete list of stuff you can upgrade fully without bringing any tools to technicians. Very basic equipment.


	Pistols:
	PM
	PMM
	PB
	CZ 52
	TT-33
	APS
	Fort-17
	Hi-Power
	Colt 1911

	SMGs:
	MP5
	MP5SD
	Kiparis
	Skorpion
	PPSh-41
	
	Rifles:
	SVT-40
	G43
	SKS
	Type 63
	Mosin
	Kar98k
	
	Shotguns:
	TOZ-34 (and its variants)
	TOZ-66 (and its variants)

	Outfits:
	All the different types of jackets
	Overcoat
	Military service outfit
	
	Helmets:
	Respirator
	Steel helmet
	ACH-7




6. Changelog

	1.0.3 - small bugfix for Mags Redux
	1.0.4 - fixed a syntax error from previous version that caused the script to die (thx Haruka)




7. Credits
	
	If you want to reuse stuff from this addon, do so while giving appropriate credit to the original authors.
	

	To thank certain people:

	- Raven Ascendant for setting up the script base I expanded upon, his monkey patch tutorial, MCM
	- Jurkonov for testing and letting me work on his addon
	- HarukaSai for showing me why I'm an idiot
	- Anomaly dev team for making and still working on this amazing mod
