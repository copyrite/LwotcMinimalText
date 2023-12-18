## Adaptive Aim
Overdrive no longer applies an aim penalty.

## Aggression
+5 crit per enemy in line of sight, up to +30.
* Units visible at squadsight ranges do confer bonus.
* TODO: What's the visibility rule?

## Aid Protocol
Remotely give an ally +{{ AID_PROT_DEFENSE }} defense until the start of your turn.
* {{ AP1 NTE }}
* Defense improves with GREMLIN tiers.

## Aim
+20 aim and +20 crit to your next shot after you Hunker Down.
* TODO: On your next turn?

## Aim Assist
+15 aim and +15 crit against holotargeted units.
* The debuffs from Holotargeter (weapon) and Holo Targeting (ability) both work.

## Airdrop
Remotely give an explosive grenade to an ally.
* Gives a Frag Grenade. If the project "Plasma Grenades" is completed, gives a Plasma Grenade instead.
* {{ AP1 NTE }}
* {{ CHARGES }}

## Alpha Mike Foxtrot
+4 primary weapon damage. +2 primary weapon crit damage.

## Amplify
Target an enemy in sight. It will take {{ AMPLIFY_BONUS_PCT }}% more damage from the next {{ AMPLIFY_NUM_ATTACKS }} attacks.
* {{ AP0 }}
* {{ FOCUS1 }}
* {{ COOLDOWN }}

## Arc Pulser
Your arc thrower can target and damage robotic enemies. -{{ ARC_PULSER_HACK }} to target's hack defense on hit.
* {{ AP1 ET }}
* {{ COOLDOWN }}
* Damage improves with arc thrower tier.

## Arsenal
The BIT can equip and fire heavy weapons.

## Apex Predator
On primary weapon crit, the primary target and enemies in a {{ APEX_PREDATOR_RADIUS }} radius around it have a {{ APEX_PREDATOR_PANIC_CHANCE }}% chance to panic.

## Apotheosis
Bonuses to Rend damage, dodge and mobility per Focus above 2.
* 50% more Rend damage per consumed Focus above 2.
* +20 dodge per consumed Focus above 2.
* +2 mobility per consumed Focus above 2.
* Requires at least 3 Focus.
* {{ AP0 }}
* {{ FOCUSALL }}
* {{ COOLDOWN }}

## Arc Welder
Use your arc thrower to heal a robotic ally for {{ ARC_WELDER_HEAL }} HP.
* TODO: {{ AP1 ET}}?
* {{ CHARGES }}

## Area Suppression
Target an area in a 4-tile radius around an enemy. The area and enemies that enter it become Suppressed.
* Requires 3 ammo. Consumes 2 ammo when used and 1 ammo per reaction shot fired.
* Ends at the start of your turn.
* Ends if you take damage.
* Cannot be used when concealed.
* Cannot be used with a sniper rifle or shotgun.

## Arc Wave
Rend deals damage in a cone behind the primary target.
* Arc Wave does not damage the primary target.
* Arc Wave deals 4/7/10 damage depanding on weapon tier.
* Arc Wave passes through environment.

## Avenger
Once per enemy turn, fire a reaction shot with your primary weapon at an enemy that has taken a hostile action against an ally.
* Avenger will also activate on hostile actions with no target.

## Banish
Fire at a target until you run out of ammo or it dies. The aim of this attack decays by 15 per shot.
* Reveals you.
* {{ COOLDOWN }}

## Battlefield Awareness
Once per turn, you enter Battlefield Awareness on kill. While in Battlefield Awareness, damaging attacks against you are forced to miss. When this happens, you exit Battlefield Awareness and you cannot enter it for {{ SelfCooldown_LW }} turns.
* You will also exit Battlefield Awareness at the start of your turn.
* {{ COOLDOWN }}

## Battlelord
After each enemy in line of sight takes a turn, take an action after their turn is completed. No action points will be refunded (e.g. from Hit and Run).
* Battlelord can allow the Skirmisher to prevail in the most dire of circumstances.
* {{ COOLDOWN }}
* Turns from the Lost and enemy pod reveals do not grant the immediate action.
* Abilities that refund action points, like Implacable and Hit and Run, will not work during Battlelord.

## Biggest Booms
Your grenades and standard rockets have 50% chance to crit. Their crit damage is 3.
* +1 to damage-per-turn effects from critical hits with grenades.
* The critical chance provided by Biggest Booms cannot be modified in any way.

## Blademaster
+1 melee damage. +10 aim with melee attacks.

## Bladestorm
You will reaction attack with your {{ BOUND_WEAPON_NAME }} enemies that enter, exit or attack from melee range on enemy turns.
* Will not trigger if you are concealed.
* TODO: Impairments?

## Blinding Protocol
Remotely disorient a non-robotic enemy and other non-robotic enemies in a {{ BLINDING_PROTOCOL_RADIUS }} tile radius around it.
* Squadsight targeting with line of sight required.
* {{ AP1 ET }}
* {{ COOLDOWN }}

## Blood Trail
+2 ranged attack damage and ignore 40 dodge of targets that have taken damage after the start of their turn.

## Bluescreen Bombs
Your Flashbangs disorient robotic enemies and apply -{{ BLUESCREEN_BOMBS_HACK }} hack defense on hit.
* TODO: Duration?

## Bluescreen Knives
+2 pierce with throwing knives. Your throwing knife attacks disorient robotic units on hit.

## Body Shield
Give an enemy in sight -20 aim against you and -50 crit against you.
* {{ AP0 }}
* {{ COOLDOWN }}
* TODO: Duration?

## Bombard
Deal damage to all units in a {{ BOMBARD_RADIUS_TILES }} tile radius around a tile seen by the squad.
* {{ AP1 NTE }}
* Squadsight targeting with no line of sight required.
* Damage improves with BIT tier.

## Bombardier
+{{ BOMBARDIER_RANGE }} grenade launch and throw range.

## Boosted Cores
+1 grenade damage. +1 to damage-per-turn effects from grenades.

## Both Barrels
Fire your sawed-off shotgun at a nearby enemy. Base damage is doubled. Consumes 2 charges.
* {{ AP1 ET }}

## Brawler
You take {{ BRAWLER_DR_PCT }}% less damage from enemies in a {{ BRAWLER_RADIUS }} tile range.

## Bring 'Em On
Your primary weapon and explosives have +1 crit damage per every 2 enemies you can see, up to a maximum of +8.
* TODO: Units visible at squadsight ranges apply. (But do you need squadsight for it?)

## Brutality
Non-robotic enemies have a 50% chance to panic when you kill a non-robotic enemy in a {{ BRUTALITY_RADIUS_TILES }} tile range of it with a sawed-off shotgun.

## Bulwark
+{{ BULWARK_ARMOR }} Armor. You are a high cover object.

## Bunker Buster
Fire a rocket that deals moderate damage and huge environmental damage in a large area of effect.
* {{ AP2 }}
* {{ CHARGES }}

## Burnout
You leave a smoke cloud with a {{ BURNOUT_RADIUS }} tile radius centered at your position when you attack with your flamethrower.
* +20 defense to all units on tiles with Burnout smoke.

## Capacitor Discharge
Remotely deal damage and a {{ CAPACITOR_DISCHARGE_RADIUS }} tile radius around a location. Affected units have a chance to be stunned. Robotic units take more damage.
* Uses per mission: {{ CAPACITOR_DISCHARGE_CHARGES }}
* Damage improves with GREMLIN tier.

## Center Mass
+1 damage with guns.
* If your primary weapon is not a gun, +1 primary weapon damage.

