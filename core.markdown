1.  Stats and Skills
---------------------

There are only three stats: Strength (STR), Dexterity (DEX), and Mind (MND). The modifier for each stat is `(stat - 10) / 2` (round toward zero) - these are referred to like 'STRmod' or 'DEXmod'

Picking stats:

* Method 1: Roll 4d6, drop lowest, assign to a stat. Repeat for remaining stats.
* Method 2: Pick from the lists [18,12,10], [16,15,9], [15,14,11]. Assign each number to a stat.
* Method 3: Pick three numbers that add up to 40. None above 18, none below 8.

There are four skill categories: Athletic (Ath), Subterfuge (Sub), Studies (Stud), and Social (Soc). Checks are usually made against some combination of your level (clvl), a stat, and a skill - a climbing check would have a bonus like (STRmod + Ath), and trying to sneak up on someone might be (DEXmod + Sub).
To roll a check, compare `d20 + statmod + skillmod + circumstancial_mod` to the difficulty class (picked by the DM).
If the total matches or exceeds the check's DC, the check was passed. 

You can have more specific skills, like lockpicking, or dancing, or bartering, but they have to counterbalanced by specific disadvantages (of appropriate impact), like 'afraid of heights', 'argumentative', 'slow to react'. The DM will help you come up with quirks of your character, and how they might impact play. Every character should have a few; they help shape the character's pesonality. These can develop during play! If your paladin gets attacked by people he trusts too often, he might become less trusting and more wary, increasing his initiative by 1 and hurting his social interactions.

* Defense modifier are `clvl + Statmod`, and they are respectively: Fortitude (Fort), Reflexes (Refl), and Will. (When rolling a save, compare `d20 + defense` against DC)
* Defenses are `10 + defense_mod`. (When rolling an *attack* against a defense, compare `d20 + attack_bonus` against `10+defense`)
* Armor Class (AC) is `10 + Refl + gear` - See the equipment list for that last number.
* Magic Class (MC) is `10 + Will + clvl`
* HP = `STR + 2*clvl + d4(clvl)`
* The initiative modifier is generally DEXmod, though a host of things could modify it (armor, race, quirks, surprise, etc).

### Races

* Human:    +1 to all skills and defenses (not AC)
* Elf:      +1 MND, +1 DEX, +1 Stud
* Dwarf:    +2 STR, +2 HP
* Halfling: +2 DEX, -1 STR, +1 Sub, +1 init
* Half-Elf: +1 DEX or MND, +1 to a skill, +1 to a defense


2.  Combat
------------------

Standard attacks compare `Attack_bonus + d20` against the targets AC (magic attacks use `Magic_bonus + d20 + caster_level`).
The base attack bonus is STRmod for melee weapons, DEXmod for ranged weapons, and MNDmod for magic attacks. (Trained characters can use DEXmod for melee with light weapons if they prefer).

A natural 20 on a d20 is automatically a hit, and deals maximum damage. A nat20 or a spread of 5+ (spread is `roll + mods - AC`) grants an extra attack with a cumulative -3 penalty on the attack roll. Extra attacks in one round may not exceed `max(STRmod, DEXmod)`. When wielding a heavy or two-handed weapon, this extra swing cannot be against the same target. Add STRmod to melee damage rolls (x2 for 2h weapons).

Trained characters may wield two light weapons at a time, and attack with both. They take a -1 on the main hand weapon,
and a -2 on the offhand weapon; the second attack during a turn has an additional -2 penalty if the first attack missed.

Temporary hp are health point buffers - if you have 3 temp hp, and take a hit for 5, you lose the temporaries, and only ake 2 damage. Temporary hp do not stack; if you gain 3 thp and then gain 5 thp, you have 5.

3.  Tricks
----------------

Combat is descriptive rather than tactical. Trying to do something fancy is reasonable - the DM will come up with modifiers to be applied (and will explain them before you commit). Examples: "Run past X, take a swing while running", "Cast magic missile past an ally", "Run at someone full-tilt, and smash into them shield-first."

These are called 'tricks' - write them down when you commit them, so we'll know the modifiers later. They may involve a skill check to perform an impressive stunt, or allowing an attack to hit you (reducing your ac to just Armor-mod) in order to land a bigger attack. If you use a trick a few times, it may be available to 'learn' when you next have the opportunity (see 'Leveling up'); learning a trick reduces its penalty or improves its outcome, because you are practiced at it.

4.  Magic
---------------

Spells cost HP to cast, and that HP can't be restored except by resting - maxHP can't go below 1; after he's reduced to 1 hp,
a caster spends MND or STR directly; if he spends those down to zero, *bad things* happen to him. Each night of rest will only 
restore 1 point of each stat, so don't dip into that reserve unless it is absolutely necessary.

Most spells don't take away any HP unless they succeed - spells that manifest an entity which can miss (fireball, magic missile)
still take HP even if they miss (and misses still hit *something*).

A caster can learn spells up to `ceil(clvl / 2)`. On level up, he gains/learns one spell of each rank he can cast. Spells cost `rank + 1` hp to cast by default. A caster can choose one spell of each rank except the highest they can use to be particularly familiar with (preferably whichever spell he/she casts most often) - that spell costs half as much (round down).

###Modifiers:
  A caster can modify his spells in various ways while casting them. Modifying a spell makes it take longer to cast, and also take more HP.

  - Extend:  lasts twice as long. 2hp extra.
  - Empower: 50% more damage/stronger effect (round up). 4hp extra.
  - Widen:   spell affects twice as much area/ doubles in size. 6hp extra, or double the cost of the spell.
  - Repeat:  cast the spell both this turn and next turn. 1.5x cost (round up). MUST cast the spell again, or take spell-cost damage (real damage) for not casting.

A friendly that is in physical contact with the caster can voluntarily spend their own HP instead of the caster's. An unwilling target can have their HP drained through ritual sacrifice; the vial of blood produced is worth the STR of the victim, and gradually loses it's power (loses one STR per day). Many casters prey on the helpless for this purpose.

5.  Leveling Up
-----------------

Levels are gained at the DM's discretion, generally upon completing some major arc of story (beating the big bad, returning the blessed hand of Edur to the temple, etc).

On gaining a level:

* add +1 to a skill class. On even levels, add +1 to two skill classes.
* add +1 to a stat if the new level is divisible by 3.
* add +1 to two stats if the new level is divislbe by 6.
* add 2+d4 to HP (if str went up, add 1 to that)
* learn a trick if the new level is odd.


