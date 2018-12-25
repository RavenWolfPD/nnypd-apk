# 0.1 Changelist


## Major changes
- New graphics/animations for wielded weapons/shields
- Alternative paths at cave chapter, featuring a new challenging boss and two new mobs
- Added 9 new melee weapons, 2 new shields and 3 new throwing weapons 
- All weapons have chance to cause critical hits (effects vary by weapon type), and most weapons have different bonus
- Every character start with a new bag that can hold throwing weapons and ammunition, and provide an additional slot to equip those weapons, allowing more equipment combinations and strategies
- Some wands where replaced or tweaked to make them more interesting and fun to use
- Removed item deterioration and increased upgrade limit to 5, strength requirement only decrease on odd upgrade levels
- Cursed items no longer have negative levels, but may cause harmful effects on use. Scrolls of upgrade and enchantment can be used to remove curses
- Equipment penalties (to stealth, dodge and accuracy) can be partially reduced with additional strength, but there is a cap now
- Ranged weapons no longer provide combo and have 50% accuracy penalty at close combat
- Penalties for equipping incompatible objects reduced, now is viable to equip a two handed weapon and a shield if you have some excess strength
- Dual wielding is no longer available (will be reintroduced latter), but you can equip one-handed Weapons in the offhand slot to be used at melee if a ranged weapon is on the main hand.
- Alternative paths at caves chapter, featuring a new challenging boss and two new mobs
- Changed some mob's behaviour. Tweaked Tengu battle
- Reworked blocking/parring mechanics. Weapons and shields now display their defencive value, which is used to determine your chances of blocking while guarding 
- Shields can also be used to slam enemies: Deals some damage and have chance to push back enemy (Guaranteed if enemy is exposed). Long click on shield to activate
- Most buff/debuff where reworked/tweaked to make them more unique and balanced
- Starvation damage phase start faster and additional food drops are reduced
- Herb's effects on eat reworked, they now provide more interesting and powerful buffs (and some debuffs)
- Rebalanced/tweaked almost every item in the game



## Detailed Changelog


### Fixes
- Fixed attack times penalties for ranged and throwing weapons 
- Fixed accuracy penalties based on distance
- Ring of shadows wasnt increasing damage on sneak attack
- Dwarven King debuf when knockback was higher than intended
- Succubus Charm debuff duration was higher than intended
- Fixed Yog Fist’s not respawning and adjusted health modifier
- Enemies won't commit suicide if you throw an item in a near charm
- Fixed Harpoons not properly triggering traps 
- Scroll of banishment and scroll of torment debuff duration was higher than intended


### Visuals
- Added graphics for equipped weapons/shields and different animations for attacking (thrust, swing, pistol shot, bow, rifle shot)
- Replaced consumables short names with icons (Credits to ShatteredPD)
- Added sleep animation from moonshinePD (Credits to moonshinePD Team)
- Added new sleep animations for thief, evil eye, vampire, warlock, swarm and elemental
- Tweaked succubus sprite
- Goo boss level have new assets to improve it looks
- Flip some item sprites to match lighting angle with the rest of them (potions, bombs)
- Enlarged shields sprites
- New chakram sprite
- Quarterstaff renamed to Short staff and have a new sprite (Quarterstaff is now a twohanded weapon)
- Added a visual effect to reflect Disrupt debuff

### Features (WIP)
- Cave Chapter is forked in two different subchapter at depth 14  (You have to choose one path to continue) 
- Dark cave subchapter features a new boss battle and a new mob
- Abandoned mine subchapter features DM boss and a new mob
QoL
- Improved auto acquire target mechanic (tagged enemy). It now prioritises the last attacked target if any, and path not blocked, otherwise it will choose the nearest visible enemy.


### General
- Starvation damage phase starts much faster
- Depth 2 exit room no longer hidden
- Piranha rooms will spawn sparkling dust potion (be careful using those) instead of invisibility
- Adjusted traps effect duration
- Reduced amount of waterskin charges, specially on non guaranteed wells
- Reduced mystery meat drop chance


