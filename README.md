# Deezix Hack
This hack is a series of replacement rules for old-school style fantasy rpg games aimed at making it easier for small player groups to manage the large parties of PCs and henchmen often assumed in old-school style adventure modules. These rules consolidate many PC and Monster statistics into a handful of quick-reference stats that directly correlate with their mechanical function, and implements a universal dice pool mechanic for all combat rolls.

This hack assumes you are using B/X or a B/X-compatible role-playing game (such as Old School Essentials) as your chassis, with these rules overriding certain aspects.
## Summary of Changes
**Game Statistics**
- Traditional 6 ability scores are consolidated to 3 (PHY, MEN, SPR) ranging 1 - 3
- HP is reduced overall. PCs have SPR + Level HP. Monsters have HP equal to their HD.
- AC is ranges from 0 - 2 and serves as damage reduction
- Attack bonus/THAC0 and Saving Throw progression is consolidated to a single Combat Bonus (CB)

**Mechanics**
- A d6 dice pool system is used for rolls, where a 5 or 6 on any die is a success.
- Attack dice pools are PHY + CB. Each success is 1 damage
- Damage and healing from spells and other effects are converted to 1 per die (a 5d6 fireball is now 5 damage)
- Saving throw dice pools are SPR + CB
- Encumbrance is slot based
- Monsters stats are mostly derived from their HD. Multiple attacks are made by re-rolling non-6s.

---
# Game Statistics

## Ability Scores
PC and NPCs have 3 primary ability scores. ***Physical*** (PHY), ***Mental*** (MEN) and ***Spirit*** (SPR). A character is ranked in each ability by a number between 1-3 (higher is better). These are determined by rolling a d6.

| d6  | Ability Scores       |
| --- | -------------------- |
| 1   | PHY 3, MEN 2, SPR 1  |
| 2   | PHY 3, MEN, 1, SPR 2 |
| 3   | PHY 2, MEN 3, SPR 1  |
| 4   | PHY 2, MEN 1, SPR 3  |
| 5   | PHY 1, MEN 3, SPR 2  |
| 6   | PHY 1, MEN 2, SPR 3  |

**Calling it:** At character creation, a player may "call it" by predicting the outcome of their ability score roll. If they are correct, they may opt to set all ability scores to 2.
## Hit Points (HP)
PC and hireling hit points equal SPR + Level.
## Armor Class (AC)
Armor reduces incoming damage by the armor class value. Armor cannot reduce damage to 0.

| Armor Worn      | Armor Class |
| --------------- | ----------- |
| Unarmored       | 0           |
| Lightly Armored | 1           |
| Heavily Armored | 2           |
## Combat Bonus (CB)
PCs and NPCs have a combat bonus based on their class and level. This bonus is applied to attacks and saving throws. 

| **Level** | **Cleric** | **Fighter** | **Magic-User** | **Thief** |
| --------- | ---------- | ----------- | -------------- | --------- |
| **1**     | 0          | 0           | 0              | 0         |
| **2**     | 0          | 0           | 0              | 0         |
| **3**     | 0          | 0           | 0              | 0         |
| **4**     | 0          | 1           | 0              | 0         |
| **5**     | 1          | 1           | 0              | 1         |
| **6**     | 1          | 1           | 1              | 1         |
| **7**     | 1          | 2           | 1              | 1         |
| **8**     | 1          | 2           | 1              | 1         |
| **9**     | 2          | 2           | 1              | 2         |
| **10**    | 2          | 3           | 1              | 2         |
| **11**    | 2          | 3           | 2              | 2         |
| **12**    | 2          | 3           | 2              | 2         |
| **13**    | 3          | 4           | 2              | 3         |

# Adventuring
## Ability Rolls
Ability rolls are used to determine certain outcomes influenced by a character's abilities. To make an ability roll, roll a number of dice equal to the relevant ability score. **If a 5 or 6 is rolled on any dice, it is a success.**

Multiple successes on a single roll may have additional effects.
## Attack Rolls
Attacks are resolved by making a PHY + CB roll. For every 5 or 6 rolled, 1 damage is dealt to the target's HP (reduced by their AC to a minimum of 1).
## Saving Throws
Saving throws are made by making a SPR + CB roll. If a 5 or 6 is rolled, the saving throw is successful.
## Damage and Healing from Spells and Other Effects
Damage and healing from spells is converted from their original format as 1 damage per damage dice stated on the spell (ex. a spell dealing 3d6 would deal 3 damage). This method is used for potions, traps, monster abilities, etc.
## Encumbrance
Any normal sized character may carry/wear the following items:
- Armor
- 2 melee weapons
- 1 ranged weapon
- 6 items
- 1000 gp (or treasure of equivalent weight)

Items purchased in units such as torches (6), or arrows (20) count as 1 item

**Exceeding encumbrance limits**: Movement is at halved. Combat Bonus is reduced to 0.
# Monsters
Statistics for monsters are primarily handled by referencing their hit dice.

**HP:** Equal to their HD

**Saving Throws:** Equal to their HD

**Attack Rolls**: Equal to their HD

**Multiple Attacks**: Creatures with multiple attacks do not make additional attack rolls. Instead, they are able to re-roll any failures for each additional attack listed on their original stat block.

**Armor Class**: Armor class should be converted based on the referee's judgement of which of the three categories their worn or natural armor falls (unarmored, lightly armored, heavily armored).

Alternatively, use this table:

| Original AC/AAC | Deezix AC           |
| --------------- | ------------------- |
| 6 [13] or worse | Unarmored (0)       |
| 5-3 [14-16]     | Lightly Armored (1) |
| 2-0 [17+]       | Heavily Armored (2) |

---
# Example Combat

Galadan (Fighter 4): **HP** 6, **AC** 2,  **PHY** 3, **MEN** 1, **SPR** 2

Ghoul: **HD** 2*, **AC** 0,  **ATT** 2 x claw (paralysis)

Galadan wins initiative and attacks the ghoul, rolling 5d6 (3 STR + 1 CB) resulting in 1, 2, 4, 6. The 6 represents a successes and the Ghoul takes 1 point of damage.

The Ghoul attacks back, rolling 2d6 (2 HD) resulting in 4, 3. The Ghoul has 2 claw attacks, so it re-rolls all non-6s for its second attack. The results are now 1, 6. The damage is reduced by Galadan's AC (2) to a minimum of 1 damage.

Galadan must make a saving throw against the Ghoul paralysis, rolling 4d6 (2 SPR + 2 SB) resulting in no 6s. He fails the saving throw and becomes paralyzed.

---
# Balance Notes
To maintain compatibility with old-school and OSR adventure modules, these rules aim to generate roughly similar outcomes in combat that would occur using B/X or similar rules. However, some balance considerations should be acnkowledged due to the differences in game mechanics.
- PCs are tougher at early levels due to their relatively-higher HP compared to monsters of equivilant HD.
- Armor is strong! Especially as higher HD monsters with multiple attacks are encountered.
- Damage in general is constrained more tightly than in B/X due to the effectiveness of armor and the re-roll mechanic for multiple attackes. This makes combat outcomes more deterministic. Players should keep this in mind when deciding whether or not to charge into battle.
