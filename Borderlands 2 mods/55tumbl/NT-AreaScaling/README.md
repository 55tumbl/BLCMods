*All files and content provided here were written by me (55tumbl), unless stated otherwise.*

*- They are free for personal use. I do decline any responsability in case it blows up in your face somehow, or any other misuse.
You may use these mods in videos, or for streaming, as long as you give me proper credit. I would appreciate you letting me know about it.*

*- You may re-use small bits of code (e.g. formulas, behavior modifications, etc) for your own purposes as long as you give me proper credit, and let me know about it.
Ask me for permission first if you wish to use larger portions of this code, make a modified/improved version, include it in a mod pack, etc.*

*- Do not re-upload any of those files anywhere.*

# Overview

NT-AreaScaling makes all areas and side-missions progressively scale up according to your advancement in the main mission, in Normal mode and TVHM. Level restrictions on the DLCs are lifted, so they can be played anytime during NVHM/TVHM, and they will also scale up according to the progress in the main game story.

This means that you can go back and farm Knuckledragger for a Hornet at level 18, for example. Or start Tiny Tina's DLC at level 8, do a couple missions before coming back to the main game... and return to finish that DLC at level 28. Or farm the snowman over and over and over and over.

# Compatibility

NT-AreaScaling should be compatible with any other mods, as long as these mods do not touch the area level definitions (I don't know of any mod that does, but I don't know everything).

NT-AreaScaling can be applied before loading any save game: it should automatically scale up the relevant areas. If you reload the save later on without NT-AreaScaling, the areas will go back within the acceptable limits in vanilla.

It is a relatively big file (2.4M, about half the UCP), so it may take a few seconds to load. The DLC sections may be disabled at will using BLCMM (in case you don't own some of the DLCs, or if you don't want to play them with the NT-AreaScaling modifications). NT-AreaScaling does absolutely nothing in UVHM, so there's not much point loading it when playing in UVHM.


# Detailed changes

## Normal mode

* Turning in one of the main story missions listed below will make all previous areas (and non-accepted side missions) scale up to your level, within certain limits.
* Some areas will scale up directly, **others may require a save/quit (notably the DLC areas)**.
* Side-missions and DLC missions that have already been accepted (and their rewards) will never scale up, but the areas in which they take place, and the enemies you fight, should scale up.
* Finishing the main story and killing the Warrior will make all areas scale up to level 30.
* The mission You. Will. Die. (Terramorphous) should be between level 30 and 35 (depending on your level when you finish the main story). Completing this mission will make all areas in the main game and headhunter DLCs scale up to 35.
* The raid boss missions in the 4 main DLCs will also be between level 30 and 35.

**Phaselock (damage on non-phaselockable targets)**: made to scale like other skills.   
* Damage increase of +60% at level 30, +100% at level 50, +144% at 72, +160% at OP8

**Scorn**: made to scale like other skills.   
* Damage increase of +60% at level 30, +100% at level 50, +144% at 72, +160% at OP8

**Immolate**: compensate for the double dip in damage penalty against higher level enemies in the OP levels (the special mechanics of this skill made it so that it was doing only about 20% damage versus a level 80 enemy, while other skills and weapons are doing 45% damage).   
* No effect up to level 72. Damage increase in the OP levels, up to +122% at OP8.

## Krieg

**Light the Fuse**: removed the level 72 cap.
* No effect on damage up to level 72. Damage increased by +183% at OP8.

**Krieg's innate melee damage bonus (without blade attachment)**: removed the level 72 cap.
* No effect on damage up to level 72. Base melee damage increased by +6.6% at OP8.

## Zer0
**Unf0rseen (electrocute DOT)**: made to scale like other skills and removed the level 72 cap.    
* Damage increase of +60% at level 30, +100% at level 50, +144% at 72, +590% at OP8.
* This is minor, since it does not affect the main damage from Unf0rseen (if the target is electrocuted, the increased DOT would give about +5% overall Unf0rseen damage at OP8).

