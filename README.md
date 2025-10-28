# Everydungeon
An open-source TTRPG.
# The Purpose
## 1. Anyone can play
The system must be relatively simple to understand, not rely on large tables, and not involve too much math.

## 2. Anyone can add to the source
The system must be modular and community created.

## 3. Attempts to create a comprehensive system
Below is a metaphorical equation to better convey the message.
Let E(t) be Everydungeon with some time t.
Let C be the hypothetical, completely comprehensive TTRPG system.

$$
\lim_{t\to\infty} E(t) = C
$$

# The Core Combat System
## The 3 Core Stats
These are initialized by taking 3d6 and taking the middle -1

Action (STR)
- Initiative+, Accuracy+, General DMG+
- STR + a half of DEX

Reaction (CON)
- Armor Class+, Health Points+, Healing+, Shielding+, Saves
- CON + a half of DEX

Interaction (INT)
- Magic, Language, Explotation, Reaction
- INT + WIS + CHA

Checks: Core Stat +10 >= d20
## Heavy and Light Specialization
Heavy Specialization
- Choose between the 3 Core Stats (denoted STR-H, CON-H, and INT-H)
- +2 to that stat, determines which Heavy Ability you can have (which in turn determines class)
- Determines your HP die, available armor, and available weapon
- INT-H can use Magic

Light Specialization
- Choose between the 3 Core Stats (can be the same as the Heavy Specialization, and denoted STR-L, CON-L, and INT-L)
- +1 to that stat, determines which Light Ability you can have

The unchosen stat(s) get -1 to that stat(s).

## Combat Stats
Health Points (HP)
- Determined by Heavy Specialization + CON
- (INT-H/STR-H/CON-H -> d4/d6/d8) + CON

Armor Class (AC)
- Determined by Heavy Specialization + Sidearm + CON
- (INT-H/STR-H/CON-H -> 8/10/12) + (0/1/2/3) + CON

Experience (XP)
- Converts to Level (LVL), Start at LVL 0
- It takes (Goal LVL)*1000 XP to get to (Goal LVL) from (Goal LVL-1)
- Gain EXP at the end of the session based on how much gold the party made from treasures at the end of each session + additional XP at the GM's discretion upon questline completion.
- +1 to a chosen Core Stat on level up.
- Max LVL is 12.

## Abilities
Heavy Ability
- Choose one with the corresponding Heavy Specialization
- Gain one additional Heavy Ability slot at LVL 12.

Light Ability
- Choose one with the corresponding Light Specialization
- Gain one additional Light Ability slot at LVL 6.

## Spells
Only INT-H can wield them (with some exceptions). Can wield LVL+1 amounts of spells. Remember all spells all the time. Basic skills can be learned by level up, other spells can be found. All spells have a LVL restriction.

## Equipment
Weapon
- Choose one based on Heavy Specialization
- Choose the range: Melee or Ranged (Ranged cannot be above d8)
- Choose the damage type: Slashing, Piercing, Bludgeoning
- (INT-H/CON-H/STR-H -> d4/d6/d8 (or d10 two-handed)) + STR

Sidearm
- INT-H cannot use Sidearms
- (CON-H or STR-H -> 0/(1 and Accuracy +1)/2/(3 two-handed))

## Saves
General: CON +10 >= d20
Death: Roll a 6 on d6

## Exploration
Using Your 5 Senses: INT +10 >= d20
Find Secret: INT +5 >= d20
Open Stuck Door: STR +10 >= d20

## Language
1 Language per INT, start with Common

## Note
No encumberance, and distance is GM discretion.

# Combat Loop
1. Everyone rolls for initiative, add STR
2. Everyone goes from highest to lowest (if multiple players/enemies are in the same initiative number, players go first)
3. Everyone does their things (Move, Basic Attack, Ability, Spell) on their turn
4. Repeat until conclusion

# The Core Narrative System
## Identification
None of the below has any combat influence, but may influence socials.
- Name
- Race
- Gender
- Affiliation (choose from the lore)
