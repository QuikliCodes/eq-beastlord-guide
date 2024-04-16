# Beastlord Guide

This guide was last updated by *Quikli* on the Mischief server `2024-04-05`

## VoA Updates

* New spell line: [Shared Ferocity](abilities#shared-ferocity)
    * No more single targeting Fero, get whole groups at a time.
* 2360 new AAs to farm
    * Frenzy of Spirit gets twice as potent Hundred Hands Effect for only 12 AA
    * Group Bestial Alignment gets 1 more tick of base duration for only 12 AA
    * Pact of the Wurine gets 5% more chance to hit and 32 more mana regen for only 12 AA
    * New AA burn: Bloodlust - 30s of highly increased proc rate
    * Burst of Power gets 15% flurry chance
    * Most of the normal AAs get boosts, typical priorities


## Buffing during raids

* Check pet buffs between each encounter, you should be running:
    * Spirit of Bale (Pet Proc)
    * Incomparable Velocity (Pet Haste)
    * Mea's Aggression (DPS Stance)
    * Epic 2.0 (Not important anymore, and eventually becomes negative DPS)
* Rebuff the raid
    * Tranquil Blessings + Bst Crack, then TB again to have one available for the event
    * Ferocity on as many melee as you can manage
* Check if you're missing any important buffs
    * Unity from shammy
    * Haste & crack from enchanter
    * Ranger ATK buff (or use your own)
    * Cleric HP buff
* Click any clickies you have, for instance Direwolf Totem of Battle (but make sure to click off the summon familiar buff)

## Mash Key

**The single most important thing for beastlord DPS is a good mash key/multibind.**  This is done by making a new hotbar, going into options for it, and binding every key in it (or at least the first 7) to a single key, then assigning the following buttons to that new hotbar.

1. [Barrage (Rush)](abilities#rush)
2. [Chameleon Strike](abilities#chameleon-strike)
3. [Beastial Rending (Vivisection)](abilities#bestial-vivisection)
4. [Bale's Maelstrom](abilities#krons-maelstrom)
5. [Frozen Cyanin](abilities#frozen-venin)
6. [Rotsil's Bite](#sarsez-bite)
7. [Frostrift Lance](abilities#glacial-lance)

This will allow you to spam a single button to do most of your DPS work. Every time you press the button, #1, #2, and #3 will fire if avaiable, and the first nuke of 4, 5, 6, and 7 will fire that is available.  You can think of the nuke order as a priority order, with the best nukes placed earlier.

## Swarm Pets and DoTs

If a mob is going to last at least 20 seconds, your swarm pet will outshine all of your other DPS options.  Your poison and disease DoTs will outshine all of your nukes.  Priority is Swarm pet, then poison DoT, then disease DoT.  The disease DoT can be skipped entirely on fights < 1 minute or on highly resistant targets, as it often gets resisted and your nukes will make up the gap.

**The Swarm Pet or the Swarm Pet/Growl hybrid spell are great targets for gift of mana procs**


## Growl and Feralgia

Growl of the Lion will increase the melee DPS of your and your pet by 20% while also healing you over time.  This does not stack with [Empathic Fury](#empathic-fury) or [Anguish Click](#anguish-click), but growl is now a self buff, so you can run it at the same time as anguish click.  You will get growl and your pet will keep the anguish click for a bigger boost to the pet.

Feralgia can be used to re-up Growl and summon your swarm pet at the same time.

## Rules of Engagement


Make an attack hotkey that makes sure [Bestial Rending](#bestial-vivisection) is up before turning on attack to get benefit of it before your first round of combat and chameleon strike.  Chameleon strike is in there as an agro dump for the round so that your initial agro will be lower, giving the tank more time to stabilize even if you attack too early. Your `/assist` setting should be set to `/assist off` to benefit from this fully.  I keep /stand in these buttons for those events where things like to FD you.

```
/stand
/disc bestial rending
/attack on
/pet attack
/disc chameleon strike
```


You should also have an attack off hotkey like the following that allows you to stop everything in the event of an emergency.

```
/stand
/pet back off
/attack off
/stop
```

1. Hit assist to get target (`/assist off` should be the default setting, use a different button for turning on attack and sending pet)
2. Let the tank position the mob and hit it for a round or two
3. Press your attack hotkey from above
4. Cast swarm pet, poison dot, and disease dot (if disease is resisted, just move on, it happens a lot)
5. For the rest of the fight:
    * Mash Mash Mash Mash Mash
    * Recast swarm pet on cooldown
    * Re-up DoTs as needed
    * **Pay attention to mechanics, DPS isn't everything**

## Burns

[Bestial Rending](abilities#bestial-vivisection) should be up at all times during combat, endurance permitting.

* We have the following burns for our group:
    * ~10 minute burns
        * [Group Bestial Alignment](#group-bestial-alignment)
        * [Spire of the Savage Lord](#spire-of-the-savage-lord)
    * ~20 minute burns
        * [Nature's Fury](#natures-fury) + all of the 10 minute burns
* We have the following burns for ourselves:
    * ~5 minute burns
        * Anguish BP Click
    * ~10 minute burns
        * [Frenzy of Spirit](#frenzy-of-spirit)
        * Current Expansion BP Click
    * ~20 minute burns
        * [Bestial Alignment](#bestial-alignment)
        * [Empathic Fury](#empathic-fury)

## Panic Buttons

Your spiky DPS on engage will also tend to get you agro on engage.  Keep track of your panic button cooldowns and temper the use of your mash key accordingly.

* [Protective Spirit Discipline](abilities#protective-spirit-discipline)
* [Roar of Thunder](abilities#roar-of-thunder)
* [False Death](abilities#false-death) and [Playing Possum](abilities#playing-possum) (FDs)
