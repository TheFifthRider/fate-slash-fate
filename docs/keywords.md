# Keywords

## Weapon and Armor
(*Source: [Fate Core & Condensed](https://fate-srd.com/fate-condensed/optional-rules#weapon-and-armor-ratings)*)

Physical weapons and armor are not typically tracked as resources in Fate. 

Instead, "Weapon" and "Armor" are a special property that a character can get. Taking Weapon or Armor Extra grants a passive modifier to damage calculation. Weapon adds to damage dealt, and Armor reduces damage taken. The modifier is equal to the rating Level. 

### Rolling with Weapon and Armor

Weapon and Armor are factored separately from the roll's Shifts and do not apply when the Attack roll outright fails. 

> A character with \[Weapon: 1\] rolls a 5 to Attack against a Defend of 3, yielding 2 Shifts. 
> 
> Because this Attack succeeds, an additional 1 point of Weapon damage is dealt for a total of 3. However, the Attacker does not Succeed with Style because they only rolled 2 Shifts.

**Weapons** *do* apply to Tie rolls. However, the damage dealt by Weapons replaces the Boost that an Attacker would receive. 

**Armor** has the potential to negate all damage shifts. In this case, the Attacker receives a Boost just as if it were a Tie.

| Action | Attack Failure                                   | Attack Tie                                                                                     | Attack Succeed                                                        |     |
| ------ | ------------------------------------------------ | ---------------------------------------------------------------------------------------------- | --------------------------------------------------------------------- | --- |
| Weapon | Attack is prevented. Do not apply Weapon damage. | Apply only Weapon damage, but do not create a Boost.                                           | Deal Shifts of damage, then add damage equal to Weapon Level.         |     |
| Armor  | No damage is taken. No Boosts are made.          | If Attacker has Weapon, subtract Armor from damage received. Otherwise, Attacker gets a Boost. | Subtract Armor level from damage. If damage is now 0, Defender Boost. |     |

Effectively, Weapon tags mean you always deal damage even if you tie, while Armor tags increase the threshold at which you would tie.

??? tip "Usage Tips"
    
    As with all Extras, Weapon and Armor are best given to a character for a narrative reason. For example, a character with an Aspect reflecting Divinity may have Armor to reflect their power level over mortals. A Stunt reflecting use of a special literal weapon may grant a Weapon level. Bosses may gain levels in Weapon or Armor to reflect a change in phase or form.
    
    Weapon and Armor levels are very powerful and should be assigned conservatively. Level 1 of something may sound low, but Level 2 is effectively a perpetual Free Invoke. Level 3 is extraordinarily powerful and should be balanced as such.
    
    Weapon and Armor are our currently recommended mechanics for damage factors. Further options can be explored in [The Fate System Toolkit](https://fate-srd.com/fate-system-toolkit/weapons-and-armor-alternatives), but have not yet been reviewed for use in Fate/moon.

## Execute

If a character suffers shifts of damage from an Attack with Execute X, their bar is broken if they have X or less shifts of health remaining in that bar.

??? example "Example stunt: La Mort Marie Antoinette"
    When Marie succeeds with style on an attack she can gain \[Execute:2\], replacing the boost.

## Momentum

Momentum works like a boost, but has a keyword number rather than just being worth +2. You can consume the Momentum to automatically roll that number on an action if it would succeed.

??? example "Example stunt: I Just Need to Find a Crack"
    When you succeed with style on an Attack you can gain \[Momentum: 2+SNEAKY\] on your target, replacing the boost.

## Shield

Shield is a keyword for aspects that grant an armor rating to whomever (or whatever) it is related to while that aspect exists.

??? example "Example stunt: Bulletproof Fibers"
    When Willow Succeeds at creating an Advantage with her plant magic, she can spend a plant point to turn the created aspect into an \[Armor:1 Shield\]. When the aspect is created, she may also invoke the created aspect to increase the Armor rating of the Shield by 1 for each invoke.

## Foil Invokes

Foil Invokes are Free Invokes that can only be used against an enemy's roll. Typically, a stunt will create more Foil Invokes than it would Free Invokes because of this limitation.

??? example "Example stunt: Tell the Sun to Shine on Only Me"
    Whenever Willow Creates an Advantage, she can choose to place twice as many Foil Invokes as she would Free Invokes, replacing the free invokes.

## Obstacles
(*Source: [Fate Adversary Toolkit](https://fate-srd.com/fate-adversary-toolkit/obstacles)*)

Obstacles can be introduced either by a character's special abilities, as part of the environment, or even a living being. An Obstacle can even be a part of the enemy you're fighting. 

Obstacles are not simply Aspects, but carry their own set of properties. Often (but not always) they can be Overcome and removed, but they typically cannot be destroyed by brute force.

| Type | Components |
| ----- | -------------- |
| Hazards | Aspect, Unique Skill, Weapon, a Turn |
| Blocks | Aspect, Unique Skill, optional Weapon | 

### Hazards
Obstacles Attack characters and can do real damage. They have:

1. An Aspect, complete with all invoke and compel functions of an Aspect. 
3. A unique Skill with the same name as the Aspect, usually about as high as the PCs' best.
3. A Weapon Level between 1 and 4. 
4. A turn in the initiative order

The Hazard's Skill is used for all of its rolls, and also dictates the passive opposition it provides for any rolls against it. 

| Hazards Can...      | Hazards Cannot... |
| ------------------- | ----------------- |
| Attack              | Defend\*          |
| Create an Advantage | Overcoe           |
\**Narrative circumstances may convert a Hazard into an Attackable enemy* 

??? example "Example Hazards"
    | Rating | Hazard Aspect/Skill            | Weapon  |
    | ------ | ------------------------------ | ------- |
    | +4     | ***Machine-Gun Turret***       | \[W:3\] |
    | +6     | ***Whirling Spike Apparatus*** | \[W:2\] |
    | +5     | ***Distant Sniper***           | \[W:4\] |

### Blocks

Blocks hinder you from what you want to do, but are much more passive; they do not Act or roll and they have specific boundaries. They have:

1. An Aspect, complete with all invoke and compel functions of an Aspect. 
2. A unique Skill with the same name as the Aspect, usually no higher than one over the PCs' best.
3. Optionally, a Weapon Rating. 

They *typically* do not hurt you, but they certainly can. Instead of Attacking, they might deal damage based on the Shifts of a failed Overcome against them. 

If you like, you can Attack someone to forcibly push them into a Block. 

You might also try to use a Block as cover from an Attack. If applicable, you would gain [Armor](#Weapon and Armor) equal to half the block's Skill (rounded down, minimum 1). Of course, so can your enemies.

??? example "Example Blocks"
    | Rating | Hazard Aspect/Skill | Weapon |
    | --- | --- | --- | 
    | +2 | ***Chain Link Fence*** | --- |
    | +3 | ***Vat of Acid*** | \[W:4\] |
    | +4 | ***Animate Statue*** | \[W:1\] |