### Equipment
- Added 9 new melee weapons, 2 new shields and 3 new throwing weapons
- Deterioration removed
- Upgrade limit increased to 5
- Only odd upgrade levels will reduce ST requirements (1, 3 and 5)
- Reworked penalties from equipment: penalties can only be reduced by half of their base penalty with excess ST.
- Every player start with a new container (heavy quiver) that holds throwing weapons and missiles
- Added a new slot for throwing weapons and missiles (This slot is inside the quiver)
- OneHanded Heavy weapons can be used as offhand weapon, with a ST penalty of 1+weapon tier
- Shields and two handed weapons can be equipped together with a ST penalty of 1+ weap/shield tier
- Shields and dual weapons can be equipped together but attack speed bonus from weapon is negated
- Shields no longer can be equipped with ranged weapons with the exception of the sling
- Tweaked drop tables (including enchant and curses chances).
- Reworked curse mechanics, items no longer have negative lvls. All cursed weapons and armors are enchanted (enchantment effect is reversed on cursed items).
- Scrolls of upgrade and enchantment can be used to remove items curses
- Starting Items no longer can be found on hero remains
- Ring of durability removed
- New ring of sharpshooting, increase damage with ranged weapons (specially throwing ones) and reduce ranged penalties 


### Armors
- Added min dr Value. This value increases with upgrades and Heavy Armors have greater base value. 
- Excess Strength no longer increases DR bonus 


### Weapons
- Weapons stats rebalanced
- Weapons now have chance to score critical hits, critical effect will be based on type (blade, blunt, thrust, flintlock)
- Every weapon has a Backstab bonus damage modifier (lower for heavy weapons, higher for light ones) 

Most weapons also have different bonus.  As a general rule:
- Swords: better counter damage, Scimitar having the greater modifier.
- Axes: greater critical chances
- Daggers: greater backstab modifiers
- Polearms: can attack enemies from one tile away
- Maces/Flail: will cause Stun on top of dazing enemies on criticals
- Quarterstaff/Moon blades: Better blocking modifiers
- Dual Weapons/knuckles: better attack speed


### Ranged weapons
- At close combat, ranged weapons have half chance to hit (wands excluded)
- Ranged attacks can still miss to unaware/stunned enemies (chance based on distance)
- Ranged attacks dont stack combo and dont gain bonus damage from combo
- Flintlock weapons no longer ignore range penalties
- Flint lock weapons penetrate armor (reduce defence at half) instead of ignoring it.


### Throwing weapons
- Break rate decreased the higher the tier of the weapon
- Special throwing weapons breaks faster
- Harpoons move to Special throwing category as 4th tier for this category
- Harpoons distance displaced reduced (Still based on difference between your ST and enemy)
- Harpoons no longer disable enemies for one turn
- Harpoons no longer draws you towards heavy enemies, but instead the ammunition won't return if attacking a heavier enemy
- Light throwing weapons deals more backstab damage
- Heavy throwing weapons have greater chance to score criticals hits


### Wands
- Wands recharge a bit faster
- Utility wands charges progression reduced to one per lvl (instead of two)
- Removed miscast and zapping additional charges mechanic
- Cursed wands have chances to negatively affect the caster on each zap
- Wand of Entanglement will spread webs to nearby tiles of target point
- Wand of charm buff duration increased
- Wand of blink max distance moved doubled per charge, and can go through critters,  on cast it will blind any enemy near the caster. 
- Wand of Harm replaced with wand of Decay, causes the Decay debuff on the target, dealing unholy damage every turn that increases over time. If the target have less than half health, it will be also withered. 
- Wand of Phasing replaced with Wand of Disruption, spread unstable energy on target location, after spreading, the particles will burst into magical fire, dealing energy damage and disrupting evil entities.
- Wand of Flock removed (Will be replaced soon)


### Consumables Items
- Bombs will explode after two turns
- Anks no longer uncurse items on inventory (only equipped ones)
- Lantern consumes oil at higher rate
- Oil flasks only fill 50% of lanter, amount of spawned oils flasks reduced
- Potion of freeze blob deals damage to chilled enemies in the affected area
- Miasma deals uhnholy damage instead of body
- Removed potion of blessing effect when throw (removed damage to magical critters and uncursing items effect)
- Potion of thunderstorm replaced with sparkling dust: deals shock damage and quickly spread over water (credits to ShatteredPD)
- Added stormvines herbs (used to brew sparkling dust) and fadeleaf (brew invisibilty)
- Herbs have powerful effects while consumed and only take one turn to eat 
- Ring of satiety also increase herbs buff durations
- Scroll of Transmutation behaviour adjusted to work better with the new tier system


