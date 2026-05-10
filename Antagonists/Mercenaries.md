# THE MERCENARIES
## Overview
**Mercenaries** are a roundstart/midround **Team-Based Free Agent** with  goals centered mainly around making money, and causing slight damage to the station as they go about it. The purpose of this proposal is to add a bit more danger to the money-printing process, and **Cargo**'s gameplay loop as a whole, while still providing meaningful roleplay potential for antagonists and crew alike. The Mercs themselves are split into two roles. A **Mercenary Boss**, who is intended to remain on the ship, act as the brains of the operation, and coordinate the rest of the group. The other role are the **Mercenary Freelancers**, the muscle of the Mercs, and will ideally be the ones that go out onto the station and complete their goals there.
## Flavor Text: Mercenary Freelancer
> I am the **Mercenary Freelancer!** As an elite employee of the Sirius Paramilitary Group, I've got to follow the orders of the Boss, and make a little money for myself on the side.
### Mercenary Freelancer Gear:
>Active Bomb Collar

> Random Ballistic Weapon

>Cerberus Hardsuit


###### (The Cerberus Hardsuit is a no-slowdown armor with slightly worse stats than a traditional Syndicate Hardsuit, but they get slightly faster when near another Cerberus, with the buff maxxing out when three Freelancers are moving together. The current design uses a base of the [USSP Tacsuit](https://github.com/Monolith-Station/Monolith/tree/main/Resources/Textures/_Mono/Clothing/OuterClothing/Hardsuits/ussp_combat.rsi), and the only major resprite needed is a more dog-shaped helmet, in order to fit in with the themes of the Sirius Group.

## Flavor Text: Mercenary Boss
> I am the **Mercenary Boss!** I need to ensure that the **Siphon** is activated, and that I complete any additional contracts given to me by the higher ups... or anyone with enough money to make it worth my while. 
### Mercenary Boss Gear:
>**Remote Detonator**

###### (This can also activate Insurgent bomb collars if interacted with.)
> **Spare Deactivated Collars**

> **Exotic Coat**

###### (Green reskin of cap's armored jacket, but is also insulated against cold.)

> **The V3NOM-5 Arm**

###### A piece of highly illegal cyberware that deals heavy stamina damage if hit on non-lethal mode, or if swapped to lethal mode,  shoots a rocket punch. (spare hands included)

## Mechanics
Mercenaries will spawn if Cargo has been printing suspicious spesos, and placing them into the console, scaling with the amount of suspicious spesos deposited, or if overall station accounts reach a surplus of over 100,000 spesos. When either of these events trigger, the following announcement(s) will play. 
>**"Attention crew, it has been discovered that this station has been paying the non-interference fees for the Sirius Paramilitary Group in counterfeit currency, and after this discovery, a nearby Sirius shuttle has gone rogue and entered your sector."**
>
>"**Attention crew, it appears that the true value of the station accounts have been leaked to the Sirius Paramilitary Group by a competitor, please prepare for the arrival of a rogue shuttle.**"

They also have a chance to spawn naturally as a midround, or through Ninja's hacking of the comms console with the following announcement.
> **"Attention crew, it appears someone on your station has made an unexpected communication with a paramilitary group of uncertain loyalty."**

