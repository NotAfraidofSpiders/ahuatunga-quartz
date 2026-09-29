---
publish: true
permalink: /2 - Mechanics/e. Player Options/Classes/Bard Content/College of Creation.md
created: 2025-10-14T17:23:31.596Z
modified: 2026-04-23T01:45:18.395Z
published: 2026-04-23T01:45:18.395Z
tags:
  - PlayerOption
  - Subclass
  - Rules
  - StatBlock
---

**_Bards believe the cosmos is a work of art - the creation of the first dragons and gods. That creative work included harmonies that continue to resound through existence today, a power known as the Song of Creation. The bards of the College of Creation draw on that primeval song through dance, music, and poetry, and their teachers share this lesson: "Before the sun and the moon, there was the Song, and its music awoke the first dawn. Its melodies so delighted the stones and trees that some of them gained a voice of their own. And now they sing too. Learn the Song, students, and you too can teach the mountains to sing and dance."_**

**_Dwarves and gnomes often encourage their bards to become students of the Song of Creation. And among dragonborn, the Song of Creation is revered, for legends portray Bahamut and Tiamat-the greatest of dragons -as two of the song's first singers._**

Source: Tasha's Cauldron of Everything

### Mote of Potential

When you join the College of Creation at 3rd level, whenever you give a creature a [[Bard#Bardic Inspiration|Bardic Inspiration die]], you can utter a note from the Song of Creation to create a [[Combat Rules#Size Category Table|Tiny]] mote of potential, which orbits within 5 feet of that creature. The mote is intangible and invulnerable, and it lasts until the Bardic Inspiration die is lost. The mote looks like a musical note, a star, a flower, or another symbol of art or life that you choose.

When the creature uses the Bardic Inspiration die, the mote provides an additional effect based on whether the die benefits an [[Ability Scores#Ability Checks|ability check]], an [[Combat Rules#Attack Rolls|attack roll]], or a [[Ability Scores#Saving Throws|saving throw]], as detailed below:

#### Ability Check

When the creature rolls the [[Bard#Bardic Inspiration|Bardic Inspiration die]] to add it to an [[Ability Scores#Ability Checks|ability check]], the creature can roll the Bardic Inspiration die again and choose which roll to use, as the mote pops and emits colorful, harmless sparks for a moment.

#### Attack Roll

Immediately after the creature rolls the [[Bard#Bardic Inspiration|Bardic Inspiration die]] to add it to an [[Combat Rules#Attack Rolls|attack roll]] against a target, the mote thunderously shatters. The target and each creature of your choice that you can see within 5 feet of it must succeed on a [[Ability Scores#Saving Throws|Constitution saving throw]] against your [[Bard#Spellcasting Ability|spell save DC]] or take thunder damage equal to the number rolled on the Bardic Inspiration die.

#### Saving Throw

Immediately after the creature rolls the [[Bard#Bardic Inspiration|Bardic Inspiration die]] and adds it to a [[Ability Scores#Saving Throws|saving throw]], the mote vanishes with the sound of soft music, causing the creature to gain [[Combat Rules#Temporary Hit Points|temporary hit points]] equal to the number rolled on the Bardic Inspiration die plus your [[Ability Scores#Ability Scores and Modifiers Table|Charisma modifier]] (minimum of 1 temporary hit point).

### Performance of Creation

Also at 3rd level, as an [[Combat Rules#Your Turn|action]], you can channel the magic of the Song of Creation to create one nonmagical item of your choice in an unoccupied space within 10 feet of you. The item must appear on a surface or in a liquid that can support it. The gp value of the item can't be more than 20 times your bard level, and the item must be [[Combat Rules#Size Category Table|Medium or smaller]]. The item glimmers softly, and a creature can faintly hear music when touching it. The created item disappears after a number of hours equal to your [[Ability Scores#Proficiency Bonus|proficiency bonus]]. For examples of items you can create, see the [[Adventuring Gear|equipment]] chapter of the _Player's Handbook_. ^06ec31

Once you create an item with this feature, you can't do so again until you finish a [[Resting Rules#Long Rest|long rest]], unless you expend a [[Spellcasting Rules#Spell Slots|spell slot]] of 2nd level or higher to use this feature again. You can have only one item created by this feature at a time; if you use this [[Combat Rules#Your Turn|action]] and already have an item from this feature, the first one immediately vanishes. ^1da36d

The size of the item you can create with this feature increases by one [[Combat Rules#Size Category Table|size category]] when you reach 6th level (Large) and 14th level (Huge). ^d9b2cd

### Animating Performance

By 6th level, as an [[Combat Rules#Your Turn|action]], you can animate one [[Combat Rules#Size Category Table|Large or smaller]] nonmagical item within 30 feet of you that isn’t being worn or carried. The animate item uses the [[College of Creation#Dancing Item Stat Block|Dancing Item]] stat block, which uses your [[Ability Scores#Proficiency Bonus|proficiency bonus]] (PB), The item is friendly to you and your companions and obeys your commands. It lives for 1 hour, until it is reduced to 0 hit points, or until you die.

In combat, the item shares your [[Combat Rules#Initiative|initiative count]], but it takes its turn immediately after yours. It can [[Combat Rules#Movement and Position|move]] and use its [[Combat Rules#Reactions|reaction]] on its own, but the only action it takes on its turn is the [[Combat Rules#Dodge|Dodge action]], unless you take a [[Combat Rules#Bonus Actions|bonus action]] on your turn to command it to take another action. That action can be one in its [[College of Creation#Dancing Item Stat Block|stat block]] or [[Combat Rules#Actions in Combat|some other action]]. If you are [[Conditions#Incapacitated|Incapacitated]], the item can take any action of its choice, not just Dodge.

When you use your [[Bard#Bardic Inspiration|Bardic Inspiration feature]], you can command the item as part of the same [[Combat Rules#Bonus Actions|bonus action]] you use for Bardic Inspiration.

Once you animate an item with this feature, you can't do so again until you finish a [[Resting Rules#Long Rest|long rest]], unless you expend a [[Spellcasting Rules#Spell Slots|spell slot]] of 3rd level or higher to use this feature again. You can have only one item animated by this feature at a time; if you use this [[Combat Rules#Your Turn|action]] and already have a dancing item from this feature, the first one immediately becomes inanimate

#### Dancing Item Stat Block

```statblock
layout: Basic 5e Layout
image: 
name: Dancing Item
size: Large or smaller
type: Construct
ac: 16 (natural armor)
hp: 10 + 5 times your bard level
speed: 30 ft., [[Monster Rules#Fly|fly]] 30 ft. (hover)
stats: [18, 14, 16, 4, 10, 6]
damage_immunities: poision, psychic
condition_immunities: charmed, exhaustion, poisoned, frightened
senses: [[Environment Rules#Darkvision|darkvision]] 60 ft., passive Perception 10
languages: understands the languages you speak
cr: -
traits:
  - name: Immutable Form
    desc: The item is immune to any spell or effect that would alter its form
  - name: Irrepressible Dance
    desc: When any creature starts its turn within 10 feet of the item, the item can increase or decrease (your choice) the walking [[Movement Rules#Speed|speed]] of that creature by 10 feet until the end of the turn, provided the item isn't incapacitated.
actions:
  - name: Force-Empowered Slam
    desc: "_Melee Weapon Attack:_ your spell attack modifier to hit, reach 5 ft., one target you can see. _Hit:_ `dice: 1d10`(1d10) + PB force damage."
```

### Creative Crescendo

At 14th level, when you use your [[College of Creation#Performance of Creation|Performance of Creation feature]], you can create more than one item at once. The number of items equals your [[Ability Scores#Ability Scores and Modifiers Table|Charisma modifier]] (minimum of two items). If you create an item that would exceed that number, you choose which of the previously created items disappears. Only one of these items can be of the maximum size you can create; the rest must be [[Combat Rules#Size Category Table|Small or Tiny]].

You are no longer limited by gp value when creating items with Performance of Creation.
