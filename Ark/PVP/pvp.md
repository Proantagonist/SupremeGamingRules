This ruleset applies **ONLY** to the following servers:
 
1. **Supreme Ark Genesis PVP** 


&nbsp;

### **General Disclaimer**

The general operation of these rules is more ‘spirit of the law’ mindset rather than a ‘letter of the law’ mindset, and as such are purposely loose. The absence of an item in these rules does not imply permission. If an item appears to not be in line with the following ruleset, then it is most likely to be frowned upon. Please use common sense and err on the side of caution.

**All rules are ultimately dependent upon the judgment of the admin team. If questions arise with regards to these rules, please do not hesitate to contact an admin for clarification.**

&nbsp;

### **Global Rules**

1. No glitching, abusing, meshing, bug or other mod exploits. 
1. No racism, sexism, or hate speech either on the server or on the Discord. This extends to Discord and in-game names/aliases as well.
1. No harassment or personal attacks upon other players either in the game or on discord. (This includes things such as handcuffing a player for a significant amount of time, spawn-camping, repeatedly raiding someone in a short period of time, or steamrolling defenseless tribes.) 
1. No blocking or impeding access to loot crate or artifact spawns. 
1. No C4/rocket running. This includes any method to quickly get to turrets and blow them up point-blank with explosives.
1. No dino armor or boxes to prevent 100% line of sight, or picking of riders on platform dinos during raids.

&nbsp;

### **Punishments**

Punishment for breaking of rules is dependent upon the severity and circumstances of the rulebreak. Issues are dealt with on a case-by-case basis rather than the addition of new rules.

*NOTE:  Breaking of Rule 1 is grounds for immediate and permanent ban, while other rule violations are subject to either a temporary ban or other punishments determined by the admin team.*

### **Main Settings**


- **Max Player Level**: 120 + Ascensions
- **Max Wild Level:**: 120
- **Gathering**: 8x
- **XP**: 8x
- **Taming**: 15x
- **Egg Hatch Speed**: 15x
- **Baby Mature Speed**: 15x
- **Imprint Interval**: 0.20x
- **Floating Damage Text**: True
- **PVP Dino Decay**: True
- **PVP Structure Decay**: True
- **Max Players in Tribe**: 10
- **Spikes Damages Wild Dinos**: True

#### Per Level Stat Multipliers

- **Player Weight**: 3x
- **Tamed Dino Weight**: 3x


### *Super Structures Additional Settings*

- **Elevator Weight Multiplier**=5
- **Elevator Speed**=350
- **Disable Pickup When Damaged**=true
- **Grinder Resource Return Percent**=25
- **Grinder Resource Return Max**=500
- **Disable Ability To Place Vacuum Compartments Above Water**=true
- **Disable Ability To Place Tek Generator On Saddles**=true
- **Disable Ability To Place Teleporter On Saddles**=true
- **Allow Admin To Demo Any Tribe With Demo Gun**=true
- **Disable Dino Scan**=true
- **Disable Dino Scan Details**=true
- **Disable Dino Scan Map**=true
- **Allow Intake To Place Without Water**=true
- **Mutator Pulse Cost**=100
- **Mutator Buff Max Stack Count**=2
- **Minimum Glass Transparency**=0.1
- **Disable Vivarium Placement On Saddles**=true
- **Mutator Prevent Breeding Cloned Or Neutered**=true

### *Dino Storage v2 Additional Settings*

- **BuffsPreventTrapping**=True
- **Exclude Big**=True
- **Exclude Boss**=True
- **Exclude Raid**=True
- **Keep Ally Looking Status**=True
- **Keep Ignore Whistle Status**=True
- **No Combat Trap**=True (cannot trap while in combat)
- **Trap Health**=0.1 (Minimum HP you can trap a dino - 10%)
- **Enemy Structure Range**=25.0 (range in foundations you can release a dinoe)
- **LootBag Life Span**=60.0 (Minutes bag will remain if you store them and they drop a bag)
- **Release Consumes Trapper**=False
- **Release Prevent DupeID**=True (checks for duplicates)
- **Release Tribe Logs**=True (Creates Tribe Log entry for release)
- **Require Ownership**=True (You must personally or tribe own the dino)
- **Require Tribe Ranks**=True (Governance can be set for release)
- **Trapping Tribe Logs**=True (Creates Tribe Log entry for trapping)
- **Disable Terminal Pickup**=False
- **Terminal Exclude All Platforms**=True (Will not accept platform saddles)
- **Terminal Tribe Limit**=2 (Maximum number of terminals you can own)
- **Distribute Fertilizer Range**=30 foundations
- **Distribute Pellet Range**=30 foundations
- **Enable All Generation**=True (Eggs, Poop, Pellets, Acharins PAste, etc will continue in the terminal)
- **Enable Fert Egg Collection**=True
- **Enable Fruit Seeding**=True
- **Enable Incubation**=True
- **Enable Poop Conversion**=True (will convert to fertilizer if Dung Beetle is in Terminal)
- **Terminal Egg Multiplier**=1.0
- **Terminal Misc Poop Multiplier**=1.0
- **Terminal Passive Multiplier**=1.0
- **Terminal Poop Multiplier**=1.0
- **Terminal Wool Multiplier**=1.0
- **Terminal Slots**=500
- **Unlock Tribute Terminal**=True (Can use as a tribute terminal)
- **Vault Terminal**=True (will fall like a vault if support below it is destroyed)
- **Prevent Offline Mating Interval**=16 hours (max offline time before mating will stop)

### *Plugin settings and how to use them*

#### **MAGA**

MAGA includes ORP, PvP cooldown, Suicide Command, DinoStats command and anti-popcorning

- **Disabled Structure Damage** = Cannon (meaning cannons cannot damage structures)
- **Blocked items while in PvP** = Remote Demolisher, Remote Transfer Tool, Personal Teleporter, Remote Transparency Cycler, SS Item Translocator
- **Disabled commands while in PvP** = /suicide, /shop, /kit, /buy
- **Popcorn Cooldown** = 3 seconds 100 items max (meaning you can only drop 100 resources every 3 seconds during PvP)
- **Popcorn restricted items** = Blueprints, Drop All button
- **Other restrictions** = Suicide while handcuffed, suicide while unconscious 

##### *ORP Settings*
- **Time to Activate** = 5 min
- **Time to Activate if in PvP** = 120 min
- **Max ORP Duration** = 7 days (168 hours)
- **Disable ORP Dino Carry** = True
- **Damage taken while in ORP** = 0%
- **Turret ammo while in ORP** = Infinite
- **Max Number of ORP locations** = 2
- **Max ORP range** = 15000 (50 foundations diameter)

##### *ORP Commands*
- **/setorp <name\>** = Sets ORP at your current location and names it
- **/setorp <id\> <name\>** = Replaces ORP id with current location
- **/listorp** = Lists current ORPs
- **/removeorp <name\>** = Removes the named ORP
- **/orp** = Will let you know if you're inside your own ORP

##### Other MAGA commands
- **/dinostats** = Prints the base stats of the targeted dino
- **/ds** = Short version of /dinostats
- **/suicide** = kills your player

#### **Raid Balancer**

Raid Balancer helps to mitigate the issue of large tribes attacking much smaller tribes and rolling them simply due to numbers.

When a tribe attacks another, the damage done by the defending tribe's defenses will increase based on the ratio of attackers to defenders. For example, if Tribe A with 2 people is attacked by Tribe B with 4 people, Tribe B will take 200% damage from Tribe A's turrets. If Tribe B moves 2 people away from the raid area (approx 85 foundations) then it will rebalance and Tribe B will only take 100% normal damage.

