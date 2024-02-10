# House of Thule Beastlord Guide

This guide was last updated by *Quikli* on the Mischief server `2024-02-10`

## Buffing during raids

* Check pet buffs between each encounter, you should be running:
    * Spirit of Kron (Pet Proc)
    * Incomparable Velocity (Pet Haste)
    * Neivr's Aggression (DPS Stance)
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

1. [Rush](#rush)
2. [Chameleon Strike](#chameleon-strike)
3. [Beastial Vivisection](#bestial-vivisection)
4. [Kron's Maelstrom](#krons-maelstrom)
5. [Frozen Venin](#frozen-venin)
6. [Sarsez' Bite](#sarsez-bite)
7. [Glacial Lance](#glacial-lance)

This will allow you to spam a single button to do most of your DPS work. Every time you press the button, #1, #2, and #3 will fire if avaiable, and the first nuke of 4, 5, 6, and 7 will fire that is available.  You can think of the nuke order as a priority order, with the best nukes placed earlier.

## Swarm Pets and DoTs

If a mob is going to last at least 20 seconds, your swarm pet will outshine all of your other DPS options.  Your poison and disease DoTs will outshine all of your nukes.  Priority is Swarm pet, then poison DoT, then disease DoT.  The disease DoT can be skipped entirely on fights < 1 minute or on highly resistant targets, as it often gets resisted and your nukes will make up the gap.

**The Swarm Pet or the Swarm Pet/Growl hybrid spell are great targets for gift of mana procs**


## Growl and Feralgia

Growl of the Tiger will increase the melee DPS of your and your pet by 20% while also healing you over time.  This does not stack with [Empathic Fury](#empathic-fury) or [Anguish Click](#anguish-click), but growl is now a self buff, so you can run it at the same time as anguish click.  You will get growl and your pet will keep the anguish click for a bigger boost to the pet.

Feralgia can be used to re-up Growl and summon your swarm pet at the same time.

## Rules of Engagement


Make an attack hotkey that makes sure [Bestial Vivisection](#bestial-vivisection) is up before turning on attack to get benefit of it before your first round of combat and chameleon strike.  Chameleon strike is in there as an agro dump for the round so that your initial agro will be lower, giving the tank more time to stabilize even if you attack too early. Your `/assist` setting should be set to `/assist off` to benefit from this fully.  I keep /stand in these buttons for those events where things like to FD you.

```
/stand
/disc bestial vivisection
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

Vivisection should be up at all times during combat, endurance permitting.

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

* [Protective Spirit Discipline](#protective-spirit-discipline)
* [Roar of Thunder](#roar-of-thunder)
* [False Death](#false-death) and [Playing Possum](#playing-possum) (FDs)

## Ability Descriptions

### Bestial Alignment

_AA (ID 245, timer 7)_

The original "morphin' time" burn for 30s (45s with buff extension). Part of the 20 minute burns. Can be run at the same time as [Group Bestial Alignment](#group-bestial-alignment), so that your group can get the worse version of it while you get the better one.  If you're in a big burn situation, don't pick one or the other, use both.

* Increase hit damage by 125%
* Increase chance to resist spells by 20%

### Bestial Vivisection

_Combat ability (timer 7)_

30s duration buff from disc with a 30s reuse, so can be maintained as long as you have endurance.

* Increase hit damage bonus by 72
* Increase min. hit damage by 21%
* Increase chance to hit with all skills by 53%
* Also applies a nearly identical buff to pet (22% increase min. instead of 21%)

**_If you include in the mash key, and I think you should, you'll need to click it off to use other discs that have durations and take up the disc bar in the combat ability window like Fearless or Protective Spirit.  You won't need to do this for empathic fury, nature's fury, or any of the other big important burns._**

### Chameleon Strike

_AA (ID 11080, timer 10)_

Single attack with increased damage and reduce agro.  Use every 20s on cooldown in mash key.

### Empathic Fury

_Combat ability (timer 3)_

30s duration buff from disc.  Part of the 20 minute burns.

* Increase hit damage by 50%
* Increase min. hit damage by 400%
* Increase chance to critical hit by 100%
* Also applies a similar buff to pet (100% increase hit damage instead of 50%)

### False Death

_AA (ID 421, timer 9)_

Instant, Fade, FD.  This is the best agro dump you have, make sure to have `/stand` in one of the buttons you have convenient for you to press if you're going to use this during a boss fight.  I put my `/stand` in my attack keybind

### Frenzy of Spirit

_AA (ID 127, timer 4)_

48s self buff. Do not run at the same time as [Nature's Fury](#natures-fury)

* Increase Melee Haste by 99%
* Decrease Weapon Delay by 22.5% (Hundred Hands Effect)
* Increase ATK by 325

### Frozen Venin

_Spell (timer 14)_

**Nuke** | Cast Time 0.5s | DPS ★★★ | Mana Efficiency ★★

This is our second best nuke.  Put it just after [Kron's Maelstrom](#krons-maelstrom) in your mash key.
It has significantly higher DPS than [Sarsez' Bite](#sarsez-bite) but significantly less mana efficiency than [Kron's Maelstrom](#krons-maelstrom).


### Glacial Lance

_Spell (timer 7)_

**Nuke** | Cast Time 0.5s | DPS ★★ | Mana Efficiency ★

This is our worst nuke that still deserves a spot in our mash key, but put it last.
It has the worst DPS and second worst mana efficiency of all of our nukes.  By putting it last, it won't be used if you mash slower while preserving your mana.

### Group Bestial Alignment

_AA (ID 985, timer 66)_

Can run in parallel with the single-target version [Bestial Alignment](#bestial-alignment) so that your group can get this and you can get the better version, you will not get the effect of both, but self-beast is too important to skip if you're in a big burn situation.  Lasts 1m18s (1m49s with exension).  Don't run this if the ranger group buff is running, since they won't stack.

* Increase hit damage by 30%
* Increase chance to resist spells by 20%

### Kron's Maelstrom

**Nuke** | Cast Time 0.5s | DPS ★★★★★ | Mana Efficiency ★★★

This is our best nuke, by a mile.  It has about double the damage output as [Frozen Venin](#frozen-venin) and substantially better mana efficiency too.  This deserves the top slot in our mash key, right behind our AAs and combat abilities. It hits 3 times right away and once more after a few seconds.  This thing destroys trash.  It is mana efficient, but it is **_not_** cheap.  If you get a gift of mana proc, use it either on a swarm pet or wait for this to be off cooldown to use it on this.

Extra points: make a second mash key for when gift of mana procs that contains the following, so you can keep mashing when you hear the gift proc and have it used on something really valuable.

* Your combat abilities
* Feralgia or Shout at the Moon (depending on your spell lineup)
* Kron's

### Nature's Fury

_Combat ability (timer 4)_

36s **group** buff from disc.  Part of the 20 minute burns. Do not run at the same time as [Frenzy of Spirit](#frenzy-of-spirit)

* Increase pet chance to flurry by 76%
* Decrease offhand damage shield taken by 46%
* Increase chance to flurry by 32%
* Decrease weapon delay by 22.5% (Hundred Hands Effect)

### Playing Possum

_AA (ID 11073, timer 53)_

80% success rate FD, without the fade component of [False Death](#false-death).  I only use this when [Roar of Thunder](#roar-of-thunder) and [False Death](#false-death) are down.

### Protective Spirit Discipline

_Combat ability (timer 2)_

90% melee mitigation for  12 seconds every 4 minutes.

### Roar of Thunder

_AA (ID 362, timer 8)_

Moderate agro dump + small nuke.
Great for corrections where you're sitting at 85-90% on a boss during a burn where you don't want to lose time FDing.

### Rush

_Combat ability (timer 9)_

Triple attack with increased damage. Use every 30s on cooldown in mash key.

### Sarsez' Bite

_Spell (timer 6)_

**Nuke** | Cast Time 0.5s | DPS ★★ | Mana Efficiency ★

This is our second worst nuke that still deserves a spot in our mash key, but put it second to last.
It has slightly better damage and slightly less efficiency than [Glacial Lance](#glacial-lance).  We only want this triggering when we really need more damage, so put it near the end of the mash key.


### Spire of the Savage Lord

_AA (ID 1430, timer 40)_

For self:

* Increase hit damage bonus by 42

For group:

* Increase min. hit damage by 30%
* Increase chance to hit by 7%
* Increase ATK by 70

For pet:

* Add proc DD 2500 with 100% bonus rate mod
