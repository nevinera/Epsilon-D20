Warrior
---------------

* May use any armor, any shield, and any weapon.
* +3 Athletics skill
* `+ ceil(clvl / 5)` to all attack and damage rolls.
* Learns a trick every level, instead of just odd ones.
* Can 'mark' a target that's within range of them (even outside of combat, though it'll have social implications). Has a -1 attack penalty on targets other than the marked one, but gets to take an attack of opportunity on the marked target if it moves away or engages another character. Also grants +1 AC against that target.

Rogue
--------------

* Light armor only, light weapons only.
* +3 Subterfuge skill
* When attacking an enemy that is not aware of them (sneaking up is usually DEX+Sub check), can add Subt skill rank to the damage roll.
* Reduced penalty for attacks attempted while moving.
* Learns a trick every level, instead of just odd ones.

Paladin
--------------

* Can use any armor, any shield, most one-handed weapons (prefers blunts).
* +2 Athletics skill, +2 Social skill
* +1 to Will (MND defense). +1 to Fortitude as well, starting at level 5.
* Can 'defend' another character; reduces your AC by DEXmod, Improves their AC by your DEXmod. If an attack misses the character you are defending with a spread of at least DEXmod, take an opportunity attack against the perpetrator (only once per round).
* Can use cleric spells like a cleric 3 levels lower. (At level 3, he gets one Rank 0 spell). The paladin gets no familiarity bonuses, and cannot empower or widen spells.

Druid
--------------

* Can use any non-metal armor and shield, and any weapon.
* +2 Studies, +1 Subterfuge, +1 Social

###Spirit Wolf:

  * Follows simple commands, can fight indepently. 
  * Uses the owner's magic attack bonus as his attack bonus, and does d4 + MNDmod damage with teeth (d8 + MNDmod on prone targets)
  * Selects targets based on what level of threat it considers them against its master (unless directed otherwise).
  * Resummoning takes ~ 5min, and costs 2hp.
  * Faintly ethereal, VERY good at remaining hidden in natural settings.

    STR: `Druid's MND - 4`  
    DEX: `Druid's MND - 2`  
    MND: `4`  
    Subt: `2 + floor(clvl/3)`  
    Athl: `1 + floor(clvl/3)`  
    HP:   `6 + clvl*d4`  
    AC:   `10 + clvl + MNDmod + 2`  


Mage
---------------

* No armor, No shield, small light weapons only.
* +4 Studies
* Mages choose a spell to be familiar with for *every* level gained instead of only one per rank.  (So they end up with two familiar spells per rank)
* +1 to Will against magic.
* `+ceil(clvl / 5)` to magic attack bonus and magic damage rolls.

Cleric
---------------

* Medium armor, light shields, light and blunt weapons only.
* +2 Social, +2 Studies, +1 Will, +1 Fortitude
* Can attempt to "turn" undead - roll `MND + Stud + clvl` against Will+mlvl. On success, the target flees for 2+d4 turns. On success with spread > 4, the target de-animates, with various effects. Costs 1hp, can target up to clvl different targets at once.
* When granted sufficient time, can meditate/pray for ~ 10 minutes, and reduce the cost of a spell by 1 (but not to zero).
