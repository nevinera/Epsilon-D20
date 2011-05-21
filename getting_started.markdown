### Making A Character

#### Pick stats
  * STR, DEX, MND. 
  * Any three stats between 8 and 18 summing to 40 will do. 
  * Check your racial stat modifiers, and apply them.
  * `mod(stat) = (stat - 10) / 2`

#### Skills
  * You start with zero of each skill (Ath, Sub, Std, Soc)
  * Check your class modifiers and your racial modifiers for these.

#### Attack Bonuses
  * `mod(STR)` for melee weapons
  * `mod(DEX)` for ranged weapons
  * `mod(MND)` for magic attacks.
  * Trained characters can use `mod(DEX)` for light melee weapons or staves if they prefer
  * Check for class bonuses

#### Defenses
  * Fort, Refl, Will
  * Each is `1 + mod(relevant_stat)`
  * Check for racial and class bonuses.

##### Armor
  * AC: `10 + Reflex + Gear`
  * Armor Reduction Range: `floor(AC_from_gear / 2)`
##### Magic Class
  * `10 + Will + clvl`
##### Health Points
  * `STR + 2 + d4`
  * Check racial modifiers (Dwarves)
##### Initiative Modifier
  * `mod(DEX) is the base
  * Heavy armor reduces it by one
  * Check racial modifiers (Halflings)

#### Spells
  * If your character can use spells, pick the starting spells.
  * Start with one rank 1 spell and two rank 0 spells.

#### Equipment
  * Everyone has food, water, basic supplies (and they don't run out under normal circumstances)
  * if you want anything unusual, ask; things that would not be expensive are fine.
  * Armor - This is mostly dictated by class. You can wear what you want, though plate is beyond the means of a level 1.
  * Weaponry - Pick what you'd like your character to use. If it's expensive, it will be of poor quality.
  