## Chain Lightning
Fire your arc thrower at a target that you can stun. Chain Lightning bounces up to {{ CHAIN_LIGHTNING_CHAINS }} other targets within {{ CHAIN_LIGHTNING_RADIUS }} tiles.
* {{ AP1 ET }}
* {{ COOLDOWN }}
* Cannot be used when concealed.

## Chain Shot
Fire a shot with -10 aim. If you hit, you fire another shot with -10 aim.
* {{ COOLDOWN }}
* Chain Shot can be devastating against non-cover enemies, or when augmented with aim bonuses.

## Channel
Enemies have a chance to drop Psionic Loot when they die. Any unit with Focus can collect Psionic Loot to raise their Focus level.
* Non-psionic enemies have {{ CHANNEL_NONPSI_CHANCE }}% chance to drop Psionic Loot.
* Psionic enemies have {{ CHANNEL_PSI_CHANCE }}% chance to drop Psionic Loot.
* TODO: Can any unit with Focus collect it?

## Channeling Field
You gain a stack of Channeling Field when an enemy targets you. +1 standard shot damage per stack. Lose all stacks when you fire a standard shot.

## Cheap Shot
Once per turn, gain a movement action after firing your primary weapon at a unit that was damaged after the start of its own turn.
* Cannot trigger on the same turn as Knife Encounters.
* TODO: Does it work for special shots or not?

## Close and Personal
+30 crit chance against adjacent targets. This bonus decays by 5 per 1 tile of distance to the target.

## Close Combat Specialist
You will reaction attack with your primary weapon enemies that enter, exit or attack in a {{ CCS_RADIUS }} tile range on enemy turns.
* Will not trigger if you are concealed.
* Only targets each enemy once per turn.
* {{ AMMO }}

## Close Encounters
Once per turn, gain an action after firing a standard shot with your primary weapon at an enemy in a {{ CE_RADIUS }} tile radius.
* A red ring will mark the range of this ability.
* Cannot trigger on the same turn as Hit and Run.
* Cannot trigger on the same turn as Run and Gun. Run and Gun cannot be used if you have gained an action from Close Encounters.

## Combat Awareness
+15 defense when on Overwatch. +1 Armor when on Overwatch.
* This ability does not provide defensive bonuses if the unit is disoriented, stunned, panicking, on fire or otherwise impaired.

## Combat Engineer
Bonuses to environmental damage of your explosives. Your explosives' environmental damage no longer suffers from falloff.
* TODO: What are the numbers?

## Combat Fitness
+{{ COMFIT_AIM }} aim. +{{ COMFIT_MOB }} mobility. +{{ COMFIT_HP }} HP. +{{ COMFIT_WILL }} will. +{{ COMFIT_DODGE }} dodge.

## Combat Presence
Give an action to a visible ally.
* {{ AP1 NTE }}
* {{ COOLDOWN }}
* TODO: Are VIPs, rebels, etc. valid targets?

## Combat Protocol
Remotely deal guaranteed damage to an enemy in squadsight range. Additional damage against robotic enemies.
* {{ CHARGES }}
* Damage improves with GREMLIN tier.

## Combatives
You will parry and counter melee attacks that graze or miss against you. +90 dodge against the first melee attack against you each turn.\
Passive: +10 dodge.
* Combatives does not trigger against area of effect melee attacks.

## Conceal
Enter concealment.
* {{ AP1 ET }}
* Cannot be used while concealed.
* Cannot be used when flanked by enemies that see you.

## Concentration
Your grazes are converted to normal hits.
* The hit result conversion happens after the usual hit-miss-crit-dodge resolution.

## Concussion Rocket
Fire a rocket that deals low damage and has a chance to stun or disorient non-robotic enemies on hit.
* {{ CONC_ROCKET_STUN_CHANCE }}% chance to stun non-robotic enemies. Always disorients non-robotic enemies that are not stunned.
* {{ AP1 ET }}
* {{ CHARGES }}
* Allies are immune to all effects, including damage.
* TODO: Scatter rules?

## Cool Under Pressure
+10 aim with reaction attacks. Your reaction attacks now have a crit roll.

## Coup de Grâce
+{{ CDG_AIM }} aim, +{{ CDG_CRIT }} crit, and +{{ CDG_DAMAGE }} damage to your {{ BOUND_WEAPON_NAME }} attacks against stunned and panicking enemies. Bonuses apply at 50% effectiveness against disoriented enemies.

## Covering Fire
Reaction shots confer an aim malus on enemies and can now be triggered by any enemy action, not just movement.
* If triggered by an enemy action, Covering Fire will trigger before the enemy action completes.
* In addition, having the Covering Fire ability confers a temporary aim penalty upon any units you take a reaction shot at, regardless of whether it was a covering fire shot or not.
* The penalty does not affect the current action an enemy takes if it is aim-based and would only apply in the next turn. This means that if a covering fire shot was taken against an enemy performing an aim-based action, that action does not suffer the penalty.

## Covert
25% reduced detection range.
* Does not apply to ADVENT security towers.
* Infiltration rate bonus? How does that work?

## Crippling Strike
Throw a knife that Maims the target on hit for a 1 turn duration.
* Maimed enemies have 0 mobility.
* Breaks concealment, but not Shadow.
* {{ COOLDOWN }}

## Crusader's Rage
You deal 25% more damage per every 25% HP missing, up to 50%. Your wound recovery times are reduced by {{ CRUSADERS_RAGE_HEAL }} HP.
* Wound recovery time reduction is not applied if the soldier entered a bleeding out state during the mission.

## Cutthroat
+15 crit, +2 crit damage and infinite pierce to melee attacks against non-robotic enemies.
* TODO: Non-robotic or organic?

## Cyclic Fire
Fire three shots with -{{ CYCLIC_FIRE_AIM }} aim.
* {{ AP2 }}
* {{ COOLDOWN }}
* {{ AMMO }}
* Does not work with shotguns or sniper rifles.

## Damage Control
Once per turn, gain +2 Armor after you take damage. If you gained Armor this way, lose 2 Armor at the start of your turn.

## Damn Good Ground
+10 aim and +10 defense against targets at a lower elevation.
* This ability does not provide defensive bonuses if the unit is disoriented, stunned, panicking, on fire or otherwise impaired.

## Danger Zone
Your Area Suppression radius is 5 tiles.

## Deadeye
Fire a shot with 15% less aim and 50% more base damage.
* {{ COOLDOWN }}

## Death Dealer
Weapon crit damage is doubled against flanked targets while in Shadow.\
Passive: +25 crit chance.

## Death From Above
Once per turn, gain an action after killing an enemy at a lower elevation with your primary weapon. Long range aim penalty is halved for sniper rifles and vektor rifles.
* Aim penalty from sources such as Snap Shot is not halved.
* TODO: Can the penalty just be called "Squadsight aim penalty"?

## Dedication
+2 mobility until the start of your turn. Ignore reaction fire until the start of your turn.
* {{ AP0 }}
* {{ COOLDOWN }}

## Deep Cover
If you did not use hostile actions this turn, hunker down automatically.

## Demolition
Destroy or damage the cover of an enemy. Deals no damage to the target.
* {{ AMMO }}
* {{ COOLDOWN }}

## Dense Smoke
+10 defense from your Smoke grenades.

## Disabling Shot
Fire a shot that stuns for 2 actions on hit. +2 stun duration on crit. Deals 50% reduced base damage and critical hits are converted to normal hits.
* The hit result conversion happens after the usual hit-miss-crit-dodge resolution.
* The hit result conversion causes Disabling Shot to never trigger other effects that depend on dealing a critical hit, other than its own bonus stun duration.
* {{ COOLDOWN }}

## Disassembly
You gain a stack of Disassembly when you kill an enemy. +20 hack per stack. Each stack has a 3 turn duration.