### Hero Stats
- Every stat will be increased on leveling (Warrior, mage and acolyte will also gain stealth on level up,  with warrior having a lower increase rate than other characters)
Stealth, awareness and willpower calculations are additive instead of multiplicative
- Base stats for every hero tweaked
- Warrior no longer gain ST on level up
- Awareness now also affect critical chance and expose chance
- Backstab bonus damage is affected by your current Stealth. (Stealth values lower than 100 will reduce/negate the base modifier from the weapon, while higher stealth will increase it)
- The backstab bonus is not applied if you don't see your enemy (like throwing weapons through grass)

### Guarding/Parrying
- Added a new attribute to Shields and melee Weapons: Defensive Value. 
- This attribute represents your chances of blocking an incoming attack. Strength also increases this value
- Enemy roll is based on damage and modified by their awareness to determine if will bypass your defence (so enemies with low/reduced awareness are easier to block).

Guard reworked: 
- Guarding will grant an amount of Blocking instances. 
- Moving or being hit will consume one instance. After all instances are lost Guard stance is lost.
- Guarding with shields, will provide more instances than weapons but reduces your dodge at half.
- Failing a Block with shields will add part of the shield defencive value as bonus AC
- Characters will still attempt to dodge a failed block
- On a successful block there is a chance to leave you enemy Exposed. That chance is no longer constant, and it depends on equipment (shield/weapons), self awareness and enemy awareness
- Shields have less base chance to expose enemy, and is generally lower for high tier shields
- Shield no longer add AC bonus with random chance if equipped
- Shields can also partially block damage from magic bolts while successful blocking 
- An enchanted shield instead can absorb the whole damage if the element of the attack matches the glyph resistance (Example: Fire ward Shield can absorb fire based attacks. Reflection enchantment allows to block damage from any source)


### Buffs
- Enraged damage bonus halved (Now grant 50% more damage instead of 100%)
- Focus buff reduced to 50% more accuracy
- Mending don't instantly remove harmful effects, but makes them wear off faster
- Mind vision buff now allows you to ignore range penalties
- Corrosion is not instantly clear in water, but wear off faster while standing on water tiles
- Combo is not lost after one turn, instead the combo value is halved
- Poison damage reduction nerfed to 25%, no longer decrease attack speed. Damage is applied each two turns
- Withered reductions (damage, healing, armor) reduced to 25%. Wands damage reduction is still 50%
- Wither no longer prevent wands from recharging
- Reintroduced Bleed Debuff
- Blinding Debuff will reduce accuracy, awareness and block chance by 3/4
- Charm no longer reduce wands damage
- Charm duration is reduced instead of removed when damage is received
- Disrupted and Dazed Debuffs will prevent enemies from using magical attacks
- Disrupted also make enemies vulnerable to Energy damage


### Mobs
- Added min DR for mobs, increased Armor class and health scaling
- Charmed mobs will stop fighting each other when duration ends
- Vampire Bats now use hit and run attack (some debuffs can prevent this behaviour)
- Fire elementals can always use its ranged attack
- Evil eyes will attempt to retreat when low on HP (less than half), instead of when full
- Bandits have only two ranged attacks, range increased to 3
- Gnoll brute have only two ranged attacks, enrage start at ⅓ Hp
- Piranhas may cause bleed on hit and will gain bloodthirst buff (double atk spd) if attack a bleeding target
- Piranhas are vulnerable to shock damage
- Succubus drain life doubled (gain same HP as damage dealt)
- Spiders are no longer affected by webs
- Golems may daze their targets on hit
- Wraiths will only use its ranged attack if target is not withered
- Wraith melee attack changed to Unholy damage
- Wraiths are vulnerable to Dispel type (Banish, Dispel, Control)


### Bosses
- Tweaked tengu battle
- Added random corrosion traps to DM-300 battle


### Enchantments/glyphs
- Armor glyphs are more powerful when proc on shields (example: retribution reflect more damage)
- New armor enchantment Repulsion: push back enemies
- Revival enchantment replaced with Holy light (chance to banish magical creatures), still grant resistance to unholy damage
- Unholy enchantment reworked: it now has chance to deals bonus unholy damage. Damage scales based on enemy missing HP
- Deflection now first redirect damage and apply resistances after
- Ethereal weapons will penetrate AC (armor is halved for damage reduction calculation)
- Arcane enchantment will grant an accuracy bonus based on magic skill (⅙*upgrade)


