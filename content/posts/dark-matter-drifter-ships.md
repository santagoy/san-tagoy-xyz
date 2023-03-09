---
author: Nico Santagoy
date: 2023-03-09
linktitle: Dark Matter Drifter, Ships
menu:
  main:
    parent: ttrpgs
title: Dark Matter Drifter, Ships
summary: |
  Almost everything about Starships for your Space-Western games!
categories:
  - setting
  - system
tags:
  - rules
  - sci-fi
  - combat
---

---

_Please check out Night-Tripper by Chris P. Wolf! Find the original rules for [Ship Travel](https://www.night-tripper.fun/chapters/rules-for-play/starships-travel/) and [Ship Combat](https://www.night-tripper.fun/chapters/rules-for-play/ship-combat/) in the original website. Night-tripper as a whole is just really cool and was a major inspiration for Dark Matter Drifter!_

_Some of these words aren't mine either, but I have a game on the 19th and need to prep for that one while balancing everything else in my life._

---

These rules cover small craft like light freighters, gunboats and pleasure yachts. Capitals and other large ships should be treated as set pieces and terrain. You won’t win in a fight against them.

Other than shuttles and other short-range craft, most ships are outfitted with a gate core. A gate core enables a ship to jump to gatespace and travel many times the speed of light. A ship can only enter or leave gatespace a significant distance from worlds or other large bodies.

## Ship Components

All measured from 1 to 6.

- Gate Core: Facilitates interstellar travel.
- Armor: In the form of ablative material or shields. The latter being for higher tech levels.
- Electronics: The speed, capacity, and power of the vessel's primary computer and sensor array. Anti-ordnance defense are included here.
- Thrusters: Speed and maneuverability granted by the vessel's realspace drive and thrusters.
- Guns: The number and power of weapons. Usually turrets armed with laser cannons.
- Ordnance: The potency of missiles and torpedoes aboard.
- Quarters: The number of staterooms on board. Luxury passengers and officers will expect a private room. Crew on military vessels sleep four to a room.
- Hold: The size of the vessel's cargo hold in Loads. 1 Load is the size of a real-world cargo container.

### Example Starships

| Ship             | Armor | Electronics | Thrusters | Guns | Ordnance | Hold | Quarters | Cost |
| ---------------- | :---: | :---------: | :-------: | :--: | :------: | :--: | :------: | :--: |
| Militia Gunship† |   2   |      1      |     3     |  2   |    1     |  1   |    1     | 70k  |
| Military Frigate |   4   |      4      |     1     |  3   |    4     |  3   |    4     | 300k |
| Trade Cog        |   1   |      1      |     2     |  0   |    0     |  4   |    2     | 85k  |
| Blockade Runner  |   1   |      2      |     4     |  1   |    2     |  2   |    1     | 200k |
| Pirate Raider    |   3   |      2      |     3     |  2   |    3     |  4   |    2     | 250k |

† No Gate Core. Incapable of Interstellar Travel without a carrier.

## Ship Combat

All rolls are 2d6 + relevant Skill. The Impact is always the higher of the two die. When attacking, determine Hit Location with the lower die.

Each crew member must take their stations on the ship: Computers, Helm, Guns, Ordnance, Engineering. With the exception of the Helm, all other stations with more than one crew member roll with Advantage. If no crew member can operate a station, they forfeit that turn.

> _A ship with electronics 1 and thrusters 2 starts an engagement with position 3._

Each crew determines their current goal for the encounter. The stated goal can change at any point during an encounter. Alternatively, a crew may surrender granting the enemy their goal.

Not every enemy will be so merciful as to accept surrender.

Position represents how close a ship is to achieving its goal. Assign each ship a Position determined by the sum of their electronics and thrusters.

First to reach the requirements of their goal at the end of a round reach their desired outcome.

| Goal                                    | Requirements                                                                                                    |
| --------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| Escape by jumping to gatespace          | Position 3 greater than enemy's and fully operational gate core.                                                |
| Forcibly dock with and board enemy ship | Position 3 greater than enemy's and enemy thrusters and guns are destroyed.                                     |
| Scuttle the enemy                       | Position 4 greater than enemy's and enemy gate core and thrusters plus 1 additional component are all destroyed |

Take the following steps each combat round:

1. Computer
2. Side 1 Helm vs Guns
3. Side 1 Electronics vs Ordnance
4. Side 2 Helm vs Guns
5. Side 2 Electronics vs Ordnance
6. Engineering

### Computer

Computer operators uses their ship's electronics to try to predict the enemy's movement. Each side rolls 2d6 + Computer + electronics.

The side with the higher roll attacks first. Ties are broken by the crew with higher Impact or Position. If the tie remains, the referee may rule accordingly.

### Attacks vs Defenses

These are a series of contested rolls. Higher Impact or Position break ties. The winner always adds their Impact to their Position at the end of the round.

Position can be traded 1:1 to increase or decrease their own Hit Location die or that of the enemy.

#### Hit Location (1d6)

| Roll | Hit Location and Effect                                                                                                                                                       |
| :--: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  1   | Quarters                                                                                                                                                                      |
|  2   | Hold                                                                                                                                                                          |
|  3   | Electronics                                                                                                                                                                   |
|  4   | Guns or Thrusters                                                                                                                                                             |
|  5   | Gate Core or Ordnance. If latter, roll 1d6 to determine damage in an additional area.                                                                                         |
|  6   | Attacker chooses where or the Helm/Bridge. If the latter and armor is penetrated, all crew in that area take the impact. Hit location is determined randomly per crew member. |

#### Helm vs Guns

The Helm rolls 2d6 + Piloting + thrusters against the enemy's 2d6 + Gunnery + guns. Should the Helm roll higher, the ship dodges incoming fire.

Should the gun station roll higher, the Impact must exceed the Ship's armor rating to damage.

If a tie remains after resolution, **the helm wins by default.**

#### Electronics vs Ordnance

The stationed crew rolls 2d6 + Computer + electronics against the enemy's 2d6 + Gunnery + ordnance. Should the defender roll higher, the ship's defenses prevail! Add the Impact to the Position.

Should the ordnance station roll higher, the attacker scores a direct hit! Ordnance ignores armor that aren't shields.

If a tie remains after resolution, **the ordnance wins by default.**

#### Ship Damage

The first time a component is hit, it is damaged. The second time, it is breached. The third time, it is destroyed.

Damaged components roll with Disadvantage.

Breached components force those stationed there to make d20 + Athletics roll. 12+ means they hold on for dear life before failsafes activate. Any lower means they are forcibly pulled into the vacuum of space.

Once a component is destroyed, all stationed there take the impact of the hit +1d6, ignoring armor. Hit location is determined randomly per crew member.

### Engineering

Each ship's engineer rolls 1d20 + Engineer. On a 14+, they may either jury rig a damaged component, or boost an intact component to grant one teammate advantage on their throw during the next round. Jury rigged components operate as normal during the next round. Destroyed components cannot be jury rigged, and need to be replaced in port.