## Double Tap
Fire a standard shot, then gain another action that can only be used for shooting or overwatching.
* {{ COOLDOWN }}
* Same action cost as standard shot with your weapon (Snipers cost 2 AP and all other weapons cost 1)
* TODO: reword action cost bullet?

## Electroshock
Your arc thrower disorients the target on miss.
* What about robots?

## Evasive
You start the mission with +100 dodge. You lose this bonus when you take damage.

## Ever Vigilant
You will enter overwatch at the end of the turn if you only used movement actions this turn.

## Executioner
+20 aim and +20 crit chance against targets at 50% or less health.

## Extra Conditioning
-1 to Run and Gun cooldown.

## Failsafe
Negative effects no longer occur when you fail a hack.
* Negative effects prevented by Failsafe include breaking squad concealment.

## Field Medic
+2 charges to equipped Medikits.
* TODO: Medical Protocol?

## Field Surgeon
Wound recovery times of all organic squad members are reduced by 1 HP.
* Multiple units with Field Surgeon on a mission have a chance to reduce wound recovery time further.
* Wound recovery time reduction is not applied to units that entered a bleeding out state during the mission.
* TODO: What's the chance?

## Fire and Steel
+1 XCOM gauntlet attack damage. +1 damage per turn to fires set by XCOM gauntlet attacks.

## Fire in the Hole
-2 to number of rocket scatter rolls.
* TODO: Concussion Rocket?

## Firestorm
Dash to a position and spray fire in a {{ FIRESTORM_RADIUS_TILES }} tile range.\
Passive: You are immune to fire damage.
* Firestorm deals +2 damage over your Flamethrower's base damage.
* {{ AP2 }}
* {{ CHARGES }}
* It is not recommended the soldier uses Firestorm on rooftops.

## Flashbanger
You start the mission with +1 Flashbang.

## Fleche
Dash to an enemy within movement range and attack it with your sword. Bonus damage against more distant targets.
* +1 damage per every 4 tiles of distance between your position at the start of the turn and your target, up to 5.

## Flush
Fire a shot with +30 aim and 50% less base damage. Debuffs the target for -10 defense and -30 dodge on hit. Forces the target to move on hit.
* {{ AMMO }}
* {{ COOLDOWN }}
* 1 turn debuff duration.
* Does not apply bonus ammo effects.
* Cannot crit.
* Cannot be used when concealed.

## Focus
Gain Focus during missions. Focus can be spent on powerful abilities and modifies the stats of some abilities.
* Your primary source if Focus is Rend, which generates Focus after you attack.

## Formidable
+2 ablative hit points. 50% less explosive damage taken.

## Fortify
+20 defense until the start of your turn.
* {{ AP0 }}
* {{ COOLDOWN }}

## Full Kit
Grenades in utility slots have +1 charges.
* Applies to explosive and support grenades as well as Battle Scanners.
* Extra grenades provided by Smoker and Flashbanger abilities do not get extra charges.
* TODO: reword?

## Full Override
Remotely shutdown or permanently control an enemy robot. Permanently controlled MECs that survive the mission become Resistance MECs.
* Success chance is based on a contest of your hack and target's hack defense.
* Greater Shutdown stuns the target for 6 actions.
* Master Enemy permanently controls the target and gives it a stat bonus. If it is a MEC and it survives, it will become a Resistance MEC in the mission region.
* {{ AP1 ET }}
* {{ CHARGES }}
* Failed attempts do not consume charges.
* {{ COOLDOWN }}

## Full Throttle
You gain a stack of Full Throttle when you kill an enemy. +3 mobility per stack. Each stack has a 2 turn duration.

## Ghost
Raise a Ghost from the body of a fallen humanoid. The Ghost expires when it loses all Focus. Costs 2 Focus.
* Ghosts are copies of yourself. It starts with your Focus level minus 1, and its Rend consumes 1 Focus.
* Ghost must be cast on the corpse of a humanoid enemy, and cannot be cast on the same corpse twice.
* {{ COOLDOWN }}
* Ghosts cannot gain following abilities: Volt, Shield bash, Shield abilities, Deflect, Reflect, Solace, Void Conduit, Bladestorm, Apotheosis, Superior Aptitude, Ionic Storm and Sustain.
* TODO: Which abilities can they even gain?

## Ghost Grenade
Throw a specialized smoke grenade to conceal a squad member in line of sight.
* Does not use grenade targeting and only conceals a single unit.
* Produces a smoke cloud centered at the target. +20 defense to units in Ghost Grenade smoke.
* {{ AP1 ET }}
* {{ CHARGES }}
* Cannot be used while concealed.
* Cannot target civilians.

## Ghostwalker
Reduce your detection range almost 25% for 2 turn(s).
* Does not apply to ADVENT security towers.
* {{ COOLDOWN }}
* {{ AP0 }}
* TODO: You gain infiltration bonuses. How do they work?

## Grapple
Deploy a grappling hook to move to an elevated position.
* {{ AP0 }}
* {{ COOLDOWN }}

## Grazing Fire
Your primary weapon misses have 50% base chance to be converted to a graze.
* -1% chance to convert misses to grazes per 1 dodge on target.
* This effect occurs after normal hit-miss-graze processing.

## Greater Padding
Reduce wound recovery time for this soldier by 1/2/4 HP.
* Greater Padding reduces the number of hit points a soldier must heal after being wounded in battle by 1/2/4.
* Wound recovery time reduction is not applied to units that entered a bleeding out state during the mission.

## Hack
Remotely hack an object with your {{ BOUND_WEAPON_NAME }}.
* The target needs to be in your sight.

## Hail of Bullets
Fire a shot that is guaranteed to hit.
* {{ AMMO }}
* {{ COOLDOWN }}
* Cannot be used with shotguns or sniper rifles.

## Hard Target
+5 dodge per enemy in sight, up to +30.
* Units visible at squadsight ranges do not confer bonus.
* This ability does not provide defensive bonuses if the unit is disoriented, stunned, panicking, on fire or otherwise impaired.
* TODO: What's the visibility rule?

## Haywire Protocol
Remotely shutdown or control an enemy robot.
* Success chance is based on a contest of your hack and target's hack defense.
* Shutdown stuns the target for 2 actions.
* Control Enemy controls the target for {{ HAYWIRE_PROT_CONTROL_TURNS }} turns.
* {{ AP1 ET }}
* {{ COOLDOWN }}

## HEAT Warheads
+2 pierce with grenades. +1 shred with grenades.
* The grenade must shred innately to benefit from the additional shred.

## Heavy Weapons
You can equip the XCOM gauntlet, a combination Rocket Launcher and Flamethrower.
* The Rocket Launcher may be targeted at any tile in sight range. It has a 3 tile radius and its damage is subject to falloff.
* When you launch a rocket, you roll a series of aim checks to determine how many tiles a rocket scatters. Each failed roll increases scatter by 1 tile. The base number of scatter rolls is 4. If you only have one action remaining, you have +2 number of scatter rolls.
* Rocket launcher charges: 1
* The flamethrower is a short-range weapon that causes damage to multiple targets within a cone-shaped area of effect.
* Flamethrower charges: 2
* {{ AP1 ET }}

## Heavy Ordnance
Damaging grenades in your grenade-only slot have +1 charges.

## HiDef Holo
All units have +10/+15/+20 crit chance against your Holotargeted enemies.
* Applies to Holo Targeting, Rapid Targeting, and Multitargeting.

## Hipfire
Firing your sawed-off shotgun no longer ends the turn.