## Gaige
**Deathtrap**: Made its damage scale the way it was supposed to (and actually does, on console)
* This affects the base melee damage, and the damage from its skills (Explosive Clap, The Stare, etc)
* Damage decrease of -29% at level 5 (Normal), increase of +4% at level 30 (Normal), +110% at level 50 (TVHM), +156% at level 72 (UVHM), +173% at OP8.
* The multiplicative bonus on his roid damage from Sharing is Caring now depends on level: instead of a constant value of x1.4, it increases from about x1.5 at level 31 (Normal), to about x3.8 at OP8.
* Deathtrap now gets a bonus to his damage in co-op. The max bonus (4 players) should be about x1.9 in Normal, and about x1.3 in TVHM/UVHM.
* All of this should now be exactly the same as it is on console.

**Deathtrap**: Fixed a bug that made the interaction between Make it Sparkle and Sharing is Caring (with a roid shield) completely broken.

**Deathtrap**: Made his ranged shock attack (used against flying and non-phaselockable targets) benefit from all his melee damage bonuses, including roid damage from Sharing is Caring, and Make it Sparkle. This makes his damage output more consistent against different types of enemies. The animation was modified so that the damage is spread over 2 damage ticks instead of 7 (per shock beam), but the overall damage should be exactly the same in absence of any melee damage bonuses.

**Electrical Burn**: compensate for the double dip in damage penalty against higher level enemies in the OP levels (the special mechanics of this skill made it so that it was doing only about 20% damage versus a level 80 enemy, while other skills and weapons are doing 45% damage).   
* No effect up to level 72. Damage increase in the OP levels, up to +122% at OP8.

## Axton
**Sabre Turret**: Tried to make its damage scale the way it was supposed to (and actually does, on console). Unlike Deathtrap, I couldn't figure out a way to do it perfectly, so I got as close as I could. I'll update if I find a better solution.
* This affects the damage of the bullets, the Scorched Earth Rockets, Nuke, and the capacity of the Phalanx Shield.
* The damage is now as it should be (and the same as on console) at level 0 (Normal), and at OP8. But it evolves a bit differently in-between. Mostly: it gets about 30% too large at the end of Normal mode, and about 30% too small in the beginning of TVHM. 
* Bullets, Rockets & part of the Nuke damage: -38% damage at level 5 (Normal), +14% at level 30 (Normal), +56% at level 50 (TVHM), +119% at OP8.
* Other part of the Nuke damage: +43% at level 30 (Normal), +95% at level 50 (TVHM), +173% at OP8.
* Nuke Fire DOT: +43% at level 30 (Normal), +95% at level 50 (TVHM), +620% at OP8 (there was a level 72 cap on this one, also on console).
* Phalanx Shield capacity is made to scale better, to stay (very roughly) constant relative to the turret's health. This is not the case on console. -12% capacity at level 16 (Normal), +18% at level 30 (Normal), +61% at level 50 (TVHM), +125% at OP8.
* The Sabre Turret still does not get any bonus damage in multiplayer, as it does on console (like Deathtrap).

One issue with this fix is that the damage of the turret is in part calculated from the level of the game, rather than the level of the turret itself. For example, if you join the game of a lower/higher level player, your turret damage will adapt (to some extent), and be lower/higher than it should. I don't think this should be too problematic in practice.

# Credits

This was all written by me.

Thanks to Koby for making me want to do something about it, and inviting me to Shadow's Evil Hideout Discord channel. And thanks to all the folks there who answered my questions and helped me get started.


# Change log

* [2018-08-09] v2.1: Added the modifications to Deathtrap's ranged shock attacks.
* [2018-07-31] v2.0: Added the Immolate & Electrical Burn fixes.
* [2018-07-18] v1.1: Fixed a small issue with the calculation of the Phalanx Shield Capacity. Switched to BLCMM-compatible format.
* [2018-06-24] v1.0.
