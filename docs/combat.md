# Combat Rules
In Fate, a full battle is called a Conflict, though we colloquially refer to it as Combat.
## Roar Phase
*(Source: [War of Ashes](https://fate-srd.com/war-ashes/advanced-conflict)*)

The Roar Phase is an optional prelude to combat. It is a moment to define the awesome way that your character is approaching the Conflict before them. Maybe you are ***Intensely Focused***, or maybe you have entered into a ***Berserk Rage*.

**Mechanically**, each participating combatant is Creating An Advantage to place a special Roar Aspect on themself. You Roll against a +2 with the Combat Style that most fits your intentions. 

However...

1. After a Player Roars, the GM then gets to do a Roar. 
   The GM can Roar as many times as the Players Roar, even if it means some enemies get to Roar multiple times.
2. Your Roar reflects a highly focused mindset. 
   You can only Attack with the Combat Style you used to Roar, or one of its Adjacent styles. 
   See the chart below.

```mermaid
flowchart LR
    ar(Arts) <--> br(Brave) & sn(Sneaky)
    br <--> bu(Buster)
    sn <--> qu(Quick)
    bu & qu <--> wi(Wild)
    style bu color:#fff,fill:#b30000 
    style wi color:#fff,fill:#ce9f00
    style qu color:#fff,fill:#41a21e
    style sn color:#fff,fill:#424242
    style ar color:#fff,fill:#2f59d2
    style br color:#fff,fill:#401684
```
*For example, if you Roar with Buster, you can Attack with Brave, Buster, or Wild.*

!!! note "Modification From Original Rules" 

    Under the original Fate rules, Failing your Roar roll would create a Consequence. 
    In FATE/moon, we will instead resolve this as you would any other Create An Advantage: the enemy gets a Free Invoke on the Aspect.

## Taking Turns

In Combat, every character gets a turn to act, as do [obstacles]. 

Bosses may receive multiple turns, and low-level "mooks" might share their place in the turn order even if there are multiple of them. Allied NPCs may be present but abstain from the turn order unless specifically called upon by the party.

One complete round of turns is called an Exchange.

#### The Nature Of Turns

Flavorfully, it is important to remember that turn-based battle does not mean your character is sitting around waiting for their turn on the XBox. You can always safely assume that your characters are trading blows, dodging, repositioning, preparing, etc. while others act, or that your actions are simultaneous. Your turn is simply when the camera zooms in on you for a significant development!

Brief dialogues are also perfectly fine to have during combat, but extended conversations may have to be paused until the next Exchange. One possible rule of thumb is to ask: "Would this fit on one page of manga?"

### Popcorn Initiative
*(The Fate SRD discusses this under [Elective Action Order](https://fate-srd.com/odds-ends/elective-action-order))*

Rather than rolling initiative to determine a fixed turn order, the flow of action is chosen dynamically under the Popcorn Initiative system. 

1. At the conclusion of your Turn, select a participant who has not yet taken their Turn in the current Exchange. 
2. Once they have completed their Turn, they will select another participant.
3. So on and so forth until the Exchange has been completed. 
4. Whoever finished the Exchange chooses the player to start the next Exchange. 
   Every participant is now available to act, though you cannot "popcorn" to yourself.

!!! example "The Strategy and Implications of Popcorn Initiative"

	You can "popcorn" to any participant, even if they are not your ally. As with Compels and Conceding, the Popcorn Initiative is a player decision and not a character one. Your character does not have to yield to an enemy to allow them to act; you the player are simply turning the camera. 
	
	In fact, there can be many benefits to popcorning to an enemy. One strategic quirk of the Popcorn Initiative is that you may want to get the enemy's Turns out of the way! If you allow an enemy to have the last Turn in the Exchange, they may choose another enemy to start the next Exchange, and that enemy might then choose another enemy! On the other hand, letting your ally end the Exchange lets your team control the top of the turn order.
	
	Of course, every battle will have its own strategies. Feel free to confer with your party to decide your preferred course of action.

## Zones

A battlefield is made up of Zones which. Zones can be big or small, and there can be as many or as few Zones as appropriate. Zones can even be created by major environmental changes or special abilities. 

No matter what the Zone physically is, the point of the Zone is to codify range! You can always target any person or thing in a Zone. 

Maybe you're narratively jumping and sprinting around, but you can reasonably reach anything in the Zone during your turn. A Zone might be enclosed within a barrier or exist on a different elevation, or it may simply end because the adjacent Zone is "far away" enough. 

### Attacking With Zones

If it makes narrative sense, you can perform a ranged attack across Zones. 
 
> If there is another Zone across a ***Giant Chasm***, an Archer can shoot across the gap. If your opponent is in a Zone representing the top of a skyscraper, it could be a hard sell to shoot at them from the adjacent alleyway.

With an appropriate Stunt, you could perform an Attack against every combatant in the Zone. 

### Movement

If your movement would not be hindered, **you can move between Zones *in addition* to your Turn Action**.

Otherwise, you need to use your Turn Action to Overcome the impediment. It could be the natural environment, an enchantment binding you to the Zone, or a fellow combatant trying to stop your efforts. Failure prevents your efforts, *or* you can succeed at a cost. However, there is no "Attack of Opportunity" against you when your back is turned.

Conversely, you could also use your Turn Action to Overcome if you wanted to rush to any Zone on the map. The GM will set a difficulty for this, and it could be very high.

## Multi-Target Attacks
*(Source: [Fate Condensed](https://fate-srd.com/fate-condensed/optional-rules#ways-to-handle-multiple-targets))*

Yes, you *can* try to Attack multiple people at once. Technically, these rules can apply to any Action, but Attacks are the most common circumstance to want them.

### Split Effort (Select Targets)

1. Roll once! 
2. If it is positive, you may distribute your Shifts among the targets.
3. Each target can Roll to Defend against the Shifts you assigned to them.

### Zone Attack

1. Have a prerequisite Stunt or Aspect to justify this range
2. Roll once!
3. Each participant in the Zone Rolls to Defend against that same number. 

## Getting Taken Out vs. Conceding the Conflict

Once you've taken all the hits you can (pending your option to [take an extreme consequence](consequences)) you are taken out of the conflict. **This is not necessarily the same as being killed!** Perhaps you simply fall unconscious, or you get taken hostage. Remember: stress represents your stamina.

Whoever took you out gets to decide what happens to you. (...Which could be worse than death!)

To take control of your character's fate, you can Concede. **This is not the same as your character surrendering!** Your character may exit the scene willingly, but it can be unwilling. Either way it's still a loss, just a softer kind of loss. 

You can Concede during any Turn of the Exchange, even after an Action has been declared, as long as the dice have not yet been rolled. 

If you Concede, you receive 1 fate point, plus an additional fate point for each consequence you suffered during the conflict!