## Hit and Run
Once per turn, gain an action after firing a standard shot at a flanked enemy with your primary weapon.
* Cannot trigger on the same turn as Hit and Run.
* Cannot trigger on the same turn as Run and Gun. Run and Gun cannot be used if you have gained an action from Hit and Run.
* Bonus full actions from Serial and Death from Above will be awarded first.

## Holo Targeting
You primary weapon attacks Holo Target enemies. All units have +15 aim against your Holo Targeted enemies.
* Directed primary weapon-specific abilities will apply Holo Targeting.
* Abilities that target multiple units will not apply Holo Targeting.
* 1 turn duration.

## Holotarget
Use your Holotargeter to Holotarget an enemy. All units have +10/+15/+20 aim against your Holotargeted enemy.
* {{ AP1 ET }}
* 1 turn duration.
* Does not break concealment.
* TODO: What if you have the perk (not the weapon)?

## Homing Mine
Attach an explosive to an enemy. It will explode when that enemy takes damage.
* {{ AP1 NTE }}
* {{ CHARGES }}
* Attacks against targets with a homing mine attached never miss.
* Does not break concealment.
* TODO: What's the guaranteed hit/never miss rule?

## Hunter Protocol
When an enemy makes a scamper move, you have a 33% chance to reaction attack it with your primary weapon.

## Hunter's Instincts
+2 damage with ranged attacks against flanked enemies.

## Impact Compensation
You gain a stack of Impact Compensation after you take damage. Damage is reduced by 20% once per stack. Stacks are lost at the start of your turn.

## Impact Fields
Take 33% less damage. 2 turn duration.
* {{ COOLDOWN }}
* {{ AP1 NTE }}

## Impersonal Edge
Gain a stack of Impersonal Edge and reduce your Shadow cooldown by 1 when you kill with a Throwing Knife. +20 aim per stack. Each stack has a 3 turn duration.

## Implacable
Once per turn, when you kill an enemy, you gain a movement action.

## Impulse
+10 aim and +10 crit chance if you have moved this turn.
* TODO: Until the start of your turn, right?

## Incinerator
+2 flamethrower length. +1 flamethrower width.
* Roust?
* Firestorm?

## Independent Tracking
+1 to your Holotargeting duration.
* Applies to Holo Targeting, Rapid Targeting, and Multitargeting.

## Indomitable
Once per turn, when an enemy targets you, gain 1 focus.
* Reaction attacks are not targeted.

## Infighter
+40 dodge against attacks in a {{ INFIGHTER_RADIUS_TILES }} tile range.
* This ability does not provide defensive bonuses if the unit is disoriented, stunned, panicking, on fire or otherwise impaired.

## Inspire Agility
Give an ally +30 dodge until the start of your turn. You gain an extra charge on kill.
* {{ COOLDOWN }}
* {{ CHARGES }}
* {{ AP0 }}

## Interference
Remotely cancel the Overwatch of an enemy.
* Squadsight targeting.
* {{ AP0 }}
* {{ CHARGES }}
* Number of charges increases with GREMLIN tier.

## Interrupt
A powerful form of Overwatch. Instead of firing automatically, perform any single action. Free action.
* {{ AP0 }}
* Some actions are not available during Interrupt, like Overwatch.
* {{ COOLDOWN }}

## Intimidate
After an enemy targets you, it has a chance to panic.
* Reaction attacks are not targeted.
* Chance to panic improves with armor tier.
* TODO: What's the panic chance?

## Invert
Switch locations with a unit. Costs 1 Focus.
* {{ COOLDOWN }}
* Can target both ally and enemy units.

## Ionic Storm
Dash to a location, then deal damage in a {{ IONIC_STORM_RADIUS_TILE }} tile range. Additional damage and range per Focus. Consumes all Focus.
* Ionic Storm's base damage is doubled against psionic units.
* {{ COOLDOWN }}
* TODO: Focus on kills?

## Iron Curtain
Attack enemies in a cone for 50% less base damage. -8 to target mobility on hit.
* {{ COOLDOWN }}
* Consumes 3 ammo.
* Debuff has 2 turn duration.
* Blocked by high cover.
* Does not apply ammo effects.
* Cannot be used with a sniper rifle or shotgun.

## Javelin Rockets
+6 tiles to rocket range. You can target rockets at tiles outside your visual range.

## Judgement
After an enemy targets you, it has a chance to panic. The chance is based on a contest of wills.
* Reaction attacks are not targeted.
* The base chance to panic is 30%.
* The minimum and maximum panic chance are 5% and 90%.

## Justice
Use the Grapple to pull a humanoid target to you and attack it with your Ripjack.
* Only the pull is subject to an aim roll. The Ripjack attack is guaranteed to hit.
* Requires an empty tile adjacent to you.
* {{ COOLDOWN }}

## Kill Zone
Fire a reaction shot against any enemy that moves or attacks within a cone of fire.
* If you have Squadsight, Kill Zone shots are taken at squadsight range.
* {{ COOLDOWN }}

## Killer Instinct
+50% more damage with critical hits while in Run and Gun.

## Knife Encounters
Once per turn, gain an action after throwing a knife at an enemy in a {{ KNIFE_ENCOUNTERS_RADIUS }} tile range.
* A red ring will mark the range of this ability.
* Cannot trigger on the same turn as Hit and Run.
* Cannot trigger on the same turn as Close Encounters.
* Cannot trigger on the same turn as Run and Gun. Run and Gun cannot be used if you have gained an action from Close Encounters.

## Knife Fighter
Attack an adjacent enemy with your combat knife.
* {{ AP1 NTE }}

## Knife Juggler
+1 throwing knife damage. +1 throwing knife charges. You gain a throwing knife charge when you kill with your primary weapon.

## Launch Grenade
You use your grenade launcher to launch grenades, rather than throwing them. Bonus to grenade launch range. Gain a grenade slot.
* {{ AP1 ET }}
* {{ COOLDOWN }}
* Grenade launch range improves with grenade launcher tier.

## Lead The Target
Target an enemy. Fire a shot at it with +{{ LEAD_TARGET_AIM_BONUS }} aim if it moves.
* {{ AP2 }}
* {{ COOLDOWN }}
* To fire the shot, you need line of sight to the enemy when it moves.
* Lead The Target ends if you haven't fired the shot until the start of your turn.
* Lead The Target is not a reaction attack, despite activating on enemy movement.

## Lethal
+2 primary weapon damage. +1 primary weapon crit damage.

## Lick Your Wounds
Heal for 2 HP when you Hunker Down, up to 8 per mission. Remove poison, burning, and acid burning when you Hunker Down.
* TODO: Does the heal also work if you're out of charges?

## Light 'Em Up
Your standard shots no longer end your turn.
* Light 'Em Up replaces your primary weapon's standard shot. It counts as a standard shot.

## Lightning Reflexes
You have +100 defense against reaction attacks. This bonus decays by 20 per reaction attack against you after the start of your turn.
* This ability does not provide defensive bonuses if the unit is disoriented, stunned, panicking, on fire or otherwise impaired.

## Lightning Slash
Move to an enemy within the range of a single move and attack it with your {{ BOUND_WEAPON_NAME }}.
* {{ AP1 NTE }}
* {{ COOLDOWN }}

## Like Lightning
When you enter Run and Gun, your arc thrower cooldown resets to 0.
* Does not apply to Chain Lightning.

## Lingering Shadow
+15 defense and +30 dodge after you are revealed from Shadow. 1 turn duration.

## Lock 'N Load
+1 ammo on primary weapon kill.

## Lockdown
+20 aim with attacks that trigger when a target you are suppressing moves.

## Locked On
+20 aim and +10 crit to attacks against the target of your previous primary weapon attack.
* Area-of-Effect-based shots do not grant the bonus.