## Gameplay Loop: Preperation
Mercenaries spawn inside their shuttle, the **Hellhound**, and the first thing that they'll be doing is grabbing their respective gear. (The Boss will be implanting his prosthetic arm and putting on his gear, and the Freelancers will be getting their Cerberus Hardsuits and weaponry.) The time spent gearing up and strategizing for their objectives shouldn't take too long, as the Mercs don't have that much to their name, and as a midround, they won't have that much time to begin with.
## Gameplay Loop: On the Station.
After the Mercs have geared up, they're intended to FTL to the station and begin seeking out ways to make money and complete their initial objectives, as well as finding a place to place their **Siphon**, which functions as their primary goal. The **Siphon** can only be placed on a specific part of the station, similar to the **Ninja**'s bomb, or the **Entropic Colossus**'s effigy. However, unlike the other two, there will be an announcement played when the **Siphon** begins to actually... siphon, and the **Mercenary Freelancers** will be expected to defend the **Siphon**, similar to **Nuclear Operatives** and their Nuke. The **Mercenary Boss** can choose to either start the **Siphon** immediately with their initial gear, or to try and complete their secondary objectives first. 
## Gameplay Loop: Space.
As a space-based midround, the Mercenaries will be spending a fair portion of their time on their shuttle, mechanically incentivized through reloading their weapons, transporting prisoners to their brig, and attaching bomb collars to potential "recruits". However, the **Freelancers** should be mainly on-station, in order to complete their objectives, so the main person who will remain in space is the **Mercenary Boss**, the boss will serve as the priority target that security has to take out, because they have items on them that will allow security to either execute/take control of the remaining Mercenaries. Ideally, the **Boss** should be strong in single combat, but weak when facing a coordinated group without their own **Mercenaries** behind them. This will reward the **Mercenary Boss** if they are proficient in coordinating their **Freelancers.** 
## Shuttle Design.
The shuttle itself, the **Hellhound**, will be unable to hide its IFF, and is extremely large in size. It will make up for its obviousness with Mercenary-locked doors, but will be largely defenseless in regards to turrets and the like, as it's primarily a troop carrier/mobile prison. It will run on the AME, which could be overloaded and explode, crippling the Mercs. However, the Mercenary armory is stocked with ballistics, and anybody breaking into the **Hellhound** will likely find themselves met with deadly force. The current plan for shuttle design is to retrofit the retired Monolith ship design of the **[Flashpoint](https://github.com/Monolith-Station/Monolith/pull/3320)**, and change it to fit Trauma Station. It will most likely be done via downscaling it, and removing excess departments within.
## In-Game Aesthetic
The mercenaries aren't as advanced as the corporations they work for, so any gear that they have should either be from a different company, but retrofitted to be used by the mercenaries, or feel run-down and slightly outdated yet well-maintained. The primary color scheme of the mercenaries is a more faded green, as to not overlap with the brighter greens of Central Command gear. The primary theming of gear made by the Sirius Paramilitary Group should be dog-themed, as to give them a more distinct feeling among other midrounds, and not bland or basic.
## Freelancer Objectives:
**Collect your Pay** 
(End the shift with 10,000 spesos on your person. 100% chance to roll.)

**Keep Collateral Low** 
(End the shift without more than 1-3 kills. 33% chance to roll. If this objective has failed when evacuation docks to CentComm, the Merc’s collar explodes.)

**Keep Collateral High.** 
(End the shift with at least 3-5 kills. 33% chance to roll. If this objective has failed when evacuation docks to CentComm, the Merc’s collar explodes.)

**Break Free!** 
(5% chance to roll, greentexts via having no bomb collar attached.)


## Boss Objectives:
**Activate the Siphon**.
(Activate the funds siphon. Instead of stealing existing funds from the station, this will either apply a flat 25% tax to all future orders from cargo, make research 25% more expensive to research, or explode any existing PTLs. 100% chance to roll.)

**Recruit at least X members to your group.** 
(50% chance to roll, will greentext if more conscious people are equipped with Bomb Collars by the time the shift ends. Scales with server pop.)

**Steal a Nuclear Device.**
(25% chance to roll, will greentext if the nuke is on the shuttle when evac docks to CentComm.)

**Have at least 1-3 members of Command in custody.** 
(25% chance to roll. Will greentext if a member of command is cuffed in your ship when evac docks to CentComm.)

**Cause Chaos.**
(1% chance to roll. Will always greentext.)

# Credits:
> Bias (The Hidden King) as a Bounty Author/Investor,
> Dr.Oktober as an Investor,
> Hideo "Game" Kojima, as an Investor, 
>NoElka, as the Coder, 
> idk, as the Spriter, and
>Graves as the Conceptguy.