## Lone Wolf
+12 aim and +12 defense if you are at least 7 tiles away from the nearest ally. This bonus decays by 3 aim and 3 defense per tile.
* This ability does not provide defensive bonuses if the unit is disoriented, stunned, panicking, on fire or otherwise impaired.

## Long Watch
Replaces Overwatch. Long Watch can trigger at Squadsight range.

## Low Profile
Low cover counts as high cover for you.

## Maim
Fire a shot that Maims the target on hit.
* Maimed enemies have 0 mobility.
* {{ COOLDOWN }}

## Manual Override
Lowers all ability cooldowns on a selected ally soldier by up to 3 turns.
* {{ 1AP NTE }}
* {{ COOLDOWN }}
* TODO: Action cost?

## Marauder
Your standard shots no longer end your turn.

## Mayhem
25% more damage with attacks that trigger when a target you are suppressing moves.

## Mechanical Chassis
You are immune to fire and poison.

## Medical Protocol
Remotely heal or stabilize an organic ally. +1 charge per equipped medikit.
* {{ AP1 NTE }}
* Healed HP improves with GREMLIN tier.

## Momentum
You gain a Momentum action after you use Rend. Momentum actions can be used for movement or deploying your Templar Shield.

## Multitargeting
Holotarget all enemies in a 4/5/6 tile radius around an enemy.
* {{ AP1 ET }}
* {{ COOLDOWN }}

## Napalm-X
Your Flamethrower can now panic enemies.
* TOOD: What's the panic chance?

## Needle
+2 pierce to shots fired in Shadow.

## Needle Grenades
+1 explosive damage against unarmored targets. You never destroy loot and corpses of enemies you kill.

## Neutralizing Agents
Aid Protocol now removes fire, poison, acid, and bleeding.

## None Shall Pass
Once per enemy turn, you will reaction fire your sawed-off shotgun against an enemy that moves or attacks in a 3 tile range. This attack can critically hit.
* Will not trigger if you are concealed.
* Works during any enemy turn: Alien, Lost, Chosen and Ruler.

## Nova
Deal damage to all units in a {{ NOVA_RADIUS_TILES }} tile range. You take 0 damage from the first Nova in a mission, and afterwards 2 damage per Nova you've used in the mission.
* {{ AP0 }}
* {{ COOLDOWN }}

## One For All
-30 defense and bonus ablative HP until the start of your turn. You are a high cover object until you move or attack.
* {{ AP1 ET }}
* Can be used with a Momentum action.

## Open Fire
+10 aim and +10 crit with ranged attacks against targets at full health.

## Overcharge
+5 aim per Focus and +10 crit per Focus to melee attacks.

## Overdrive
Gain an action. No action ends turn. While in Overdrive, your aim decays by -15 per primary weapon attack until the start of your turn.
{{ AP0 }}
{{ COOLDOWN }}

## Overkill
+2 damage with ranged attacks against units at 50% HP or less.

## Packmaster
Items in utility and grenade slots have +1 charges.

## Paramedic
Dash to an organic ally and heal or stabilize it. +2 charges per equipped medikit.
* {{ CHARGES }}
* {{ AP1 NTE }}

## Parkour
-1 to Grapple cooldown.

## Phantom
You remain concealed when the squad concealment breaks. You start the mission concealed even if the mission starts without squad concealment.
* If you are detected, you break your individual concealment and squad's concealment.

## Phosphorus
Your flamethrower attacks deal their base damage to fire immune enemies. Your flamethrower attacks now shreds 1 Armor.

## Pillar
Place a high cover object.
* {{ AP0 }}
* Duration: Equal to Focus level when cast. 1 turn minimum duration.
* {{ COOLDOWN }}

## Point Blank
Fire your sawed-off shotgun at a nearby enemy.
{{ AP1 ET }}

## Precision Shot
Fire a shot with +30 crit. Precision Shot deals 34% more damage with critical hits.
* {{ COOLDOWN }}

## Predator
+15 aim and +15 crit with ranged attacks against flanked enemies.

## Preservation
+15 defense after you are revealed. 2 turn duration.

## Protector
Support grenades in your grenade-only slot have +1 charges.
* Examples of support grenades include Flashbangs, Smoke grenades, Battlescanners and Shaped charges.

## Pump Action
+2 sawed-off shotgun charges. 

## Quickburn
Your next flamethrower attack will not cost an action.
* Works with Flamethrower and Roust.
* {{ COOLDOWN }}

## Quick Zap
Your next arc thrower attack will not cost an action.
* {{ COOLDOWN }}
* Applies to Stun and Arc Pulser.

## Rainmaker
+2 damage with heavy weapons. +2 to heavy weapon radii. +2 to heavy weapon cone length. +2 to heavy weapon cone width.

## Rapid Deployment
Your next use of a support grenade will not cost an action.
* {{ COOLDOWN }}
* Examples of support grenades include Flashbangs, Smoke grenades, Battlescanners and Shaped charges.

## Rapid Fire
Fire twice with -15 aim.
* {{ COOLDOWN }}

## Rapid Reaction
Up to 2 times per turn, +1 Overwatch shot when you hit with an Overwatch shot.
* If you can fire additional Overwatch shots unconditionally, they can start new Rapid Reaction chains.

## Rapid Targeting
Use your Holotargeter to debuff an enemy. All units have +10/+15/+20 aim against the target.\
Passive: Holotargeting and Multitargeting do not end your turn.
* {{ COOLDOWN }}

## Ready For Anything
You enter Overwatch after you fire a turn-ending standard shot with your primary weapon.

## Reaper
While in Reaper, you gain an action on melee kill. The first melee attack in Reaper will not miss. -2 melee damage per melee attack you've made in Reaper this turn.
* {{ COOLDOWN }}
* Reaper and Run and Gun cannot be used on the same turn.
* TODO: What does it mean to not miss?

## Reckoning
Dash to an enemy within movement range and attack it with your Ripjack.
* {{ AP1 NTE }}
* Only costs 1 action even if you would need more actions to reach the target.
* {{ COOLDOWN }}

## Reflex
Once per enemy turn, gain an action on your next turn when an enemy attacks you. -15 to enemy crit chance against you.

## Remote Start
Detonate an environmental explosive for double damage and double explosion radius. Does not break concealment.
* {{ COOLDOWN }}
* {{ CHARGES }}
* TODO: It doesn't reveal from Shadow, but what about concealment?

## Rend
Dash to an enemy within movement range and attack it with your gauntlet. Gain a Momentum action and +1 Focus after you attack.
* Rend has {{ REND_DISORIENT_CHANCE }}% chance to disorient and {{ REND_STUN_CHANCE }}% chance to stun.
* Stunned targets will also be knocked back.

## Rend The Marked
Throwing knives apply a stacking debuff of +50 crit chance against the target per stack. Each stack has a 1 turn duration.

## Repair
Use your BIT to heal a robotic ally for 6 HP.
* {{ AP1 NTE }}
* {{ CHARGES }}
* Healed HP improves with BIT tier.

## Reposition
Once per turn, gain an movement action after firing a standard shot with your primary weapon at a flanked target.

## Rescue Protocol
Remotely give +15 dodge, +5 mobility and a movement action to an ally with no remaining actions.
* Not usable on units that are Concealed, Suppressing or on Overwatch.
* A unit cannot be the target of both Command and Rescue Protocol on the same turn.
* {{ AP1 NTE }}
* {{ CHARGES }}
* Number of charges increases with GREMLIN tier.

## Resilience
-30 to enemy crit against you.

## Restoration
Remotely heal or revive all organic squad members.
* {{ CHARGES }}
* Healed HP improves with GREMLIN tier.

## Retribution
You will reaction attack with your {{ BOUND_WEAPON_NAME }} enemies that enter, exit or attack from melee range on enemy turns.
* Will not trigger if you are concealed.
* Impairments?
* TODO: How to sync with Bladestorm?

## Return Fire
Once per turn, after an enemy targets you, you fire back with your primary weapon.
* Reaction fire is not targeted.

## Revival Protocol
Remotely revive a squadmate from being disoriented, stunned, panicked, or unconscious.
* {{ AP1 NTE }}
* {{ CHARGES }}
* Number of charges increases with GREMLIN tier.

## Ripjack Slash
Attack an adjacent enemy with your Ripjack.
* {{ AP1 NTE }}

## Roust
Flamethrower attack with +{{ ROUST_LENGTH }} length, -{{ ROUST_WIDTH}} width, {{ ROUST_BURN_CHANCE }} chance to burn and -{{ ROUST_DAMAGE_PENALTY }}% less base damage. Forces targets to move on hit.
* {{ CHARGES }}
* Cannot be used from concealment.

## Ruthless
You gain an action when you kill a panicked or disoriented enemy with your sawed-off shotgun.

## Run and Gun
Gain a non-movement action.
* {{ AP0 }}
* {{ COOLDOWN }}

Rupture
Fire a shot with +50 crit and ruptures the target for 3.
* Targets ruptured by this attack take +3 damage from all attacks for the rest of the mission.
* {{ AMMO }}
* {{ COOLDOWN }}

## Sacrifice
Move to a position and redirect all ranged attacks against allies in a {{ SACRIFICE_RADIUS_TILES }} tile range to yourself. +10 defense and +1 Armor until the start of your turn.
* {{ COOLDOWN }}
* TODO: All ranged, probably?

## Salvo
Grenade throws, grenade launches, heavy weapon attacks and XCOM gauntlet attacks(?) are no longer turn ending.

## Sapper
Bonuses to environmental damage of your explosives.

## Saturation Fire
Attack enemies and deal environmental damage in a cone.
* Saturation Fire is equivalent to firing a standard shot at all targets in the cone, and damaging or destroying random cover elements in it.
* {{ AMMO }}
* {{ COOLDOWN }}

## Savior
+4 to healed HP of your GREMLIN heal, medikit heal and Restoration.

## Scanning Protocol
Scan all units in a {{ SCANNING_PROT_RADIUS_TILES }} tile range, including hidden or disguised units. +{{ SCANNING_PROT_LOS_TILES }} tiles to line of sight for a {{ SCANNING_PROT_LOS_DURATION }} turn duration.
* You will see scanned enemies through walls for a {{ SCANNING_PROT_DURATION }} turn duration.
* {{ AP0 }}
* {{ CHARGES }}
* Number of charges increases with GREMLIN tier.
* Passive: 40% less chance to recruit Faceless when you are the Haven adviser.

## Scrap Metal
+1 sawed-off shotgun charge when you kill with your primary weapon.
* You cannot gain more charges than the number of charges you had at mission start.

## Sentinel
+1 to Overwatch shots.

## Serial
While in Serial, your primary weapon attacks that kill are refunded. Penalties to damage and crit per primary weapon kill in Serial this turn.
* -{{ SERIAL_DAMAGE_PENALTY }} primary weapon damage per kill in Serial mode until the start of your turn.
* -{{ SERIAL_CRIT_PENALTY }} primary weapon crit per kill in Serial mode until the start of your turn.
* {{ COOLDOWN }}

## Shadow
Enter Shadow. In shadow, you have +{{ SHADOW_MOB }} mobility and enemies have {{ SHADOW_DETECTION_RADIUS }}% reduced detection range against you.
* 2 turn duration.
* {{ COOLDOWN }}

## Shadowstep
Enemy reaction attacks no longer trigger against you.

## Shadowstrike
+50 aim and +50 crit in concealment.

## Shield Bash
Bash an adjacent enemy with your shield, doing some damage and knocking back the target 2 tiles. Free action.
* The damage is equivalent to the base damage of the currently equipped shield.
* {{ COOLDOWN }}
* Can target enemies in adjacent tiles on the diagonal as well.

## Shooting Sharp
+2 pierce and +15 aim with your ranged attacks against units in cover.

## Shredder
+1/+1/+2/+2/+3 shred with your primary weapon.

## Silent Killer
You are no longer revealed when you kill with your primary weapon in Shadow.

## Slash
Attack an adjacent enemy with your sword.
* {{ AP1 NTE }}

## Slug Shot
Fire a shot with +2 pierce, +10 aim, and no aim penalty from long range. Requires a shotgun.
* {{ COOLDOWN }}

## Smoker
You start the mission with +1 Smoke grenade.

## Snap Shot
Fire your sniper rifle with one action remaining. This attack suffers severe aim penalties against targets beyond 5 tiles of your sight range.\
Passive: Many {{ ClassName }} abilities can be used after moving with the same aim penalties.
* Abilities you can use with one action remaining: Deadeye, Precision Shot, Disabling Shot, Chain Shot, Rapid Fire.
* You may not enter Overwatch with one action remaining.

## Soul Harvest
+4 crit per enemy you have killed this mission, up to +20.\
Passive: +10 crit.

## Squadsight
Your primary weapon attacks can now target units outside your sight range if they are seen by a squadmate.
* You still need line of sight to the target.
* There is no limit on how far your targets can be, but there is an aim penalty that increases with distance.
* Overwatch attacks are not fired at squadsight range.

## Steady Hands
+10 aim and +10 crit if you did not move last turn.

## Stiletto
+3 pierce with your primary weapon.

## Sting
Fire a shot that Ruptures for 1 and Holo Targets for +10 aim. Must be fired from Shadow. Does not reveal you.
* {{ COOLDOWN }}

## Sting Grenades
Your flashbang grenades have a 50% chance to stun enemies.
* Flashbang resistance does not mitigate Sting Grenades' stun chance.

## Street Sweeper
Attack enemies in a cone. +3 damage against unarmored targets. Blocked by high cover. Requires a shotgun.
* Range: {{ STREET_SWEEPER_RANGE }}
* {{ AMMO }}
* {{ COOLDOWN }}

## Strike
Dash to an enemy within movement range and punch it in the face.
* Damage improves with armor tier.

## Stun
Fire your arc thrower to stun a non-robotic enemy for 2 actions.
* {{ AP1 ET }}
* {{ COOLDOWN }}
* Stun duration increases with arc thrower tier.

## Stun Gunner
+20 aim with arc thrower attacks.
* Aim bonus increases with arc thrower tier.

## Stun Strike
Stun an enemy for 2 actions. 85% chance to hit at 1 Focus. +5% chance to hit per Focus.
* {{ FOCUS1 }}
* {{ AP1 NTE }}
* {{ COOLDOWN }}
* Cannot target units larger than 1 tile.

## Superior Aptitude
+1 Focus after you attack with Rend.

## Suppression
Suppress an enemy. Suppressed enemies have -25 to aim, are unable to use many abilities, and you will fire a reaction shot if they move.
* Examples of abilities restricted by Suppression include rocket launches and grenades throws.
* {{ AMMO }}
* {{ COOLDOWN }}
* Ends if you fire the reaction shot.
* Ends at the start of your turn.
* Ends if you take damage.
* Cannot be used with a sniper rifle or shotgun.

## Survival Instinct
+20 defense and +20 crit while not at full health.

## Sustain
Once per mission, when you take lethal damage, you will instead survive with 1 HP and enter Stasis until the start of your turn.
* Entering Stasis will not remove damaging status effects, like poison, burning, or acid burning.

## Tactical Sense
+3 defense per enemy in sight, up to +15.
* Units visible at squadsight ranges do not confer bonus.
* This ability does not provide defensive bonuses if the unit is disoriented, stunned, panicking, on fire or otherwise impaired.
* TODO: What's the visibility rule?

## Tandem Warheads
Your explosive damage no longer suffers from falloff.
* This does not apply to environmental damage.

## Target Focus
+10 aim and +1 pierce to ranged attacks against unflankable enemies.

## Templar Shield
You are in low cover. You are a low cover object.

## Terrorize
Volt has a chance to panic on hit. The chance is based on a contest of wills.
* TODO: What's the base chance?

## That's Close Enough
During enemy turns, you automatically reaction fire your arc thrower against an enemy that moves or attacks in a 1 tile range. Shares cooldown with arc thrower Stun.
* Will not trigger if you are concealed.
* Works during any enemy turn: Alien, Lost, Chosen and Ruler.
* TODO: Is the last one really necessary?

## Threat Assessment
Your Aid Protocol target will enter Overwatch. Your Aid Protocol target has Covering Fire for the duration of the buff.
* TODO: Does it work that way?

## Total Combat
Grenade throws and item uses no longer end your turn. Grenade throws have no cooldown. Gain a grenade slot. Gain Volatile Mix. +3 grenade throw range. +5 aim. +1 mobility.
* Volatile Mix: +1 to grenade radius.

## Tracking
You detect units in a {{ TRACKING_RADIUS_TILES }} tile range even without line of sight.
* You can not see the detection ranges of units that you detect but do not see.
* You can not directly target detected units that you do not see.
* Units will remain detected until the end of the player's turn. If they are outside Tracking's range at that point, they will count as no longer detected.

## Tradecraft
This soldier has significantly reduced infiltration times while on missions.
* TODO: How does this work?

## Traverse Fire
Gain a non-movement action after you fire a standard shot with two actions remaining.

## Trench Gun
Attack enemies in a cone. Blocked by high cover. Requires a shotgun.
* Range: {{ TRENCH_GUN_RANGE }}
* {{ COOLDOWN }}

## Trench Warfare
You will Hunker Down at the end of your turn if you killed on your turn turn.
* You will only Hunker Down if you would normally be able to.

## Trojan
When your hack ends, the hacked unit takes up to 8 damage and loses its actions.
* Trojan deals 1 damage per successful contest of your hack against the target's hack defense.

## Unlimited Power
Firing your arc thrower no longer ends your turn.

## Untouchable
Once per turn, you become Untouchable until the start of your turn on kill. While Untouchable, damaging attacks against you are forced to miss. When this happens, you are no longer Untouchable.

## Vital Point Targeting
Your holotargeted enemies take +1/+2/+2 damage.
* Applies to Holo Targeting, Rapid Targeting, and Multitargeting.

## Void Conduit
Imprison a humanoid enemy for 2 turns and deal {{ VOIDCONDUITDMG }} damage to it. Deal {{ VOIDCONDUITACTIONDMG }} damage to it when it loses an action to imprisonment. Damage is stolen to you as health. Costs 1 Focus.
* Imprisoned units cannot use actions or dodge, but can be targeted by other attacks.
* {{ COOLDOWN }}
* TODO: Is the flat damage also stolen?

## Volatile Mix
+1 to grenade radius.

## Volt
Deal guaranteed damage to a non-robotic enemy and other non-robotic enemies in a {{ VOLT_RADIUS_TILES }} tile radius around it. -15 to targets' defense on hit.
* {{ AP1 NTE }}
* {{ FOCUS1 }}
* {{ COOLDOWN }}
* {{ VOLT_DEBUFF_DURATION }} turn duration.
* Cannot be used when concealed.

## Walk Fire
Fire a shot with +30 aim, 34% less base damage and -30 crit.
* Consumes 2 ammo.

## Watch Them Run
You will enter Overwatch after you throw or launch a grenade.

## Weapon Handling
67% less aim penalty from short range with primary weapons.

## Whiplash
Attack an enemy in visual range with your Ripjack. Deals bonus damage against robotic enemies.
* {{ AP1 NTE }}
* {{ COOLDOWN }}

## Whirlwind
Once per turn, you gain a movement action when you hit an enemy with a melee attack.

## Will To Survive
-1 damage taken from enemies that are not flanking you.\
Passive: +5 will.
* -1 damage taken from explosives and other indirect attacks if you are not flanked to their center tile.
* This ability does not provide defensive bonuses if the unit is disoriented, stunned, panicking, on fire or otherwise impaired.

## Wrath
Use the Grapple to pull yourself to an enemy and attack with your Ripjack.
* Only the pull is subject to an aim roll. The Ripjack attack is guaranteed to hit.
* Requires an empty tile adjacent to the enemy.
* {{ COOLDOWN }}

## Wrecking Ball
While in Overdrive, you will destroy cover and environmental objects while moving.

## Zone of Control
All enemies in a {{ ZOC_RADIUS_TILES }} tile range have -15 to aim and -4 to mobility.

## Clutch Shot
Fire a pistol shot that is guaranteed to hit.
* {{ CHARGES }}

## Faceoff
Fire your pistol at all enemies in sight.
* {{ COOLDOWN }}
* Cannot be used when concealed.

## Fan Fire
Fire three pistol shots with -{{ FAN_FIRE_AIM }}.
* {{ COOLDOWN }}

## Gunslinger
Enter Gunslinger Overwatch. While in Gunslinger, you will fire a reaction pistol shot against all enemies that move or attack in a 8 tile range. Gunslinger attacks are guaranteed to hit and crit.
* {{ COOLDOWN }}
* Cannot be used from concealment.

## Lightning Hands
Fire your pistol.
* {{ AP0 }}
* {{ COOLDOWN }}

## Quickdraw
Your standard pistol shot no longer ends turn. +1 mobility if you're carrying a pistol.

## Magnum
Standard pistol shots have no long range penalty.
* Only applies to standard pistol shot and pistol overwatch.

## Air Controller
-2 to evac timer.
* Evac timer still has a minimum of {{ EVAC_TURNS_MIN }}

## Collector
Squad members have 33% chance to gain 1 intel on non-human enemy kills while you have full health.
* TODO: Is it actually full health, or not taken damage this mission, or have not been wounded this mission?
* TODO: Does it apply to the Officer?

## Combined Arms
Allies in Leadership range deal +1 damage.

## Command
Give an action to a visible organic squadmate.
* {{ AP1 ET }}
* {{ CHARGES }}
* +1 charge if rank is at least Captain.
* +1 charge if rank is at least Lieutenant Colonel.
* +1 charge if rank is at least Field Commander.
* Cannot be used on Overwatching or Suppressing units.

## Commissar
+50 aim, ignore all dodge, and Execute on hit with pistol shots against allies that are mind controlled by an enemy.
* TODO: What does it mean in this context to Execute?

## Defilade
Squad members in Leadership range have +5 to cover defense.
* TODO: Does this apply to the Officer?

## Fire Discipline
Allies in Leadership range have +10 aim with reaction attacks.
* TODO: Does this apply to reaction shots, or reaction attacks?
* TODO: Does this apply to the Officer?

## Focus Fire
Debuff a visible enemy to have -1 armor and -5 defense until the start of its turn. The defense penalty increases by 5 every time the target is attacked with an attack subject to an aim roll.
* {{ AP1 NTE }}
* {{ COOLDOWN }}

## Get Some
Give +20 crit to all allies in Leadership range until the end of their turn.
* {{ AP1 NTE }}
* {{ CHARGES }}
* TODO: Does it really tick at the end of their turn?

## Incoming!
Give +4 explosive damage resistance to all allies in Leadership range until the start of your turn.
* Does not apply to panicked soldiers or units suppressing other targets.
* {{ AP0 }}
* {{ COOLDOWN }}

## Infiltrator
The officer's squad will infiltrate enemy targets more quickly.
* TODO: What does this actually do?

## Intervention
Spend 10 intel for +2 mission timer.
* {{ AP1 NTE }}
* {{ CHARGES }}
* TODO: Number of charges increases with officer rank. But how many at which ranks?
* Intervention does nothing if there is no mission timer.
* TODO: Can it be used on missions without timer? Is it a no-op? Does it still consume intel?

## Jammer
Delay the arrival of imminent enemy reinforcements by one turn.
* {{ AP1 ET }}
* {{ CHARGES }}
* Only works if the reinforcements will enter next turn.
* If reinforcements are also queued for the enemy turn after the next one, Jammer will cause two waves of reinforcements to enter that turn.

## Lead By Example
Squadmates in Leadership range have aim, will and hack bonuses equal to half the stat difference between you and the ally.
* If the squadmate has a higher stat, the Lead By Example bonus for that stat does not apply.
* TODO: Does it apply to SPARKs?

## Leadership
Squadmates have will, dodge and infiltration bonuses per successful mission they have served under your command.
* TODO: Give me some numbers.

## Oscar Mike
Give +5 mobility to all allies in Leadership range until the end of your turn.
* {{ AP1 NTE }}
* {{ CHARGES }}
* All allies, or all squadmates?

## Scavenger
30% more supply, Alien Alloy and Elerium Crystal rewards from successful missions. Squad members have a chance to gain Alien Alloys and Elerium Crystals from alien kills.
* Multiplicative reward bonus only applies if you survive the mission and are conscious at the end of it.
* TODO: How does the latter half actually work?

## Trial By Fire
Squadmates below Sergeant rank gain experience to be promoted to their next rank at the end of the mission.
* Squadmates that otherwise gained enough experience to be promoted do not gain any bonus experience.
* Trial By Fire does not promote squadmates directly to Sergeants, only to their next rank.
* This bonus only applies if the commanding officer has this perk, and it does not give bonuses to other officers on the mission.
* TODO: Does this work on SPARKs?
* TODO: Does this really not work for officer trained people?

## You'll Need This
Give a conventional pistol to an allied civilian.
* You carry a spare conventional pistol if you have a pistol of any kind in your inventory.
* You have no mobility penalty from the spare conventional pistol. -1 mobility to the ally that receives the spare conventional pistol.
* Note: This ability will not appear in your Tactical ability icons unless you can use it.
* TODO: What does the last part mean? Is it a UX bug?

## Bastion
Your allies in a {{ BASTION_RADIUS_TILES }} tile range are immune to fire, poison, acid, and explosive damage.
* Moving into range of an ally with any of the listed effects will remove the effects.

## Domination
Permanently mind control an enemy in sight.
* Requires a contest of your psi versus the target's will.
* {{ CHARGES }}
* Failed attempts do not consume charges.
* {{ COOLDOWN }}
* Domination ends if you die, become mentally impaired, or evac.

## Fortress
You are immune to fire, poison, acid, and explosive damage.

## Fuse
Detonate the explosive of a visible enemy or corpse.
* {{ AP1 NTE }}
* {{ COOLDOWN }}

## Insanity
Disorient, panic or mind control a non-robotic enemy in sight.
* {{ AP1 NTE }}
* {{ COOLDOWN }}
* Requires a contest of your psi and target's will.
* If you win the contest, there is a 10%/85%/5% chance to disorient, panic, or mind control the target.
* TODO: Check the above numbers.

## Mind Merge
Give bonus ablative HP, will, and crit to a visible ally.
* Base bonuses are +1 ablative HP, 0 will, and 0 crit.
* +1 ablative HP per 20 psi, +1 will per 5 psi, and +1 crit per 7 psi.
* {{ AP1 NTE }}
* {{ COOLDOWN }}
* {{ DURATION }}
* Flat bonuses improve with psi amp tier.
* Passive: 40% less chance to recruit Faceless when you are the Haven adviser.

## Null Lance
Deal guaranteed damage in a line with {{ NULL_LANCE_LENGTH }} tile length.
* {{ COOLDOWN }}
* Damage improves with psi amp tier.
* TODO: Armor and ablative pierce?

## Null Ward
Give +3 ablative HP to allies in a {{ NULL_WARD_RADIUS_TILES }} range.
* Null Ward gives 3 ablative hit points.
* {{ COOLDOWN }}
* Reveals you.
* The effect ends if you die or evac.
* Ablative HP increases with psi amp tier.

## Phase Walk
Teleport to a tile in a {{ PHASE_WALK_RANGE_TILES }} range that in sight of the squad.
* {{ AP1 NTE }}
* {{ COOLDOWN }}
* Does not trigger Overwatch, but can trigger other reaction attacks.

## Quick Study
50% less Officer training time.

## Solace
Remove a disorientation, stun, panic, or mind control from an ally in sight.
* {{ AP1 NTE }}
* {{ COOLDOWN }}

## Soul Steal
You gain +3/+4/+6 ablative HP after you cast Soulfire. Damage is stolen to you as health.
* Soul Steal will not increase ablative HP over 15.

## Soul Storm
Deal guaranteed damage and environmental damage in a {{ SOUL_STORM_RADIUS }} tile range.
* Cannot destroy floors or ceilings.
* {{ AP1 NTE }}
* {{ COOLDOWN }}

## Soulfire
Deal guaranteed damage a non-robotic enemy. Pierces all Armor and ablative HP.
* {{ COOLDOWN }}
* Damage increases with psi amp tier.

## Stasis
Place a unit in Stasis. Units in Stasis cannot gain actions until the start of your turn, but are immune to damage and untargetable.
* Both allies and enemies can be targeted.
* Cannot target units larger than 1 tile.
* {{ COOLDOWN }}

## Void Rift
Deal damage to units in a {{ VOID_RIFT_RADIUS_TILES }} tile radius around a tile in sight. Ruptures for 1. {{ VOID_RIFT_INSANITY_CHANCE }}% chance to cast Insanity to non-robotic targets on hit.
* {{ COOLDOWN }}
* Insanity casts on hit do not require vision to the target.
* Rupture effect increases with psi amp tier.

## Blood Thirst
Gain a stack of Blood Thirst when you attack with your melee weapon. +1 melee damage per stack. Each stack has a 3 turn duration.

## Fatality
+100 aim and +100 crit against targets with at 50% or less health.

## Grapple
Deploy a grappling hook to move to an elevated position.
* {{ AP0 }}
* {{ COOLDOWN }}

## Mark for Death
Mark a target for death. Your standard shots and Snap Shots with your primary weapon against the marked target are refunded.
* {{ AP1 ET }}
* {{ DURATION }}
* Reveals you.

## Overbearing Superiority
Your primary weapon single shot attacks that deal critical hits are refunded.

## Shieldwall
+30 defense and 5 armor until the start of your turn. You are a high cover object until you move or attack.
* TODO: action cost?

## Vampirism
Damage with your {{ BOUND_WEAPON_NAME }} is stolen to you as health.

## Wraith
Pass through environment and cover. 2 turn duration.
* {{ AP0 }}
* {{ CHARGES }}

## Get Up
Revive an unconscious ally and disorient it for a {{ GET_UP_DURATION }} turn duration.
* {{ AP2 }}

## Stock Strike
Deal 30% of the target's maximum HP as damage to an adjacent ally mind controlled by an enemy. Stuns for 1 turn on hit.
* TODO: Health scaling?
* TODO: Stuns for how long?
